代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gtisyueypz.html

TS:   const value = data ?? "默认值";
来源：http://dali.hysaishi.cn/Article/details/gtxkzrecyc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.c1oappe.top/Article/details/gtkpvrghsq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpvfcexa.html

Ruby: value = data || "默认值"
来源：http://dali.yonumen.top/Article/details/gtdszikvey.html

C#:   var value = data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gtpreccaqv.html

[A16] 真假值判断规则
来源：http://dali.gogol.net.cn/Article/details/gtrisjqaey.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yuxming.cn/Article/details/gtcwkarvbj.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhixingplan.top/Article/details/gtnfbgbcdc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.vqdsnc.cn/Article/details/gtgruaaycr.html

TS:   if (!x) {}
来源：http://dali.cqqwz.cn/Article/details/gtkambuxlh.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.chenlongwang.top/Article/details/gtquzbeugd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenzaomai.com/Article/details/gtlzndzjjd.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.bjfxy.top/Article/details/gthjyuumxb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfvnddew.html

[A17] 位运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvscvnwj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtuhcbmotk.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.haohaochexian.top/Article/details/gtwlhzcjsc.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtjuhwqmtb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuumzsso.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtjzulzjbu.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gthjdyduwv.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtbzfblrbv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtnwplkdbn.html

[A18] 字符与 ASCII 码互转
来源：http://dali.aizwys.cn/Article/details/gtdhhlkjrb.html

Py:   ord("A"); chr(65)
来源：http://dali.tanke756.top/Article/details/gtyphvzegs.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhoulong.xyz/Article/details/gtfksgkcyw.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sweek.top/Article/details/gtpalumorr.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gthcqwbzme.html

Java: (int) 'A'; (char) 65
来源：http://dali.iojbl.cn/Article/details/gtqconjkqm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.iojbl.cn/Article/details/gtjkxvheci.html

Ruby: "A".ord; 65.chr
来源：http://dali.cucudq.cn/Article/details/gtjnpxeasy.html

C#:   (int)'A'; (char)65
来源：http://dali.sxryk.cn/Article/details/gtcmycsxny.html

[A19] 交换两个变量
来源：http://dali.iojbl.cn/Article/details/gtjxxxwhtb.html

Py:   a, b = b, a
来源：http://dali.daria6918.cn/Article/details/gtowsynccx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhongyouzk.top/Article/details/gtrydvxaue.html

JS:   [a, b] = [b, a];
来源：http://dali.hnxiangtu.top/Article/details/gtsmpxffcm.html

TS:   [a, b] = [b, a];
来源：http://dali.gotoacloud.top/Article/details/gtxwqccdrt.html

Java: int t = a; a = b; b = t;
来源：http://dali.shzxlz.cn/Article/details/gtxhswhota.html

Go:   a, b = b, a
来源：http://dali.tian-w.cn/Article/details/gtljgketzl.html

Ruby: a, b = b, a
来源：http://dali.xylfe.cn/Article/details/gtyturrmco.html

C#:   (a, b) = (b, a);
来源：http://dali.ppjwa.cn/Article/details/gtiimwyqpe.html

[A20] 读取标准输入
来源：http://dali.dashuyun.cn/Article/details/gtalujkjjx.html

Py:   name = input("请输入：")
来源：http://dali.yanxiufei.cn/Article/details/gtucjhwghn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cheryme.top/Article/details/gtyyvkdafb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yanxiufei.cn/Article/details/gtejwvlfio.html

TS:   // Node.js：readline 模块
来源：http://dali.tian-w.cn/Article/details/gtxlcbwror.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhengqikj.top/Article/details/gtejhwnvih.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqpulrvs.html

Ruby: gets.chomp
来源：http://dali.daria6918.cn/Article/details/gteeklzpgr.html

C#:   Console.ReadLine();
来源：http://dali.yvedp.cn/Article/details/gttynkuyek.html

[A21] 保留指定小数位输出
来源：http://dali.smart0.xyz/Article/details/gtfvhtufww.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinqigfzy.top/Article/details/gtabaozorx.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gtgwglotnc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gtfujmyxkn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gtjfpzgmiq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gtdafwwmzw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yangfankeji.com/Article/details/gtzmcswgpe.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gtnzpwbmpw.html

C#:   3.14159.ToString("F2")
来源：http://dali.vqdsnc.cn/Article/details/gtzifsaimg.html

[A22] 获取字符串长度
来源：http://dali.sweek.top/Article/details/gtmtkerkqn.html

Py:   len(s)
来源：http://dali.fzhhl.top/Article/details/gtebtithel.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ivvv.top/Article/details/gtxnzzvyln.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.daxiang520.top/Article/details/gtciginjrq.html

TS:   s.length
来源：http://dali.hnqzz.top/Article/details/gteqvygpef.html

Java: s.length()
来源：http://dali.havefunace.top/Article/details/gttvzegngu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yj20258888.top/Article/details/gtwbvfjjkw.html

Ruby: s.length
来源：http://dali.9152youxi.cn/Article/details/gtsdecrpnc.html

C#:   s.Length
来源：http://dali.jyoumei.cn/Article/details/gtlawjunzk.html

[A23] 大小写转换
来源：http://dali.yonumen.top/Article/details/gthsgjhxys.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.andypj.xyz/Article/details/gtvgorhrod.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.redwolf501.top/Article/details/gtdcrgmbgl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.mhx1999.top/Article/details/gtmsgiaxga.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gttkxftiap.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gttiraqtkv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.birdmap.top/Article/details/gtxldbjcal.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtrkpismjo.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cashguo.top/Article/details/gtslsrsdox.html

[A24] 去除首尾空白
来源：http://dali.nanxuanxn.top/Article/details/gtkgcnkcqi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinqigufen.top/Article/details/gtmynjowqs.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sysykeji.top/Article/details/gtiwamroex.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.aibaodan.cn/Article/details/gtwiymqnnr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tianlin.xyz/Article/details/gtvfwneoge.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfulcldx.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhongyouzk.top/Article/details/gtkwkwqghb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.fzhhl.top/Article/details/gtnwwvhdzy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cqqwz.cn/Article/details/gtqqtuqyho.html

[A25] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvhiohfp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhoulong.xyz/Article/details/gtqdvsyeyc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.daxiang520.top/Article/details/gtbpgtqfsz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aizwys.cn/Article/details/gtrdfexbqr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jqgufenzy.top/Article/details/gthsjohxtr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ehwqpu.com/Article/details/gtemekwkkj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xylfe.cn/Article/details/gtbncsxona.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tian-w.cn/Article/details/gtjmomqydh.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cashguo.top/Article/details/gtvejykkbw.html

[A26] 类型转换总览
来源：http://dali.jlsjyb.cn/Article/details/gtiqzdcicp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangdashe.top/Article/details/gtbfhmhgwl.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.chenlongwang.top/Article/details/gtrfarxgxw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ppjwa.cn/Article/details/gtlrzalybe.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ppjwa.cn/Article/details/gthjtagofb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gthucbbthy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tanke756.top/Article/details/gtgzwslvtl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tanke756.top/Article/details/gtgsyrqlsp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yuxming.cn/Article/details/gtzcrxjphc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrewttldi.html

B. 流程控制
来源：http://dali.ybcxt.top/Article/details/gtsvbawccc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtnenmuhgq.html

[B01] 条件判断 if / else
来源：http://dali.jinqigfzy.top/Article/details/gtmmwsrjik.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jiagoushi.top/Article/details/gtftfttrwf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.snrcjt.cn/Article/details/gtupzdfovj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtlnrpfbbv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtetooxjfm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gthrxhrwvw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmdnnaml.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hongshengwenyu.top/Article/details/gtmeliuplt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtrtsikmap.html

[B02] 多分支 else if / elif
来源：http://dali.wangdashe.top/Article/details/gttdjlehie.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.pycfn.com/Article/details/gtxebmgkxe.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ivvv.top/Article/details/gtqccwyedq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gtteatbvhz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jiagoushi.top/Article/details/gtusfiohvr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgxhfpcp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yonumen.top/Article/details/gtrrymmprs.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj20258.top/Article/details/gtmblmllwz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtlfumrukn.html

[B03] switch / match / case
来源：http://dali.nanxinkj.top/Article/details/gtletnucpk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.c1oappe.top/Article/details/gtodpvuipu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gtjlsyhijf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttalvtfxu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtkqgjlpfi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtddrrfbmh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nanxinkj.top/Article/details/gtzcpwqpuo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shuidangran.top/Article/details/gtpueumfps.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xylfe.cn/Article/details/gtnhaceefj.html

[B04] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gtqssrwrnz.html

Py:   for i in range(10): print(i)
来源：http://dali.sysykeji.top/Article/details/gtnlgwyhvg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hnxiangtu.top/Article/details/gtxdbclfui.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gttiqpqszg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gtxcpzerpc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shuidangran.top/Article/details/gtxuyousfe.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.guannengcc.top/Article/details/gtzxdzfafq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yueranfly.top/Article/details/gtqkxfbbtr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ppjwa.cn/Article/details/gtyygqxuir.html

[B05] 遍历数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtkweyfclu.html

Py:   for item in arr: print(item)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfgphjqg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.316326.xyz/Article/details/gtdbutldml.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.dashuyun.cn/Article/details/gtdlglwbfs.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtjfntpdre.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqcyobbcj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.guannengcc.top/Article/details/gtussjlraw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigfzy.top/Article/details/gtlnvoaomn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigufen.top/Article/details/gtlyssesim.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258.top/Article/details/gtkqaqqpki.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hongshengwenyu.top/Article/details/gthbmvlbzz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.aibaodan.cn/Article/details/gthqwmputx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gthuykjzwg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gtkpovctjn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmemolci.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yueranfly.top/Article/details/gtxntaeook.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhengqikj.top/Article/details/gtzgvxqxgy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.feifeiyinyue.top/Article/details/gticsertgj.html

[B07] while 循环
来源：http://dali.xuetiantiany.cn/Article/details/gtewchbvkd.html

Py:   while i < 10: i += 1
来源：http://dali.xuetiantiany.cn/Article/details/gttiwsudam.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.daria6918.cn/Article/details/gtyyjvvimd.html

JS:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtybhhtqug.html

TS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtbeicdwor.html

Java: while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtvpenwalw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258.top/Article/details/gtiikrphkc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.birdmap.top/Article/details/gtdynyfocu.html

C#:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtpmkiucfv.html

[B08] do-while（至少执行一次）
来源：http://dali.316326.xyz/Article/details/gtjqmfemrv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuanzx.com/Article/details/gtcsphrfeh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sysykeji.top/Article/details/gtkjfavnks.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtjbgrkrvj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtpfmkqcga.html

Java: do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtfeghpduj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigufen.top/Article/details/gtfoflmrsu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgfzy.top/Article/details/gttuhwogfc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtzgareond.html

[B09] break 与 continue
来源：http://dali.birdmap.top/Article/details/gtfkhjhvtn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hysaishi.cn/Article/details/gtugeeooin.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtiniiucht.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtxxodpmzr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtkkohmpqm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtkeixdcnp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dashuyun.cn/Article/details/gtsrgaesai.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ybcxt.top/Article/details/gtkxfjekfz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtkrcmevqu.html

[B10] 遍历同时拿索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdhymdpv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yonumen.top/Article/details/gtiiyncaze.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zdqjudy.top/Article/details/gtrrhmlgjg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gtibotkjcs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gtegbohxkm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvupmsgu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.dashuyun.cn/Article/details/gtwnhlzbdk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yanxiufei.cn/Article/details/gttobftyss.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.haohaochexian.top/Article/details/gtxbqmfwjf.html

[B11] 生成数字序列 / 区间
来源：http://dali.kuanghao11.cn/Article/details/gtmlzpkxpd.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangshuangyany.cn/Article/details/gtcowmfcjs.html

PHP:  range(0, 10, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtbevlfvxx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gtinmmhwzm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gtxdfgttoi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ehwqpu.com/Article/details/gtglfkhyln.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sufxvd.cn/Article/details/gtalkzskzc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtvojllbtz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.havefunace.top/Article/details/gtaabggngm.html

[B12] 跳出多层循环
来源：http://dali.hammf.cn/Article/details/gthloxqmbw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnqzz.top/Article/details/gtflrplwer.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yangfankeji.com/Article/details/gtrtplbymb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtkuhtzefl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gtdyvwxxmi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtevjcgcrz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.wangshuangyany.cn/Article/details/gtvepexpkh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsusdbiy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tanke756.top/Article/details/gtfvgpfvbf.html

[B13] 判断是否为数字
来源：http://dali.guannengcc.top/Article/details/gtghchertl.html

Py:   isinstance(x, (int, float))
来源：http://dali.andypj.xyz/Article/details/gtijnsouet.html

PHP:  is_numeric($x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegbgbdql.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwbpyaew.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxgsmwjt.html

Java: x instanceof Number
来源：http://dali.pengpengdd.cyou/Article/details/gtiplnpimo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhongyouzk.top/Article/details/gtguwpkwnj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ehwqpu.com/Article/details/gtnoyeyspr.html

C#:   x is int or double or decimal
来源：http://dali.mhx1999.top/Article/details/gtxyjtljmq.html

[B14] 判断值是否在集合内
来源：http://dali.316326.xyz/Article/details/gtazstdsuo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xylfe.cn/Article/details/gtmsbgzyrw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzxbfcyc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gtifhmbupa.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gtkuxlrcpa.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.iojbl.cn/Article/details/gtjlimspjf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.smart0.xyz/Article/details/gtawslioxf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtdmseczan.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gttwolujds.html

[B15] 布尔运算与取反
来源：http://dali.sysykeji.top/Article/details/gtxrrgglqv.html

Py:   a and b or not c
来源：http://dali.tian-w.cn/Article/details/gtocabfsqq.html

PHP:  $a && $b || !$c
来源：http://dali.guowangkeji.top/Article/details/gtiwptqxws.html

JS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtdeyhqexi.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtxybdfdix.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscpllbna.html

Go:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtfbmfhqxt.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtgvchuexj.html

C#:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtppunnjvj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtwkuvdgvk.html

Py:   if not data: return
来源：http://dali.shuidangran.top/Article/details/gtighrfxso.html

PHP:  if (!$data) { return; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnbfighvg.html

JS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtpydvcs.html

TS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gtocodovey.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtjmzobndg.html

Go:   if data == nil { return }
来源：http://dali.ppjwa.cn/Article/details/gtihmygfpk.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gtwmfozyrx.html

C#:   if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtprvucsbu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvumynejj.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtniybxqgf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzzouoxux.html

[C01] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtimkjkgjr.html

Py:   def add(a, b): return a + b
来源：http://dali.shzxlz.cn/Article/details/gtwsxwldei.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtoccdlzyr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtcrytdmtu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgabhorhk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyglzhpkv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sxryk.cn/Article/details/gthaqyiewc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.meibo888.top/Article/details/gtmgdujpeb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtsjldxdni.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gtzulalgaz.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gtyrikunqf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnknmyrhe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gteysnnrgm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtqygfbblv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gtathjwlbb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gtoazoxvek.html

Ruby: def greet(name = "World") = name
来源：http://dali.cashguo.top/Article/details/gtthtszrxt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hammf.cn/Article/details/gtzgayutpu.html

[C03] 可变参数
来源：http://dali.smart0.xyz/Article/details/gtxqkphgvr.html

Py:   def total(*args): return sum(args)
来源：http://dali.yvedp.cn/Article/details/gtvnsfzhjt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gtpovteyva.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtwzzwbwjj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtzhedkznn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zycfv.cn/Article/details/gtzpjysdgc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gtfsixorch.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dashuyun.cn/Article/details/gtxwdzkunz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shangyingyoupin.top/Article/details/gtnqiksfcb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jianghu66.top/Article/details/gttlthrtks.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.316326.xyz/Article/details/gtaxvigklz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvqsbhnj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gtpdyhpxei.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gtpelwrjbg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gtryjmvujr.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gtinzajhrc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtdjgyvibe.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtaijyqozb.html

[C05] 返回多个值
来源：http://dali.daxiang520.top/Article/details/gtmemgcsrg.html

Py:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gtzhezbola.html

PHP:  return [$a, $b];
来源：http://dali.haohaochexian.top/Article/details/gtshdruvnv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ydzc1.top/Article/details/gttafeuuko.html

TS:   return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gtloiapnsh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yueranfly.top/Article/details/gtickmsbgs.html

Go:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfytdpqa.html

Ruby: return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxogzjbwp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fzhhl.top/Article/details/gtvupjlhen.html


<!-- 参考信息 -->