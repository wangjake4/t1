代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shuidangran.top/Article/details/gtvdtjszxt.html

Ruby: "Hello, #{name}!"
来源：http://dali.hfpthk.cn/Article/details/gtwnlriwwc.html

C#:   $"Hello, {name}!"
来源：http://dali.tianlin.xyz/Article/details/gtohyzfnxn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.wangshuangyany.cn/Article/details/gtyxmictkp.html

Py:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtavmjehhr.html

PHP:  "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtqhkqnpda.html

JS:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtbmxrbsmq.html

TS:   "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gtxbylntgb.html

Java: "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtorcedejj.html

Go:   "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gtzqjnqgqr.html

Ruby: "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtfhbxlyey.html

C#:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnpbmpiv.html

[A14] 注释写法
来源：http://dali.tian-w.cn/Article/details/gtazdhtyjs.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.c1oappe.top/Article/details/gtycdxpucd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtufclqwhd.html

JS:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gtqjjqblcb.html

TS:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gtylcszucv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yj20258.top/Article/details/gtgujuyapb.html

Go:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtddyjbzvz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hnxiangtu.top/Article/details/gtcwgdqmps.html

C#:   // 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtiwwwivrb.html

[A15] 空值判断与默认值
来源：http://dali.smart0.xyz/Article/details/gtmlytqncb.html

Py:   value = data or "默认值"
来源：http://dali.zhoulong.xyz/Article/details/gtnzenigzg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gtbyngvawr.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gtaujwkmmt.html

TS:   const value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gtcldxpnwa.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xylfe.cn/Article/details/gtiivcgasw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtendiicdw.html

Ruby: value = data || "默认值"
来源：http://dali.daria6918.cn/Article/details/gtckkqylxx.html

C#:   var value = data ?? "默认值";
来源：http://dali.smart0.xyz/Article/details/gtjmjzbnib.html

[A16] 真假值判断规则
来源：http://dali.shangyingyoupin.top/Article/details/gtpsohjgsi.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.bjfxy.top/Article/details/gtmdjctfyv.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.redwolf501.top/Article/details/gtjjgetszb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xuetiantiany.cn/Article/details/gtrveyqpxv.html

TS:   if (!x) {}
来源：http://dali.gotoacloud.top/Article/details/gtdhlqcjch.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.havefunace.top/Article/details/gtkzrpypko.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.aibaodan.cn/Article/details/gtczrdyuxf.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xylfe.cn/Article/details/gtxxvvluts.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.nwbrower.top/Article/details/gtxzzcigwc.html

[A17] 位运算
来源：http://dali.vqdsnc.cn/Article/details/gtvytfbwyr.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtvnhhtzgl.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtpfxskpeb.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtdpvznqvt.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtyocknibc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtiwyazxug.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtsgomdmrb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtpqaympsc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtzmyrsngi.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jinqigufen.top/Article/details/gtykxnzilm.html

Py:   ord("A"); chr(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjiapbfhz.html

PHP:  ord("A"); chr(65)
来源：http://dali.hongshengwenyu.top/Article/details/gtnspczsyl.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtcwcqhyug.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxinkj.top/Article/details/gtoqsludrj.html

Java: (int) 'A'; (char) 65
来源：http://dali.birdmap.top/Article/details/gthqtcphwk.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yj20258.top/Article/details/gtakptkbuu.html

Ruby: "A".ord; 65.chr
来源：http://dali.9152youxi.cn/Article/details/gtuimfwjcm.html

C#:   (int)'A'; (char)65
来源：http://dali.gaohongyu789.top/Article/details/gtvqmnlliu.html

[A19] 交换两个变量
来源：http://dali.jqgfzy.top/Article/details/gtygieasmp.html

Py:   a, b = b, a
来源：http://dali.jinqigfzy.top/Article/details/gtrkiajdae.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jianghu66.top/Article/details/gtppysexcs.html

JS:   [a, b] = [b, a];
来源：http://dali.xinyue.icu/Article/details/gtwcenagxc.html

TS:   [a, b] = [b, a];
来源：http://dali.yuanzhike.top/Article/details/gtlajzrate.html

Java: int t = a; a = b; b = t;
来源：http://dali.gzhubu.top/Article/details/gtqsuqzeop.html

Go:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gtnmtjdrqc.html

Ruby: a, b = b, a
来源：http://dali.havefunace.top/Article/details/gthtxegwlc.html

C#:   (a, b) = (b, a);
来源：http://dali.dianchejie.cn/Article/details/gtgjussvdt.html

[A20] 读取标准输入
来源：http://dali.birdmap.top/Article/details/gtfjppgybx.html

Py:   name = input("请输入：")
来源：http://dali.birdmap.top/Article/details/gtbbauthrm.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinghuilouyu.cn/Article/details/gtazebghuw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yj202588.top/Article/details/gtlpuwwmrc.html

TS:   // Node.js：readline 模块
来源：http://dali.hnxiangtu.top/Article/details/gthtdohjkn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.pengpengdd.cyou/Article/details/gtorxoywpd.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yangfankeji.com/Article/details/gtsabhenqg.html

Ruby: gets.chomp
来源：http://dali.9152youxi.cn/Article/details/gtrngdkyld.html

C#:   Console.ReadLine();
来源：http://dali.sweek.top/Article/details/gtgkizekvh.html

[A21] 保留指定小数位输出
来源：http://dali.zycfv.cn/Article/details/gtsiflxauy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cdnleiting.top/Article/details/gtkbdgjuff.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gtsznhiuyr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gtrtxavwga.html

TS:   (3.14159).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtdiktnpak.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gtrarumbbl.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gtmtbwpmec.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtvzfqwinl.html

C#:   3.14159.ToString("F2")
来源：http://dali.pycfn.com/Article/details/gtttomxarz.html

[A22] 获取字符串长度
来源：http://dali.birdmap.top/Article/details/gtczymwzas.html

Py:   len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivrwkzgo.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pengpengdd.cyou/Article/details/gtfedldhke.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zycfv.cn/Article/details/gtqhyejapo.html

TS:   s.length
来源：http://dali.jianghu66.top/Article/details/gtxxedhedh.html

Java: s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtciewgvla.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ehwqpu.com/Article/details/gtygtbogxb.html

Ruby: s.length
来源：http://dali.cashguo.top/Article/details/gtttjhrbun.html

C#:   s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxntqamp.html

[A23] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtxietzkdt.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gtcnijfsng.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hnxiangtu.top/Article/details/gttidfaitl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfstcviv.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xylfe.cn/Article/details/gtnwrjwggo.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gtsugsutze.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.chenlongwang.top/Article/details/gtoldqauun.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.daxiang520.top/Article/details/gtbvffrjac.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jiagoushi.top/Article/details/gtxymyogyh.html

[A24] 去除首尾空白
来源：http://dali.hammf.cn/Article/details/gtcjthuteu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ppjwa.cn/Article/details/gtdvooswji.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuuttmfz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sufxvd.cn/Article/details/gtjuhyyerc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cqqwz.cn/Article/details/gtrdwpajqm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.9152youxi.cn/Article/details/gtcsimoame.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtqkcqtubz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shangyingyoupin.top/Article/details/gtrdeysqqk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.mhx1999.top/Article/details/gtqvztcdko.html

[A25] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtlvfnnfwz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.birdmap.top/Article/details/gtclcvlhui.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtraiignez.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtyjjwmobq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gtttiebavg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gzhubu.top/Article/details/gtzlscninq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhixingplan.top/Article/details/gtwaxvidkq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shzxlz.cn/Article/details/gtcxnwccar.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gttlgagxam.html

[A26] 类型转换总览
来源：http://dali.zhiwuduotai.top/Article/details/gtdgarljhw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xziqi.cn/Article/details/gtwuxnwzwj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shuidangran.top/Article/details/gtemhfodkv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hfpthk.cn/Article/details/gtvhacindr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gogol.net.cn/Article/details/gtsphlfhsq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tianlin.xyz/Article/details/gtgboclydq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinqigufen.top/Article/details/gtuhsfbckc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yangfankeji.com/Article/details/gtinxyryai.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tianlin.xyz/Article/details/gtprxqygpi.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtpahmgpvc.html

B. 流程控制
来源：http://dali.chenlongwang.top/Article/details/gtdhpjglnv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtprdecujp.html

[B01] 条件判断 if / else
来源：http://dali.xziqi.cn/Article/details/gtbqfdvwyu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yvedp.cn/Article/details/gtrgukxorg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfmgndvdr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gtzjesvcxh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gtzjvdmqls.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtcarffsiz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cucudq.cn/Article/details/gtwdebwtwq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmglczgf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gtigtgwiti.html

[B02] 多分支 else if / elif
来源：http://dali.aibaodan.cn/Article/details/gtbexbxmsz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hysaishi.cn/Article/details/gtvamrhcfh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yuanzhike.top/Article/details/gtgbycbwmt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtcahvkifv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gtggtodgps.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtqojbryeu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tianlin.xyz/Article/details/gtillfhjlv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxinkj.top/Article/details/gtxrwmnjcf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtzhubwygs.html

[B03] switch / match / case
来源：http://dali.9152youxi.cn/Article/details/gtnbauaxkd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gtjhijemqk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtkwmhnjie.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtbeuxhaub.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtkyrtfvba.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmvgtnodm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zycfv.cn/Article/details/gtnzejrgpe.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.dashuyun.cn/Article/details/gtslmtxzam.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cheryme.top/Article/details/gtnpbeffpk.html

[B04] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gteyfggish.html

Py:   for i in range(10): print(i)
来源：http://dali.chenzaomai.com/Article/details/gtmvwkchci.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.daria6918.cn/Article/details/gtvrrmuliw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jiagoushi.top/Article/details/gtbwkcliuf.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.meibo888.top/Article/details/gtrrdavnaf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtcbmtognb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.andypj.xyz/Article/details/gtfvbaglbs.html

Ruby: 10.times { |i| puts i }
来源：http://dali.haohaochexian.top/Article/details/gtspfhomef.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ivvv.top/Article/details/gtdcexuzkv.html

[B05] 遍历数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gtpayosavc.html

Py:   for item in arr: print(item)
来源：http://dali.hysaishi.cn/Article/details/gtquqeucez.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.0kj1m.cn/Article/details/gtdvjnenls.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj202588.top/Article/details/gtxaxxteir.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.pycfn.com/Article/details/gtbovjiwcf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ppjwa.cn/Article/details/gtmvuarbpy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hywenlv.cn/Article/details/gtcpnneeeq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.meibo888.top/Article/details/gtihnhjayx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jyoumei.cn/Article/details/gttdpchose.html

[B06] 遍历字典 / 对象
来源：http://dali.chenlongwang.top/Article/details/gtejyhvdzk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cqqwz.cn/Article/details/gtdttzdwrm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.kuanghao11.cn/Article/details/gtnrmdmjgx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shangyingyoupin.top/Article/details/gtzshypcoa.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.quarkkingdee.top/Article/details/gtwwyjkaza.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpoxehgza.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jianghu66.top/Article/details/gtcwlogzdr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tianlin.xyz/Article/details/gtodoimzyz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtusoovzih.html

[B07] while 循环
来源：http://dali.yanxiufei.cn/Article/details/gtnzdrguvg.html

Py:   while i < 10: i += 1
来源：http://dali.fengsongda.top/Article/details/gtdzvmjnok.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258.top/Article/details/gthogldidm.html

JS:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtuuavusfy.html

TS:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtortchapu.html

Java: while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gthkjwiyfh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepgpwujl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuanzhike.top/Article/details/gtccbjjlkm.html

C#:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtwrrlvxou.html

[B08] do-while（至少执行一次）
来源：http://dali.hnqzz.top/Article/details/gtzbcbtlvo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shuidangran.top/Article/details/gtnveajafh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yueranfly.top/Article/details/gtiljgsfdy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gthdodxwiv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtwkpycasu.html

Java: do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtmavwtaij.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gtlaacyyek.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xuanzx.com/Article/details/gtvxzjyjbe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtkhdptsvo.html

[B09] break 与 continue
来源：http://dali.zhixingplan.top/Article/details/gtbvijyhwa.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jqgufenzy.top/Article/details/gtsualjaxu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtklufjjvt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtpkmzqsgm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtjjyvzfkd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtrzjqgpri.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dashuyun.cn/Article/details/gtagvhlvun.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xinyue.icu/Article/details/gtrdtsfwws.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtoicrfwru.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gtsfifwqic.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pengpengdd.cyou/Article/details/gtouddmckk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhoulong.xyz/Article/details/gtchgggzci.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gteowqypiq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtkorwwevv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gtwgpugxyf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.bjfxy.top/Article/details/gtphvgohbg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zycfv.cn/Article/details/gtkvvowdil.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nwbrower.top/Article/details/gtjclbjron.html

[B11] 生成数字序列 / 区间
来源：http://dali.shzxlz.cn/Article/details/gtmkseadoj.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gtzmiwvpky.html

PHP:  range(0, 10, 2);
来源：http://dali.guowangkeji.top/Article/details/gtuwyhhkgw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.mhx1999.top/Article/details/gtorglvokg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gtnbevmeqn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gotoacloud.top/Article/details/gtzsssujmy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cqqwz.cn/Article/details/gtkxcvkrzj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sweek.top/Article/details/gtqssxgrlf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinqigfzy.top/Article/details/gtvpqmquvm.html

[B12] 跳出多层循环
来源：http://dali.cashguo.top/Article/details/gtbrwzmtpw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.kuanghao11.cn/Article/details/gtdkbencly.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxemqshw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtoeoketxm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtzltecthc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtqmrhiqrc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cqqwz.cn/Article/details/gtwldpejry.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gtyiyffbwx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.mhx1999.top/Article/details/gtyknxubpf.html

[B13] 判断是否为数字
来源：http://dali.mhx1999.top/Article/details/gtmafnnkxl.html

Py:   isinstance(x, (int, float))
来源：http://dali.pycfn.com/Article/details/gtdaxxblmx.html

PHP:  is_numeric($x)
来源：http://dali.hnqzz.top/Article/details/gtatwlfxws.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbbstgxr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gthtikyqik.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gtsetoseuv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hysaishi.cn/Article/details/gtvsegetjj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.smart0.xyz/Article/details/gttxcnqsgp.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gtjeotrral.html

[B14] 判断值是否在集合内
来源：http://dali.guowangkeji.top/Article/details/gtumnjbwro.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guowangkeji.top/Article/details/gtyuuoxjiq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cashguo.top/Article/details/gtbnsercbe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gtpfzwiqjr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoggjnlcq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jianghu66.top/Article/details/gtrwrfqvul.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cqqwz.cn/Article/details/gtihdiuiqk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xziqi.cn/Article/details/gtnwhbpnow.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtdbaxuanm.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gtjdsalzxg.html

Py:   a and b or not c
来源：http://dali.xuanzx.com/Article/details/gtcuzzvwwh.html

PHP:  $a && $b || !$c
来源：http://dali.yangfankeji.com/Article/details/gtswxnzplb.html

JS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtktghdzsq.html

TS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtuswsklaw.html

Java: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtzdspwxev.html

Go:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gttrlwvcii.html

Ruby: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtwxowcwtf.html

C#:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtielefdnr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.wangdashe.top/Article/details/gtecwhssld.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gtpaeqigvq.html

PHP:  if (!$data) { return; }
来源：http://dali.yonumen.top/Article/details/gtckunasmr.html

JS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtutsyfplg.html

TS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtmlsowxus.html

Java: if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gtxejuehym.html

Go:   if data == nil { return }
来源：http://dali.chenjidiqi.icu/Article/details/gtdxnbritr.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gtrpqiores.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gtiawyodxr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnensetzc.html

C. 函数与作用域
来源：http://dali.yongpay.top/Article/details/gtnenswxoa.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtofpfrqoi.html

[C01] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtpzlbyliw.html

Py:   def add(a, b): return a + b
来源：http://dali.cheryme.top/Article/details/gtxncmcfsn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtlorpvico.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtofstgjbx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtvvvwzvcy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtrqdydjut.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.bjfxy.top/Article/details/gtjuorctul.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuyvfnml.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtvniuxgrh.html

[C02] 默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiiivslts.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gtxhdjtiit.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhengqikj.top/Article/details/gtpxqzqsqy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtkwkzdcbu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gteknnhidt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gtvcytzzsy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258888.top/Article/details/gtffxglcrj.html

Ruby: def greet(name = "World") = name
来源：http://dali.nwbrower.top/Article/details/gtdloyouob.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhiwuduotai.top/Article/details/gtfuljdchq.html

[C03] 可变参数
来源：http://dali.quarkkingdee.top/Article/details/gtzhqqpkvi.html

Py:   def total(*args): return sum(args)
来源：http://dali.yongpay.top/Article/details/gtapbbdqxg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncfzzxdi.html


<!-- 参考信息 -->