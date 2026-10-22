代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.quarkkingdee.top/Article/details/gt2onhekrwf.html

C#:   var value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gt2vybyzybp.html

[A16] 真假值判断规则
来源：http://dali.316326.xyz/Article/details/gt2eztqbwia.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jiagoushi.top/Article/details/gt2mcltxxix.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ppjwa.cn/Article/details/gt2zmznmhnh.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2djtkflfx.html

TS:   if (!x) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2dlsogtpz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.sxryk.cn/Article/details/gt2mcmfgjxr.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.andypj.xyz/Article/details/gt2yezajfbu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cqqwz.cn/Article/details/gt2uptdlfwf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2zfxnecvx.html

[A17] 位运算
来源：http://dali.feifeiyinyue.top/Article/details/gt2jybonjba.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gt2vuvoarqg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkhjrbvo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gt2lnxzbwsn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gt2hazljqrx.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gt2kzqcjikz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gt2pcuiflby.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2osdagxfk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2ocmunuoo.html

[A18] 字符与 ASCII 码互转
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxkijgge.html

Py:   ord("A"); chr(65)
来源：http://dali.9152youxi.cn/Article/details/gt2xngaaewf.html

PHP:  ord("A"); chr(65)
来源：http://dali.sxryk.cn/Article/details/gt2tncurxdh.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hnqzz.top/Article/details/gt2bsczmrzt.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ivvv.top/Article/details/gt2ivwpuclr.html

Java: (int) 'A'; (char) 65
来源：http://dali.jlsjyb.cn/Article/details/gt2admypijv.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.aibaodan.cn/Article/details/gt2sxifxgbk.html

Ruby: "A".ord; 65.chr
来源：http://dali.dashuyun.cn/Article/details/gt2wittfobg.html

C#:   (int)'A'; (char)65
来源：http://dali.aizwys.cn/Article/details/gt2ovcjcklt.html

[A19] 交换两个变量
来源：http://dali.gotoacloud.top/Article/details/gt2qngobpgb.html

Py:   a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gt2iobnanai.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.tanke756.top/Article/details/gt2cgnqkadr.html

JS:   [a, b] = [b, a];
来源：http://dali.haohaochexian.top/Article/details/gt2uyshhfxh.html

TS:   [a, b] = [b, a];
来源：http://dali.zdqjudy.top/Article/details/gt2xxwvnnnq.html

Java: int t = a; a = b; b = t;
来源：http://dali.jianghu66.top/Article/details/gt2orjoyict.html

Go:   a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gt2qzbqzgqp.html

Ruby: a, b = b, a
来源：http://dali.jqgufenzy.top/Article/details/gt2xiyaepcm.html

C#:   (a, b) = (b, a);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmtzlatn.html

[A20] 读取标准输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcoedbkz.html

Py:   name = input("请输入：")
来源：http://dali.zhengqikj.top/Article/details/gt2tqerpqqp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.bjfxy.top/Article/details/gt2cjfmcuzu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jqgufenzy.top/Article/details/gt2dgmsaxkt.html

TS:   // Node.js：readline 模块
来源：http://dali.ydzc1.top/Article/details/gt2bjsoqeqk.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hongshengwenyu.top/Article/details/gt2prrqvnaf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yangfankeji.com/Article/details/gt2rprtqpsc.html

Ruby: gets.chomp
来源：http://dali.0kj1m.cn/Article/details/gt2xhviuwbh.html

C#:   Console.ReadLine();
来源：http://dali.jinqigufen.top/Article/details/gt2opprvbks.html

[A21] 保留指定小数位输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucvksndr.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yj20258.top/Article/details/gt2herjfwak.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gt2owwlgxae.html

JS:   (3.14159).toFixed(2)
来源：http://dali.aizwys.cn/Article/details/gt2bsfayngn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gt2jbphoror.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jyeevpvo.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gt2xrekmflc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gt2acodohcq.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ssnhzjom.html

[A22] 获取字符串长度
来源：http://dali.9152youxi.cn/Article/details/gt2laurlqtc.html

Py:   len(s)
来源：http://dali.ybcxt.top/Article/details/gt2acruhydv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yongpay.top/Article/details/gt2xkgptpld.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.svipenyu.cn/Article/details/gt2hbjoymdd.html

TS:   s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2ivmmciib.html

Java: s.length()
来源：http://dali.dianchejie.cn/Article/details/gt2qrexmjfq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sysykeji.top/Article/details/gt2necgedil.html

Ruby: s.length
来源：http://dali.mhx1999.top/Article/details/gt2njrlerql.html

C#:   s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmudmkao.html

[A23] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gt2ijbsrciu.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmgycwpe.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cucudq.cn/Article/details/gt2drmdepcl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gt2eytlvcxu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.havefunace.top/Article/details/gt2hiogomgv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gt2tpnwuhls.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yongpay.top/Article/details/gt2ozngxmuw.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gt2rmkhalji.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.nanxuanxn.top/Article/details/gt2xsigvhyf.html

[A24] 去除首尾空白
来源：http://dali.zhixingplan.top/Article/details/gt2ydaxqgmn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.gotoacloud.top/Article/details/gt2zeafplbf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hnqzz.top/Article/details/gt2miehxzba.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jianghu66.top/Article/details/gt2igngwfap.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.haohaochexian.top/Article/details/gt2gchczawe.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxojvctj.html

Go:   strings.TrimSpace(s)
来源：http://dali.xinyue.icu/Article/details/gt2mwjdsxpa.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenzaomai.com/Article/details/gt2lgruhlew.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jiagoushi.top/Article/details/gt2wuafyjgx.html

[A25] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gt2hrsxyrcs.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yueranfly.top/Article/details/gt2luuxcvrw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.chenzaomai.com/Article/details/gt2wsomdprx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.havefunace.top/Article/details/gt2gdwzzrpw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cashguo.top/Article/details/gt2hzlyxfsk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nanxuanxn.top/Article/details/gt2uhmlusoe.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yueranfly.top/Article/details/gt2skxohzcp.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gotoacloud.top/Article/details/gt2pptmzwoc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gogol.net.cn/Article/details/gt2qfqvxsim.html

[A26] 类型转换总览
来源：http://dali.sysykeji.top/Article/details/gt2pndweskk.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangdashe.top/Article/details/gt2xwadecyw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgcntcpj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.dashuyun.cn/Article/details/gt2cnehfmqa.html

TS:   Number() String() Boolean() x as number
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfqxnckm.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenlongwang.top/Article/details/gt2ukoejdar.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hnxiangtu.top/Article/details/gt2xoyiluda.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.c1oappe.top/Article/details/gt2sclpqdoc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gt2xzukznfr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mokdnfpy.html

B. 流程控制
来源：http://dali.jiagoushi.top/Article/details/gt2sevfxdiy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmtaddpl.html

[B01] 条件判断 if / else
来源：http://dali.hammf.cn/Article/details/gt2ahhxzuyp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jyoumei.cn/Article/details/gt2zaldfjbf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cqqwz.cn/Article/details/gt2onntqefn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gt2lhttznyz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gt2tlvuolyb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gt2zenyguli.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tianlin.xyz/Article/details/gt2avpeejis.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.9152youxi.cn/Article/details/gt2mlybeozt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gt2whwggtra.html

[B02] 多分支 else if / elif
来源：http://dali.daxiang520.top/Article/details/gt2czcsylwc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tian-w.cn/Article/details/gt2ilxaaimi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2paqrwxgj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gt2hstyjwvn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gt2djaxjizq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgxbzin.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fzsairri.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tianlin.xyz/Article/details/gt2ttgsfyjk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gt2yupyqrmf.html

[B03] switch / match / case
来源：http://dali.zhongyouzk.top/Article/details/gt2gserqipu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxinkj.top/Article/details/gt2bsmggzya.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gt2hedidyii.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2gabtuetl.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gt2hzjbmbsd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gt2lszomwzd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ehwqpu.com/Article/details/gt2zolwrsrm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhzsgmzq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gt2zlyiebwo.html

[B04] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gt2ppuvxdcc.html

Py:   for i in range(10): print(i)
来源：http://dali.jiagoushi.top/Article/details/gt2utchboge.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sweek.top/Article/details/gt2pskibxqg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ivvv.top/Article/details/gt2klcpcqkv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sweek.top/Article/details/gt2fooogazj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ydzc1.top/Article/details/gt2xdwqqfvf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.dashuyun.cn/Article/details/gt2yrodhatt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.fengsongda.top/Article/details/gt2mhcoqevh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sufxvd.cn/Article/details/gt2xtbwkhex.html

[B05] 遍历数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gt2fnshybtb.html

Py:   for item in arr: print(item)
来源：http://dali.kuanghao11.cn/Article/details/gt2tznewcvb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.aizwys.cn/Article/details/gt2rjsqjiox.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gt2tidfnuqw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.iojbl.cn/Article/details/gt2cncjdtje.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sxryk.cn/Article/details/gt2fxqoswef.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lfudzdfs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dashuyun.cn/Article/details/gt2jpcsmxbr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cqqwz.cn/Article/details/gt2lsxzlhhv.html

[B06] 遍历字典 / 对象
来源：http://dali.cqqwz.cn/Article/details/gt2zxizpljs.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hfpthk.cn/Article/details/gt2bbzqhhop.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.smart0.xyz/Article/details/gt2ltqkkhht.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ylwydgbm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daria6918.cn/Article/details/gt2pxepqjlv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yueranfly.top/Article/details/gt2hgxlybxl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jyoumei.cn/Article/details/gt2dhvqiqwt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhixingplan.top/Article/details/gt2ugyjuclu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hammf.cn/Article/details/gt2grnohfve.html

[B07] while 循环
来源：http://dali.dashuyun.cn/Article/details/gt2uzkrtehf.html

Py:   while i < 10: i += 1
来源：http://dali.cdnleiting.top/Article/details/gt2wjzrlbfn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcgutrrb.html

JS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gt2fmnhvscr.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gt2lgaczxkh.html

Java: while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gt2wehfidzn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dashuyun.cn/Article/details/gt2oksnscej.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2wugbdzxu.html

C#:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gt2nshcsibi.html

[B08] do-while（至少执行一次）
来源：http://dali.meibo888.top/Article/details/gt2dagyrbib.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.bjfxy.top/Article/details/gt2ylesklkt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gt2cyeexwgd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gt2lzjdyfpu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2cgwsxufz.html

Java: do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gt2dbhburxo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gt2ulayotyh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gt2fmatwyfd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2ompkuefu.html

[B09] break 与 continue
来源：http://dali.cheryme.top/Article/details/gt2mqciprgh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258888.top/Article/details/gt2pfazfljk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mktdjshp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gt2cjryslbf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2duengffc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2dxycthgj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgufenzy.top/Article/details/gt2aficnfbj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj202588.top/Article/details/gt2eyobojgg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gt2byuegufa.html

[B10] 遍历同时拿索引
来源：http://dali.316326.xyz/Article/details/gt2ldtkqwgz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gzhubu.top/Article/details/gt2puavqewx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yueranfly.top/Article/details/gt2wobebupg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gt2ohizbvzz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gt2jjoeeysm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.316326.xyz/Article/details/gt2uuihkoee.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cdnleiting.top/Article/details/gt2tciffzla.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenzaomai.com/Article/details/gt2ehnzfvcb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daxiang520.top/Article/details/gt2ytqitmes.html

[B11] 生成数字序列 / 区间
来源：http://dali.gotoacloud.top/Article/details/gt2vwoturyx.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnxiangtu.top/Article/details/gt2sbtnkmvb.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258888.top/Article/details/gt2vlucoqiu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2dozcjbdo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gt2oognuhzz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.andypj.xyz/Article/details/gt2ocjpzcnn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlxnhtgr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgmryhyw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sysykeji.top/Article/details/gt2ratbiiuu.html

[B12] 跳出多层循环
来源：http://dali.andypj.xyz/Article/details/gt2jswksvrj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tanke756.top/Article/details/gt2jtzpduer.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgufenzy.top/Article/details/gt2rcvecfcc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2olbsoyww.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2mspetkud.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2konxhcny.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.iojbl.cn/Article/details/gt2uywwwsmo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gt2vqbjjfny.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgfzy.top/Article/details/gt2osotoclj.html

[B13] 判断是否为数字
来源：http://dali.jinqigfzy.top/Article/details/gt2razcdmdn.html

Py:   isinstance(x, (int, float))
来源：http://dali.svipenyu.cn/Article/details/gt2czxcmefs.html

PHP:  is_numeric($x)
来源：http://dali.yueranfly.top/Article/details/gt2glmnetqn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gt2eoadrngd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gt2ygfyuisy.html

Java: x instanceof Number
来源：http://dali.dianchejie.cn/Article/details/gt2wpydbiul.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.redwolf501.top/Article/details/gt2xyqbredu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.vqdsnc.cn/Article/details/gt2nwpxlsmv.html

C#:   x is int or double or decimal
来源：http://dali.gaohongyu789.top/Article/details/gt2thbxtsjp.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258.top/Article/details/gt2iyyomchs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yueranfly.top/Article/details/gt2vuhqnxag.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pengpengdd.cyou/Article/details/gt2geyayosb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2djfnenul.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2rwiinqbk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnpknyk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2sshihmiv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2zteyottc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gt2aylrkzkd.html

[B15] 布尔运算与取反
来源：http://dali.tanke756.top/Article/details/gt2snopioyn.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2lotarqyc.html

PHP:  $a && $b || !$c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oosletig.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2ojyzyesm.html

TS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2egjblqbl.html

Java: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2mlobfoit.html

Go:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgjxjfws.html

Ruby: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2aenbfjhw.html

C#:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2dxumtyvt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daria6918.cn/Article/details/gt2clfdbxzv.html

Py:   if not data: return
来源：http://dali.daria6918.cn/Article/details/gt2mxwgcmjh.html

PHP:  if (!$data) { return; }
来源：http://dali.yvedp.cn/Article/details/gt2mrbmledc.html

JS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2uoqaottx.html

TS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gt2kvqhfdmy.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gt2budmyojk.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gt2aoilcvah.html

Ruby: return if data.nil?
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwaaauzd.html

C#:   if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gt2hksigvcw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2nnlfszcc.html

C. 函数与作用域
来源：http://dali.jinqigufen.top/Article/details/gt2zxwnkzkd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2jtkejkbw.html

[C01] 定义函数
来源：http://dali.pycfn.com/Article/details/gt2tcwmkmjl.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gt2qtssluqv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tifrqcuu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2llcrnldt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2buniiijr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yesspclj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jyoumei.cn/Article/details/gt2huywpdld.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gzhubu.top/Article/details/gt2ahdlolhh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2audgxdug.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gt2phlarkrq.html

Py:   def greet(name="World"): return name
来源：http://dali.bjfxy.top/Article/details/gt2vfklsqbt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nwbrower.top/Article/details/gt2fcixqzzw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gt2spdwznnh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2wenakryu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cashguo.top/Article/details/gt2sfloqtok.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sweek.top/Article/details/gt2uklaawrv.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwrcdaqg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxuanxn.top/Article/details/gt2nktjxjjj.html

[C03] 可变参数
来源：http://dali.ppjwa.cn/Article/details/gt2ozhfcikc.html

Py:   def total(*args): return sum(args)
来源：http://dali.xinyue.icu/Article/details/gt2leoekboo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gt2vcasgcaj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gt2gsipvhzi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gt2awbihgph.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eytdkbnb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gt2hzbyotpu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gt2jarrxeuc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenzaomai.com/Article/details/gt2xxwvsbvi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.svipenyu.cn/Article/details/gt2taahfcqj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhengqikj.top/Article/details/gt2ibgrzchy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqdpubpw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gt2stvmdfuv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuanzx.com/Article/details/gt2huejlvce.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gt2hyblrgvq.html

Go:   // 无：用配置结构体参数
来源：http://dali.guowangkeji.top/Article/details/gt2jxgwpcte.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gt2mayfkycp.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gt2bhcsbomz.html

[C05] 返回多个值
来源：http://dali.meibo888.top/Article/details/gt2ubuxafte.html

Py:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gt2tnrfwfnr.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gt2qudcnkek.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ybcxt.top/Article/details/gt2mqaktaiw.html

TS:   return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gt2ysvotmnf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhongyouzk.top/Article/details/gt2edgznjrp.html

Go:   return a, b
来源：http://dali.tanke756.top/Article/details/gt2axsrpsts.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqudwjov.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tianlin.xyz/Article/details/gt2vqcbunpn.html

[C06] 匿名函数 / lambda
来源：http://dali.cucudq.cn/Article/details/gt2pwlpdrib.html

Py:   square = lambda x: x * x
来源：http://dali.sufxvd.cn/Article/details/gt2ekbussfv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jianghu66.top/Article/details/gt2tyooiczc.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2lsszaapg.html


<!-- 参考信息 -->