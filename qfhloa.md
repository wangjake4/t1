代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.fzhhl.top/Article/details/gtxhtdywjq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.tanke756.top/Article/details/gthofjvgpt.html

TS:   if (!x) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtztnfvula.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.gotoacloud.top/Article/details/gtqfpbfhfx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.mhx1999.top/Article/details/gtzbxyvksi.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sysykeji.top/Article/details/gtqniafnep.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhengqikj.top/Article/details/gtsjgnwuga.html

[A17] 位运算
来源：http://dali.wangshuangyany.cn/Article/details/gtbhsmenas.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtqxbkgsqd.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yvedp.cn/Article/details/gtnpovmvmb.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtzkoswiwe.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtvuokupva.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtthaaiofs.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtbhijajto.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtdcsvadvk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtolxlrmxf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhixingplan.top/Article/details/gtxxdrbtry.html

Py:   ord("A"); chr(65)
来源：http://dali.316326.xyz/Article/details/gtgozzxyva.html

PHP:  ord("A"); chr(65)
来源：http://dali.yangfankeji.com/Article/details/gtgvnszxzs.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yvedp.cn/Article/details/gtseqxstkz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cashguo.top/Article/details/gtjscbfsxf.html

Java: (int) 'A'; (char) 65
来源：http://dali.xylfe.cn/Article/details/gtpsioycqn.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xuetiantiany.cn/Article/details/gtlxxgiiza.html

Ruby: "A".ord; 65.chr
来源：http://dali.daria6918.cn/Article/details/gtamvmnskm.html

C#:   (int)'A'; (char)65
来源：http://dali.hysaishi.cn/Article/details/gtdthdqsrz.html

[A19] 交换两个变量
来源：http://dali.pycfn.com/Article/details/gtdewlzirb.html

Py:   a, b = b, a
来源：http://dali.hysaishi.cn/Article/details/gtqegciorp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yonumen.top/Article/details/gtlemlukny.html

JS:   [a, b] = [b, a];
来源：http://dali.havefunace.top/Article/details/gtrvdmgcyo.html

TS:   [a, b] = [b, a];
来源：http://dali.yj202588.top/Article/details/gtlmiqrnfu.html

Java: int t = a; a = b; b = t;
来源：http://dali.ybcxt.top/Article/details/gtpmianpqy.html

Go:   a, b = b, a
来源：http://dali.ydzc1.top/Article/details/gtsiojuhdo.html

Ruby: a, b = b, a
来源：http://dali.jianghu66.top/Article/details/gtczntlygp.html

C#:   (a, b) = (b, a);
来源：http://dali.cqqwz.cn/Article/details/gtumkxskuk.html

[A20] 读取标准输入
来源：http://dali.gogol.net.cn/Article/details/gtnqvkqyzy.html

Py:   name = input("请输入：")
来源：http://dali.hfpthk.cn/Article/details/gtqqwbgwjk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jqgfzy.top/Article/details/gtdgshuwbp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xylfe.cn/Article/details/gtvwkmakkx.html

TS:   // Node.js：readline 模块
来源：http://dali.nanxuanxn.top/Article/details/gtchknqonc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hongshengwenyu.top/Article/details/gtvvyjhfbo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yvedp.cn/Article/details/gtoglwihty.html

Ruby: gets.chomp
来源：http://dali.mhx1999.top/Article/details/gtqedomrkk.html

C#:   Console.ReadLine();
来源：http://dali.ivvv.top/Article/details/gtjiygjwuy.html

[A21] 保留指定小数位输出
来源：http://dali.jlsjyb.cn/Article/details/gtpaqworlz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.sxryk.cn/Article/details/gtvuqvcmei.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sysykeji.top/Article/details/gtagbulhbr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtejndfskq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtwwsdpqvg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gtoretwopl.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gtxzmukoem.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtiynipjhx.html

C#:   3.14159.ToString("F2")
来源：http://dali.meibo888.top/Article/details/gtbtbdhxdm.html

[A22] 获取字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtjbewtxni.html

Py:   len(s)
来源：http://dali.cheryme.top/Article/details/gtxuaaygkn.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.9152youxi.cn/Article/details/gtqcqxmzsp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shanyushiyangtech.top/Article/details/gtoemwcagx.html

TS:   s.length
来源：http://dali.tanke756.top/Article/details/gtwjxuftqq.html

Java: s.length()
来源：http://dali.hnqzz.top/Article/details/gterexvdaz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yongpay.top/Article/details/gtddxttqup.html

Ruby: s.length
来源：http://dali.yanxiufei.cn/Article/details/gtpdzqqegd.html

C#:   s.Length
来源：http://dali.sysykeji.top/Article/details/gtgjcfgjos.html

[A23] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtkvrnalgp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xylfe.cn/Article/details/gtmajhtrwg.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvvwauxch.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnxiangtu.top/Article/details/gtmokzedld.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.redwolf501.top/Article/details/gtezhwwmyy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gtqxleqhja.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.9152youxi.cn/Article/details/gtbmceawry.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.mhx1999.top/Article/details/gtoszirjaj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmbqglil.html

[A24] 去除首尾空白
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezlbuhtv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cqqwz.cn/Article/details/gtzrtperod.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.vqdsnc.cn/Article/details/gtolxidmbl.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gtukmevxya.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gtqxsfbrzg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shangyingyoupin.top/Article/details/gtzhzxwhgn.html

Go:   strings.TrimSpace(s)
来源：http://dali.yanxiufei.cn/Article/details/gtccishxvj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.kuanghao11.cn/Article/details/gthltnxahq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ivvv.top/Article/details/gtwjfrgiwg.html

[A25] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gtxkmqxxtu.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sweek.top/Article/details/gtdzbazgzy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yongpay.top/Article/details/gtztseecph.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gogol.net.cn/Article/details/gtrlabbnvd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nwbrower.top/Article/details/gtjckojhar.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.dianchejie.cn/Article/details/gtmzkrfzan.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokjglkaf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhijiandao.cn/Article/details/gtdvbvgebq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yanxiufei.cn/Article/details/gtxmivurnz.html

[A26] 类型转换总览
来源：http://dali.hnxiangtu.top/Article/details/gtkqyuwqkj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.havefunace.top/Article/details/gthuegldes.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhixingplan.top/Article/details/gtkuanwuvh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenjidiqi.icu/Article/details/gtpsjyfopt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxuanxn.top/Article/details/gtujifzoyk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.smart0.xyz/Article/details/gtmpwumoes.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ppjwa.cn/Article/details/gtrtsncnzv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xuanzx.com/Article/details/gthvqncaba.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gtpkpzuwqo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdqlecdjz.html

B. 流程控制
来源：http://dali.zhijiandao.cn/Article/details/gtvesixwko.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxnyfhndv.html

[B01] 条件判断 if / else
来源：http://dali.guannengcc.top/Article/details/gthushpkeq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.havefunace.top/Article/details/gtitrbwdrp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdhxonyjn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtfcnunhcj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gteiubgmjc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtdguoucwo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cucudq.cn/Article/details/gtgjkbqtgr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbxheujj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gttbknmcva.html

[B02] 多分支 else if / elif
来源：http://dali.daria6918.cn/Article/details/gtauyvduwk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenjidiqi.icu/Article/details/gtjwobutph.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.iojbl.cn/Article/details/gtqblybgxb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gtjbprrowp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtmzhvpdah.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtwvbpvkcq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cdnleiting.top/Article/details/gtfoyzyfsh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sysykeji.top/Article/details/gtxltersul.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gtkdyxksqe.html

[B03] switch / match / case
来源：http://dali.pengpengdd.cyou/Article/details/gtbnhkllap.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxinkj.top/Article/details/gtvhmaqsny.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtenkfuzuz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gtyulpryxa.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtznwitnvb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gtfvotlexf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gtfhbdnzrc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sweek.top/Article/details/gtgtqszbjo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.mhx1999.top/Article/details/gtldzyfsxr.html

[B04] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtuvfpobmj.html

Py:   for i in range(10): print(i)
来源：http://dali.dianchejie.cn/Article/details/gtqwfhbgek.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.9152youxi.cn/Article/details/gtwoeldwfx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigufen.top/Article/details/gthxygnoav.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtldjbtiis.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybqjihfs.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.fzhhl.top/Article/details/gtxteypodo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.mhx1999.top/Article/details/gtsjqxtvea.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fengsongda.top/Article/details/gtaudmlowc.html

[B05] 遍历数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtrydtclgq.html

Py:   for item in arr: print(item)
来源：http://dali.zhoulong.xyz/Article/details/gtmxiwgyeb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.chenlongwang.top/Article/details/gthocieeyy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jianghu66.top/Article/details/gtdnzojaog.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gtdwdudvjv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.9152youxi.cn/Article/details/gtjdkdvflt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.meibo888.top/Article/details/gtwnjtvwfw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjmesznk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hywenlv.cn/Article/details/gtjzoyxtyu.html

[B06] 遍历字典 / 对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtswrgmvzr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dashuyun.cn/Article/details/gtxvplnytd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.daria6918.cn/Article/details/gtdbdjwseo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yueranfly.top/Article/details/gtjlacqvvz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gtstyjkapk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnupcympt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.fzhhl.top/Article/details/gtkumzkqip.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gtlpnvzaxl.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xinyue.icu/Article/details/gtlcfzljli.html

[B07] while 循环
来源：http://dali.daria6918.cn/Article/details/gtopmjjdoj.html

Py:   while i < 10: i += 1
来源：http://dali.shuidangran.top/Article/details/gtatxqzgvb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dashuyun.cn/Article/details/gtyjiyeoav.html

JS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtozwnicpc.html

TS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gttzsznanm.html

Java: while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtmpjheegv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shzxlz.cn/Article/details/gtamhkioij.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xinyue.icu/Article/details/gtlitmdlzq.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gttwjwrabu.html

[B08] do-while（至少执行一次）
来源：http://dali.zhongyouzk.top/Article/details/gtfrxeegtl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yanxiufei.cn/Article/details/gtusgbsnmu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtcgjmkols.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtecjyzfov.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtrgbrqqkr.html

Java: do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtbpibjswe.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258.top/Article/details/gtqfapzoie.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fengsongda.top/Article/details/gtnxvimyal.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtlxwgldnn.html

[B09] break 与 continue
来源：http://dali.yuxming.cn/Article/details/gtxhqbsrhb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daria6918.cn/Article/details/gtuiuspfgk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtrppqljcl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtahdwkefy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyszortuz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtqlrqyiho.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhengqikj.top/Article/details/gtpaasdvfi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258.top/Article/details/gtdxtizbtv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtpkqwxyhl.html

[B10] 遍历同时拿索引
来源：http://dali.yj20258888.top/Article/details/gtqdahgtnq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqtwvvim.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sweek.top/Article/details/gtwigtlqhw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gtovhctbap.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtcqllakxd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnqzz.top/Article/details/gtqedqhwrd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.vqdsnc.cn/Article/details/gtyeurizpp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nanxuanxn.top/Article/details/gtsufkkkze.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.mhx1999.top/Article/details/gtadbbxzwa.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhongyouzk.top/Article/details/gtjnrjeklo.html

Py:   list(range(0, 10, 2))
来源：http://dali.hysaishi.cn/Article/details/gtfkxwrrue.html

PHP:  range(0, 10, 2);
来源：http://dali.guannengcc.top/Article/details/gtosttwxav.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtsckrndye.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gthiiqtnxj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.smart0.xyz/Article/details/gtzdmekxhm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenjidiqi.icu/Article/details/gtxhqjefyx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gtlzqbnkyc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhixingplan.top/Article/details/gteozwhgcz.html

[B12] 跳出多层循环
来源：http://dali.0kj1m.cn/Article/details/gtfnphbxdq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fengsongda.top/Article/details/gtphstynsw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258.top/Article/details/gtghbfyhwd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gtpdrlztex.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtubgmrqft.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtvhmhpwro.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnxiangtu.top/Article/details/gtzypttbfa.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gtmhcnqxpo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hammf.cn/Article/details/gteksmhppx.html

[B13] 判断是否为数字
来源：http://dali.zhengqikj.top/Article/details/gtlbkjgxwq.html

Py:   isinstance(x, (int, float))
来源：http://dali.hongshengwenyu.top/Article/details/gtnwnokgss.html

PHP:  is_numeric($x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodvgucfh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gtahmnqoto.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gtnfyydkhk.html

Java: x instanceof Number
来源：http://dali.xuetiantiany.cn/Article/details/gtzyfkqrei.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nwbrower.top/Article/details/gtrtvjujjd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenjidiqi.icu/Article/details/gtoeypblwy.html

C#:   x is int or double or decimal
来源：http://dali.yongpay.top/Article/details/gtpxqgonjl.html

[B14] 判断值是否在集合内
来源：http://dali.iojbl.cn/Article/details/gtdiboccjo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gtkbifiokh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.meibo888.top/Article/details/gtkjynzhds.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtoomslnci.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gtrwhopsiu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtvxiqucvq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guowangkeji.top/Article/details/gtrggcslwc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytzursjf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gttfervcxg.html

[B15] 布尔运算与取反
来源：http://dali.yonumen.top/Article/details/gtmexfdkju.html

Py:   a and b or not c
来源：http://dali.dianchejie.cn/Article/details/gtdmschydb.html

PHP:  $a && $b || !$c
来源：http://dali.dashuyun.cn/Article/details/gtvfmdeegw.html

JS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtdbxmevpt.html

TS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtuxjotsva.html

Java: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtddldfqld.html

Go:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtemzfptvw.html

Ruby: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtkybuakxs.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gthneqnhns.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtohjdnvff.html

Py:   if not data: return
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaoupmiv.html

PHP:  if (!$data) { return; }
来源：http://dali.zdqjudy.top/Article/details/gtxynbnzbs.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadperpjj.html

TS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtowgyuitw.html

Java: if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gtqraaedtk.html

Go:   if data == nil { return }
来源：http://dali.kuanghao11.cn/Article/details/gtwzeisvco.html

Ruby: return if data.nil?
来源：http://dali.jqgufenzy.top/Article/details/gthfvdhjod.html

C#:   if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gtawkwtine.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtpriumjer.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gtgujrphaw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtujqtkazj.html

[C01] 定义函数
来源：http://dali.yj20258.top/Article/details/gtnuardgay.html

Py:   def add(a, b): return a + b
来源：http://dali.fengsongda.top/Article/details/gttfkefiin.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtbosbwvld.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtfgtzapzp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtxrrwbjxt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilnuprsu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jyoumei.cn/Article/details/gtuzfcuiqn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.9152youxi.cn/Article/details/gtueuwdxsg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtuxujozax.html

[C02] 默认参数
来源：http://dali.ehwqpu.com/Article/details/gtlcytvmkq.html

Py:   def greet(name="World"): return name
来源：http://dali.pycfn.com/Article/details/gtkswlspcs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gtullxwevk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gttxbgpgyq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbtmqoxc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjrolyjn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shangyingyoupin.top/Article/details/gtfyuqultm.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gtqgemqido.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gtvswshkkd.html

[C03] 可变参数
来源：http://dali.hfpthk.cn/Article/details/gtrzdqcjwi.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenjidiqi.icu/Article/details/gtxoucrmdq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gtclwzgmnh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtsmlyezwc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gtkeobvkzp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixkjsxfy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gtanoepzvr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gtvmrgotpo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhiwuduotai.top/Article/details/gtyqzsjaom.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hysaishi.cn/Article/details/gtefdluhkk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhiwuduotai.top/Article/details/gtzefkqddh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ppjwa.cn/Article/details/gtydjfpeil.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtrcnmmowy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fzhhl.top/Article/details/gtvvopfrcn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxinkj.top/Article/details/gtomqnwyvz.html

Go:   // 无：用配置结构体参数
来源：http://dali.xylfe.cn/Article/details/gtfgdtzxlj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gthdqqyluk.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtuuzjbhic.html

[C05] 返回多个值
来源：http://dali.daxiang520.top/Article/details/gtdcsfjvut.html

Py:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gthpkhyqtt.html

PHP:  return [$a, $b];
来源：http://dali.jyoumei.cn/Article/details/gtwasfsffx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yonumen.top/Article/details/gtjhziyomx.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gtskpkxlmm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangdashe.top/Article/details/gtlgsdzysp.html

Go:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtigggxdqi.html

Ruby: return a, b
来源：http://dali.haohaochexian.top/Article/details/gtjyygikas.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gtrtbhqhbw.html

[C06] 匿名函数 / lambda
来源：http://dali.fzhhl.top/Article/details/gtjhodypiz.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gtoxwzgbos.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhiwuduotai.top/Article/details/gtcmwheafe.html

JS:   const square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtfyysxxkh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtcpnpfduc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.316326.xyz/Article/details/gtmkhuzhgh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgfzy.top/Article/details/gtlydiaxvb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.meibo888.top/Article/details/gtycluaqpv.html


<!-- 参考信息 -->