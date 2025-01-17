# Recon

Automated first-look recon script build for Hack The Box.

## Dependencies

- [`nmap`](https://www.kali.org/tools/nmap/).
- [`dirb`](https://www.kali.org/tools/dirb/).

## How to use

You can either install it or run the script. If you just want to run the script like this:

```
./recon $ip_address
```

If you want to use it everywhere, just run it like this:

```
bash ./install.sh
# Or
chmod +x ./install.sh
./install.sh
```

And after that you can run in the terminal the following command:
```
recon $ip_address
```

## How it looks?

The output is very simple, first you will get a normal `nmap`-like output:
![Output 0](./assets/output_0.png)

And then you will get a summary for the `Ports`, `Web services`, and so on:
![Output 1](./assets/output_1.png)
