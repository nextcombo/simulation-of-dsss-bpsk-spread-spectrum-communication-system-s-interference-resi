# Simulation of DSSS-BPSK Spread Spectrum Communication System's Interference Resistance (Cosine, Pulse Monotone, etc.) - [Included MATLAB Code]

The algorithm can adjust parameters such as coding method, signal-to-noise ratio (SNR), dry-to-wet ratio, type of interference, and interference power.  
Simulation results
MATLABCode% Note: Implementing the simulation of direct sequence spread spectrum communication system, modulation method BPSK.\n%**************************************************************************\nclear all;\nclose all;\nclc;\n    \n%*******************************************************************************************************************************************\n% Macro Parameter Setting\nMl     = 1;                 % Number of bits per symbol (modulation order)\nSymNum = 1000;              % Symbol Count\nSNJ1 = 2:2:12;              % Dry communication ratio\nSNJ = 2:2:20;               % Signal-to-noise ratio\nNumLoop= 200;               % Number of simulation loops\n​\n% Data encoding parameters\nEncode_type = 2;            %Encoding methods 1, unencoded; 2, convolutional encoding\nEncode_rate = 0.5;          %Encoding rate\nDecode_tlen = 5;            % Code Translation Tracking Length\n​\n% Spread Spectrum Code Initial Value Setting\nUserNum  = 1;               % Number of users\nSeqType  = 1;               % Sequence Type 1: m-sequence, Sequence Type 2: Gold sequence\nSeqstage = 9;               % The order of feedback registers\nptaps1   = [1 3];           % The coefficient of the first feedback register\nptaps2   = [2 3];           % Coefficient of the second feedback register\nReg1ini = ones(1,Seqstage); % First feedback register initialization\nReg2ini = ones(1,Seqstage); % Initialize the second feedback register\n​\n% Filter parameters setting\nalpha       = 1;            % Rolling factor\nfirlen      = 4;            % Filter order\nsample_rate = 4;            % Sampling rate\nTs = 1;\n​\n% Channel Characteristics Parameter Settings\ndelay_tau = 0;         \n​\n% Interference Characteristics Parameter Settings\nJ_type  = 1;                % Interference types: 1. Broadband interference, 2. Cosine monotone interference, 3. Pulse monotone interference\nJ_fs    = 1;                %Single-tone interference frequency\nJ_theta = 0;                %Single-tone interference phase\nJ_tone  = 0.2;              %Pulse single tone interference duty ratio\nJ_p = sqrt(2560);           % Interference power\n​\nEnd  

## Images

![DSSS-BPSK Spread Spectrum Communication System Interference Resistance Simulation (Cosine, Pulse Monotone, etc.) [with MATLAB code]](01.jpg)
![DSSS-BPSK Spread Spectrum Communication System Interference Resistance Simulation (Cosine, Pulse Monotone, etc.) [with MATLAB code]](02.jpg)
![DSSS-BPSK Spread Spectrum Communication System Interference Resistance Simulation (Cosine, Pulse Monotone, etc.) [with MATLAB code]](03.jpg)
![DSSS-BPSK Spread Spectrum Communication System Interference Resistance Simulation (Cosine, Pulse Monotone, etc.) [with MATLAB code]](04.jpg)
![DSSS-BPSK Spread Spectrum Communication System Interference Resistance Simulation (Cosine, Pulse Monotone, etc.) [with MATLAB code]](05.jpg)
![DSSS-BPSK Spread Spectrum Communication System Interference Resistance Simulation (Cosine, Pulse Monotone, etc.) [with MATLAB code]](06.jpg)
![DSSS-BPSK Spread Spectrum Communication System Interference Resistance Simulation (Cosine, Pulse Monotone, etc.) [with MATLAB code]](07.jpg)
![DSSS-BPSK Spread Spectrum Communication System Interference Resistance Simulation (Cosine, Pulse Monotone, etc.) [with MATLAB code]](08.jpg)
![DSSS-BPSK Spread Spectrum Communication System Interference Resistance Simulation (Cosine, Pulse Monotone, etc.) [with MATLAB code]](09.jpg)
![DSSS-BPSK Spread Spectrum Communication System Interference Resistance Simulation (Cosine, Pulse Monotone, etc.) [with MATLAB code]](10.jpg)
![DSSS-BPSK Spread Spectrum Communication System Interference Resistance Simulation (Cosine, Pulse Monotone, etc.) [with MATLAB code]](11.jpg)
![DSSS-BPSK Spread Spectrum Communication System Interference Resistance Simulation (Cosine, Pulse Monotone, etc.) [with MATLAB code]](12.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
