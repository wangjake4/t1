代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gt2pawgvioh.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.316326.xyz/Article/details/gt2cbqhwbom.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gt2iqusknhb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.guannengcc.top/Article/details/gt2iscdhmwb.html

C#:   // 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gt2npkcmktc.html

[A15] 空值判断与默认值
来源：http://dali.yvedp.cn/Article/details/gt2brdxkbyf.html

Py:   value = data or "默认值"
来源：http://dali.andypj.xyz/Article/details/gt2ikrcobhz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gt2bvekpbgq.html

JS:   const value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gt2kwrhbfue.html

TS:   const value = data ?? "默认值";
来源：http://dali.hnqzz.top/Article/details/gt2hlnisjbp.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.smart0.xyz/Article/details/gt2auautdfd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sxryk.cn/Article/details/gt2tbuemmyp.html

Ruby: value = data || "默认值"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2azwacriu.html

C#:   var value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gt2jmbtscbf.html

[A16] 真假值判断规则
来源：http://dali.ydzc1.top/Article/details/gt2yzqshpgj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqoluqna.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfwvsodj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rruceaim.html

TS:   if (!x) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2pcuezlhr.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xinyue.icu/Article/details/gt2tcdsczqo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.nanxuanxn.top/Article/details/gt2uknruvbo.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.dianchejie.cn/Article/details/gt2xsmiasna.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sysykeji.top/Article/details/gt2ekxisviv.html

[A17] 位运算
来源：http://dali.hnxiangtu.top/Article/details/gt2luzyqamq.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gt2ulmscpto.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.cqqwz.cn/Article/details/gt2wrwqlpbu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gt2gpireqaw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gt2rqazcnxy.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gt2vpvxgild.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2gsrexlsn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdazlhmx.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gt2qkypzrhx.html

[A18] 字符与 ASCII 码互转
来源：http://dali.snrcjt.cn/Article/details/gt2ahgijbdm.html

Py:   ord("A"); chr(65)
来源：http://dali.nanxinkj.top/Article/details/gt2saroborn.html

PHP:  ord("A"); chr(65)
来源：http://dali.jianghu66.top/Article/details/gt2hryplrda.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.daria6918.cn/Article/details/gt2fgwrkwcs.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.smart0.xyz/Article/details/gt2ixdfwdyu.html

Java: (int) 'A'; (char) 65
来源：http://dali.gaohongyu789.top/Article/details/gt2naynnqws.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.snrcjt.cn/Article/details/gt2giktgitq.html

Ruby: "A".ord; 65.chr
来源：http://dali.316326.xyz/Article/details/gt2urlujkqc.html

C#:   (int)'A'; (char)65
来源：http://dali.jianghu66.top/Article/details/gt2ziltmtne.html

[A19] 交换两个变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfhdwwhd.html

Py:   a, b = b, a
来源：http://dali.xziqi.cn/Article/details/gt2jsfgtgmw.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhongyouzk.top/Article/details/gt2clqrlahh.html

JS:   [a, b] = [b, a];
来源：http://dali.wangdashe.top/Article/details/gt2jfxckjnj.html

TS:   [a, b] = [b, a];
来源：http://dali.birdmap.top/Article/details/gt2ktxzdnds.html

Java: int t = a; a = b; b = t;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qizmzgju.html

Go:   a, b = b, a
来源：http://dali.xziqi.cn/Article/details/gt2vgxjbwjq.html

Ruby: a, b = b, a
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwzzqodj.html

C#:   (a, b) = (b, a);
来源：http://dali.cucudq.cn/Article/details/gt2srcwcode.html

[A20] 读取标准输入
来源：http://dali.sweek.top/Article/details/gt2pkfcvtsk.html

Py:   name = input("请输入：")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tuamlglf.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.fzhhl.top/Article/details/gt2zlummxcr.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.pycfn.com/Article/details/gt2axttmoaq.html

TS:   // Node.js：readline 模块
来源：http://dali.havefunace.top/Article/details/gt2pholyusx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.c1oappe.top/Article/details/gt2juhavfnj.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.nanxuanxn.top/Article/details/gt2xwpjjoon.html

Ruby: gets.chomp
来源：http://dali.yonumen.top/Article/details/gt2ctjuhwqs.html

C#:   Console.ReadLine();
来源：http://dali.ybcxt.top/Article/details/gt2xlpbffdb.html

[A21] 保留指定小数位输出
来源：http://dali.smart0.xyz/Article/details/gt2uulwvtlz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.svipenyu.cn/Article/details/gt2mxvcfepi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.daxiang520.top/Article/details/gt2xidhrufq.html

JS:   (3.14159).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gt2ghavluvj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gt2dfezuhne.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifljmhsb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gt2cbngcfpp.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gt2ciwslxxw.html

C#:   3.14159.ToString("F2")
来源：http://dali.gotoacloud.top/Article/details/gt2jctztfbw.html

[A22] 获取字符串长度
来源：http://dali.ydzc1.top/Article/details/gt2rnsftsgo.html

Py:   len(s)
来源：http://dali.cucudq.cn/Article/details/gt2kkfhhcrp.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.fzhhl.top/Article/details/gt2illmiqas.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258.top/Article/details/gt2paoptual.html

TS:   s.length
来源：http://dali.cheryme.top/Article/details/gt2vipqyjbg.html

Java: s.length()
来源：http://dali.yuxming.cn/Article/details/gt2bbhxfoeo.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xziqi.cn/Article/details/gt2zybjmzml.html

Ruby: s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2eotcfveb.html

C#:   s.Length
来源：http://dali.tian-w.cn/Article/details/gt2ypybjune.html

[A23] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gt2ddthxnzx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.nanxuanxn.top/Article/details/gt2aqjyuiwj.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdjuhdfb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.0kj1m.cn/Article/details/gt2kjsxtqwt.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gt2rubnoulg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.mhx1999.top/Article/details/gt2swzqvsus.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pewxyhrd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gt2qyfwjvyp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.bjfxy.top/Article/details/gt2jyzepwmx.html

[A24] 去除首尾空白
来源：http://dali.vqdsnc.cn/Article/details/gt2yodnoesu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cashguo.top/Article/details/gt2syotwmyv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlvwqmln.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ybcxt.top/Article/details/gt2spsfkyhb.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gt2qkardmrz.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cashguo.top/Article/details/gt2kycyloom.html

Go:   strings.TrimSpace(s)
来源：http://dali.yangfankeji.com/Article/details/gt2loxxqgfj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yvedp.cn/Article/details/gt2uvngjrch.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nttqoswx.html

[A25] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gt2ablaphna.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhengqikj.top/Article/details/gt2ymcggonu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.iojbl.cn/Article/details/gt2fokassfc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhengqikj.top/Article/details/gt2vuawmmab.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cqqwz.cn/Article/details/gt2dserivjv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhixingplan.top/Article/details/gt2koeyuimn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gt2iirkbgiw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jianghu66.top/Article/details/gt2sjrazkie.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gt2qxqhgnid.html

[A26] 类型转换总览
来源：http://dali.hongshengwenyu.top/Article/details/gt2atzfcztv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenzaomai.com/Article/details/gt2htqwnjkq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xinyue.icu/Article/details/gt2ohhfdvcx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yonumen.top/Article/details/gt2iacnuajl.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zycfv.cn/Article/details/gt2hrlvwljh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gt2vwktasmq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.chenlongwang.top/Article/details/gt2qtycubcy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.316326.xyz/Article/details/gt2wvpfhiiu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.smart0.xyz/Article/details/gt2lzxfwsqj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2wdqbmerx.html

B. 流程控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqaplqol.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ezcshvno.html

[B01] 条件判断 if / else
来源：http://dali.cashguo.top/Article/details/gt2lrgudegb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.9152youxi.cn/Article/details/gt2kcdytjij.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xylfe.cn/Article/details/gt2gbhdtuwr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gt2qrifnavn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gt2oudzvhgf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gt2voqtdkny.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ivvv.top/Article/details/gt2erosomiz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.9152youxi.cn/Article/details/gt2wuwtewhn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdwarqfl.html

[B02] 多分支 else if / elif
来源：http://dali.dashuyun.cn/Article/details/gt2fkxpqlbf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhoulong.xyz/Article/details/gt2qxusaqwi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cheryme.top/Article/details/gt2uaegvwnk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gt2tvqedfey.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gt2ebrhqrcl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gt2qwxmkgtf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.andypj.xyz/Article/details/gt2kfiwqcax.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinqigufen.top/Article/details/gt2jungtinf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gt2mdmtaobe.html

[B03] switch / match / case
来源：http://dali.hfpthk.cn/Article/details/gt2rzglpibj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhongyouzk.top/Article/details/gt2agfkjdyb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gt2jsdrvgiz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gt2ofcqdkiv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gt2tdfcuggz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gt2xpbzbuol.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.daxiang520.top/Article/details/gt2jejlaadw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenlongwang.top/Article/details/gt2fekofcpj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.smart0.xyz/Article/details/gt2lpqoqbim.html

[B04] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gt2jtuwamdx.html

Py:   for i in range(10): print(i)
来源：http://dali.snrcjt.cn/Article/details/gt2tssovurc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ybcxt.top/Article/details/gt2fssikblx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gt2hyofggfp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jyoumei.cn/Article/details/gt2sbvojhot.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yj202588.top/Article/details/gt2tausurdp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ybcxt.top/Article/details/gt2clxhfwjw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhixingplan.top/Article/details/gt2fnqueigo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yuxming.cn/Article/details/gt2khvneqpz.html

[B05] 遍历数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbenhjvl.html

Py:   for item in arr: print(item)
来源：http://dali.xinyue.icu/Article/details/gt2tawlqvzf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sweek.top/Article/details/gt2wnayerov.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.havefunace.top/Article/details/gt2plaankva.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gaohongyu789.top/Article/details/gt2sulgkzgi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jyoumei.cn/Article/details/gt2belikxvh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.316326.xyz/Article/details/gt2toppgvuc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgoycea.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fzhhl.top/Article/details/gt2krvjtktp.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258888.top/Article/details/gt2vvowiggk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sweek.top/Article/details/gt2yznauvnb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ezdsogqr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nwbrower.top/Article/details/gt2jfiskget.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gt2qpyledaf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.c1oappe.top/Article/details/gt2zbfwcmrn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cucudq.cn/Article/details/gt2nemebugz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xinyue.icu/Article/details/gt2audkxins.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shzxlz.cn/Article/details/gt2rbrbirtt.html

[B07] while 循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2zealvwyo.html

Py:   while i < 10: i += 1
来源：http://dali.dashuyun.cn/Article/details/gt2vbomdxvk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tian-w.cn/Article/details/gt2xrgdnsuz.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gt2kzcbyioj.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gt2iabovefj.html

Java: while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gt2bygxiwpu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sufxvd.cn/Article/details/gt2pimfynhf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hnqzz.top/Article/details/gt2tpxeuqsq.html

C#:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gt2ktesknld.html

[B08] do-while（至少执行一次）
来源：http://dali.xuetiantiany.cn/Article/details/gt2npkzzskt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cucudq.cn/Article/details/gt2kfrdldmj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sweek.top/Article/details/gt2uscfferl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2xpgecrow.html

TS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gt2onlwtpqq.html

Java: do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gt2ddjxcexx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.0kj1m.cn/Article/details/gt2ohlyniay.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oyizpiaq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2kkwcfvfi.html

[B09] break 与 continue
来源：http://dali.hysaishi.cn/Article/details/gt2mwxlsikp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigfzy.top/Article/details/gt2poikvyqi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2klaxmyme.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gt2pxujafwt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gt2trucfopd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gt2ounqtnri.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.meibo888.top/Article/details/gt2exjtgder.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2eojpdsno.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2ttbtbwqw.html

[B10] 遍历同时拿索引
来源：http://dali.zhengqikj.top/Article/details/gt2dqmdduqj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj20258.top/Article/details/gt2mhgkuoer.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aiykxcgj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gt2ewfnyrhu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gt2pudhohjt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xylfe.cn/Article/details/gt2wttalsyy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tian-w.cn/Article/details/gt2ngtnwnki.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yonumen.top/Article/details/gt2ujknicun.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzsgejrn.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gt2pwvsmvyn.html

Py:   list(range(0, 10, 2))
来源：http://dali.ppjwa.cn/Article/details/gt2njvjhgxm.html

PHP:  range(0, 10, 2);
来源：http://dali.redwolf501.top/Article/details/gt2wogwmlsd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2judeugel.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gt2fwrzwvgu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fengsongda.top/Article/details/gt2akdvhwvv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.vqdsnc.cn/Article/details/gt2afummdqf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.c1oappe.top/Article/details/gt2zjovpjll.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gt2mqppynzc.html

[B12] 跳出多层循环
来源：http://dali.ybcxt.top/Article/details/gt2kqquesgj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.kuanghao11.cn/Article/details/gt2crxceswh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dashuyun.cn/Article/details/gt2rvnefghe.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gt2ekhoyxit.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gt2unbkkurp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovtyzjeg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhoulong.xyz/Article/details/gt2fymvsoef.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.c1oappe.top/Article/details/gt2cpqmjlfh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hfpthk.cn/Article/details/gt2mqxksgxk.html

[B13] 判断是否为数字
来源：http://dali.hnqzz.top/Article/details/gt2zpxndrrq.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuanzhike.top/Article/details/gt2dqycyaer.html

PHP:  is_numeric($x)
来源：http://dali.jqgfzy.top/Article/details/gt2ydsmmcpv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2whmvhdba.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258888.top/Article/details/gt2umwiopdm.html

Java: x instanceof Number
来源：http://dali.jianghu66.top/Article/details/gt2olychkeh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gogol.net.cn/Article/details/gt2zupteaxt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gt2wxqccutc.html

C#:   x is int or double or decimal
来源：http://dali.hywenlv.cn/Article/details/gt2jjloxzev.html

[B14] 判断值是否在集合内
来源：http://dali.wangshuangyany.cn/Article/details/gt2jpyducic.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gt2nspgotyt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hfpthk.cn/Article/details/gt2pwvemjxy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2degnrkiz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gt2zbqyfwvb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2gqeftuvp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tian-w.cn/Article/details/gt2bqjzdtbm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.meibo888.top/Article/details/gt2hjgqqgtu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.316326.xyz/Article/details/gt2izwrramf.html

[B15] 布尔运算与取反
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwljrkxz.html

Py:   a and b or not c
来源：http://dali.zhengqikj.top/Article/details/gt2zmfhrars.html

PHP:  $a && $b || !$c
来源：http://dali.nanxuanxn.top/Article/details/gt2vdxavvtj.html

JS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2uhfehgku.html

TS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2oiwzkyvf.html

Java: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2tiyyhngq.html

Go:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2dzknerxg.html

Ruby: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gt2xoctsdcz.html

C#:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2deupirgo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtakdcdm.html

Py:   if not data: return
来源：http://dali.yj20258888.top/Article/details/gt2kdtpkjmd.html

PHP:  if (!$data) { return; }
来源：http://dali.0kj1m.cn/Article/details/gt2obmvzwrj.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gt2orufkany.html

TS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gt2lrycgqmt.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gt2vsrptgyi.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gt2fbudyitu.html

Ruby: return if data.nil?
来源：http://dali.yueranfly.top/Article/details/gt2qvynrygq.html

C#:   if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gt2xsyshjmq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2fklxkaix.html

C. 函数与作用域
来源：http://dali.smart0.xyz/Article/details/gt2twnxdxru.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2njxwdplh.html

[C01] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gt2yfldghur.html

Py:   def add(a, b): return a + b
来源：http://dali.daxiang520.top/Article/details/gt2tubdkvkr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gt2kqtzuaew.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2fseepwoc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2liytlocr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdlnqnjr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cqqwz.cn/Article/details/gt2wlttrhyb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tian-w.cn/Article/details/gt2bigkexmu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2ouspayyl.html

[C02] 默认参数
来源：http://dali.yueranfly.top/Article/details/gt2ketxedxw.html

Py:   def greet(name="World"): return name
来源：http://dali.tianlin.xyz/Article/details/gt2gmrbvxgf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gt2jhqgpzsz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtpqplsy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2kgeauhdy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gt2ollrtevh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.andypj.xyz/Article/details/gt2vjtwwwvl.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnqzz.top/Article/details/gt2remidtbk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2agnokdvx.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gt2nmavrrpx.html

Py:   def total(*args): return sum(args)
来源：http://dali.shzxlz.cn/Article/details/gt2upacssqu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gt2ovbngmce.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gt2nqiqywmw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gt2klzblylq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gt2vscavyvv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuxming.cn/Article/details/gt2oebumnca.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ybcxt.top/Article/details/gt2ykqvcjxw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dianchejie.cn/Article/details/gt2qsnunmed.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcgupwug.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sweek.top/Article/details/gt2kuwxitbf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbjgfcti.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2gbohakkq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tanke756.top/Article/details/gt2zaneuspl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gt2ndbbzvcf.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gt2lsylqukp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gt2hesxmkln.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxcqtjou.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gt2drctnnvw.html


<!-- 参考信息 -->