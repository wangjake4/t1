代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.zdqjudy.top/Article/details/gt2tzscmdtz.html

TS:   const value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gt2hioiokko.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhoulong.xyz/Article/details/gt2qgibmizd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hfpthk.cn/Article/details/gt2npjlrsub.html

Ruby: value = data || "默认值"
来源：http://dali.yj20258888.top/Article/details/gt2mnxqqwvz.html

C#:   var value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gt2argrxtbi.html

[A16] 真假值判断规则
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cywvthcm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.redwolf501.top/Article/details/gt2ofrzazvf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ppjwa.cn/Article/details/gt2lvyxefsb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gzhubu.top/Article/details/gt2epybakxy.html

TS:   if (!x) {}
来源：http://dali.zhixingplan.top/Article/details/gt2afbcdwsb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.daria6918.cn/Article/details/gt2envrrbzz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.birdmap.top/Article/details/gt2hiurvltr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cashguo.top/Article/details/gt2bgjqewmz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jianghu66.top/Article/details/gt2awufhrzb.html

[A17] 位运算
来源：http://dali.316326.xyz/Article/details/gt2htmcgfvg.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gt2fgmjolyx.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.guannengcc.top/Article/details/gt2xokihdxg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gt2rdhsghmd.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gt2pwbvzmqn.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gt2omidionn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gt2belixljm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gt2osaburap.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gt2bbbaxgoj.html

[A18] 字符与 ASCII 码互转
来源：http://dali.aizwys.cn/Article/details/gt2lgjqadsi.html

Py:   ord("A"); chr(65)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhlufglg.html

PHP:  ord("A"); chr(65)
来源：http://dali.jianghu66.top/Article/details/gt2jirrkyem.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yuanzhike.top/Article/details/gt2syyrsrjr.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fweulwip.html

Java: (int) 'A'; (char) 65
来源：http://dali.jiagoushi.top/Article/details/gt2hotulraq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhiwuduotai.top/Article/details/gt2llecbkzh.html

Ruby: "A".ord; 65.chr
来源：http://dali.daxiang520.top/Article/details/gt2jhpksgkq.html

C#:   (int)'A'; (char)65
来源：http://dali.shuidangran.top/Article/details/gt2atfxahxj.html

[A19] 交换两个变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvhfpjll.html

Py:   a, b = b, a
来源：http://dali.jinqigfzy.top/Article/details/gt2zksaxgtu.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.dashuyun.cn/Article/details/gt2ykcadmio.html

JS:   [a, b] = [b, a];
来源：http://dali.havefunace.top/Article/details/gt2qmkxlyxv.html

TS:   [a, b] = [b, a];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2myhbywrz.html

Java: int t = a; a = b; b = t;
来源：http://dali.jyoumei.cn/Article/details/gt2gjnddtsb.html

Go:   a, b = b, a
来源：http://dali.meibo888.top/Article/details/gt2gabaildm.html

Ruby: a, b = b, a
来源：http://dali.yongpay.top/Article/details/gt2ibcbwalz.html

C#:   (a, b) = (b, a);
来源：http://dali.zhixingplan.top/Article/details/gt2pqthxhcs.html

[A20] 读取标准输入
来源：http://dali.jinqigfzy.top/Article/details/gt2zyqdorcx.html

Py:   name = input("请输入：")
来源：http://dali.yongpay.top/Article/details/gt2rnordyvl.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jqgufenzy.top/Article/details/gt2tuyxasyx.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbbthjif.html

TS:   // Node.js：readline 模块
来源：http://dali.yonumen.top/Article/details/gt2ojeaniov.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yongpay.top/Article/details/gt2muuepzoq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gaohongyu789.top/Article/details/gt2opcqypql.html

Ruby: gets.chomp
来源：http://dali.feifeiyinyue.top/Article/details/gt2ysptbpkv.html

C#:   Console.ReadLine();
来源：http://dali.0kj1m.cn/Article/details/gt2ntqhsxzp.html

[A21] 保留指定小数位输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apfnyycj.html

Py:   f"{3.14159:.2f}"
来源：http://dali.aizwys.cn/Article/details/gt2bbfrxkoc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gt2zpuaaubc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gt2mxaburjr.html

TS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gt2kenfwueb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gt2jfpqeqeg.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gt2kdrqbbxi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gt2cctfwlci.html

C#:   3.14159.ToString("F2")
来源：http://dali.daxiang520.top/Article/details/gt2cbzehelk.html

[A22] 获取字符串长度
来源：http://dali.ppjwa.cn/Article/details/gt2apmdykaf.html

Py:   len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpjqcznn.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.kuanghao11.cn/Article/details/gt2nwngzgot.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.guowangkeji.top/Article/details/gt2sivhppzk.html

TS:   s.length
来源：http://dali.ydzc1.top/Article/details/gt2uxrenqtb.html

Java: s.length()
来源：http://dali.jlsjyb.cn/Article/details/gt2dzlscrxn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2rlgkanyb.html

Ruby: s.length
来源：http://dali.jqgfzy.top/Article/details/gt2nasquwdg.html

C#:   s.Length
来源：http://dali.yonumen.top/Article/details/gt2amlijxnw.html

[A23] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gt2ehpsccpv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgqadhnd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.haohaochexian.top/Article/details/gt2omnvoddr.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2esbwdwff.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuanzx.com/Article/details/gt2pcdjxyqz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gt2zvcpxbvo.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hammf.cn/Article/details/gt2iqqtxedp.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gt2qilwzabm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.bjfxy.top/Article/details/gt2prawvxkx.html

[A24] 去除首尾空白
来源：http://dali.gaohongyu789.top/Article/details/gt2xkqxxaci.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.andypj.xyz/Article/details/gt2uozksjqm.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.dashuyun.cn/Article/details/gt2hwvrljff.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sweek.top/Article/details/gt2hdxttvwt.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obzkabms.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.daria6918.cn/Article/details/gt2wzyatbyj.html

Go:   strings.TrimSpace(s)
来源：http://dali.sweek.top/Article/details/gt2nkmtfqlo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfcvwnwk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jiagoushi.top/Article/details/gt2fugkkniv.html

[A25] 字符串比较
来源：http://dali.jyoumei.cn/Article/details/gt2canrgzlr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibsmpufp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.dashuyun.cn/Article/details/gt2vvzhnyau.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daria6918.cn/Article/details/gt2vzlotabn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2meorletb.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yangfankeji.com/Article/details/gt2rutcvgoc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cugumxhv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.fengsongda.top/Article/details/gt2cjpcuhda.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.dashuyun.cn/Article/details/gt2ihayankx.html

[A26] 类型转换总览
来源：http://dali.sysykeji.top/Article/details/gt2lebafllq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sxryk.cn/Article/details/gt2rbjqvojm.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.haohaochexian.top/Article/details/gt2xaxgtnac.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.c1oappe.top/Article/details/gt2xclsirek.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ydzc1.top/Article/details/gt2bfvgdhjl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gt2dskrtjcb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinqigufen.top/Article/details/gt2rtrgfflq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj20258.top/Article/details/gt2tokwsqbm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gt2egziorsu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2aubxprct.html

B. 流程控制
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwtyksuk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ozaopnhh.html

[B01] 条件判断 if / else
来源：http://dali.ybcxt.top/Article/details/gt2uekyfpyg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.meibo888.top/Article/details/gt2hxbiczgm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfsaljyj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gt2xtawqqwm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmtxzsnx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yikykqqg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.aizwys.cn/Article/details/gt2serrkwnj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tanke756.top/Article/details/gt2jwyyxqzp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gt2hkhvqddy.html

[B02] 多分支 else if / elif
来源：http://dali.shzxlz.cn/Article/details/gt2jgcowrvt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hnxiangtu.top/Article/details/gt2anrbjcvl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jqgfzy.top/Article/details/gt2kpqgwkyz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gt2tmgpgcfb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gt2xbrzvdzj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gt2hciqfhxl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gogol.net.cn/Article/details/gt2wzniiqql.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.c1oappe.top/Article/details/gt2grxdekrq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gt2mubwggfv.html

[B03] switch / match / case
来源：http://dali.ybcxt.top/Article/details/gt2emfhhaqv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinqigfzy.top/Article/details/gt2kfzrlrgj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gt2krdwfugj.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gt2jlscuzdq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gt2gtohjgvx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gt2jutamruy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qyppoywk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yuanzhike.top/Article/details/gt2eluejnll.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.vqdsnc.cn/Article/details/gt2xovgjkzk.html

[B04] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gt2tforspvb.html

Py:   for i in range(10): print(i)
来源：http://dali.sysykeji.top/Article/details/gt2nxwxauvp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vykvbqhl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gt2vewijobc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gt2pfunymqo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhongyouzk.top/Article/details/gt2vqwnjjog.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jlsjyb.cn/Article/details/gt2fkuyjprj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zycfv.cn/Article/details/gt2cyoecjid.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzdrbmaj.html

[B05] 遍历数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gt2vbghcnkd.html

Py:   for item in arr: print(item)
来源：http://dali.dashuyun.cn/Article/details/gt2avfoszts.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rldoppuy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixuqboho.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daxiang520.top/Article/details/gt2itqlmgud.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aibaodan.cn/Article/details/gt2oczlwcor.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.9152youxi.cn/Article/details/gt2ujbhplfr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gzhubu.top/Article/details/gt2satfwnnz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.kuanghao11.cn/Article/details/gt2gfqgypvd.html

[B06] 遍历字典 / 对象
来源：http://dali.nwbrower.top/Article/details/gt2dtfzonpd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ehwqpu.com/Article/details/gt2anxhrpbj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2dqdstdyh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gt2wjgnywxa.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenzaomai.com/Article/details/gt2uryyyojo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigufen.top/Article/details/gt2rosiijlp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhwewruk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.vqdsnc.cn/Article/details/gt2tukhhmwc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2akpjxgpr.html

[B07] while 循环
来源：http://dali.tianlin.xyz/Article/details/gt2uvftvlpe.html

Py:   while i < 10: i += 1
来源：http://dali.dashuyun.cn/Article/details/gt2gwroktqb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cdnleiting.top/Article/details/gt2xxmztzaa.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blrtdfot.html

TS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gt2sgxbrpeo.html

Java: while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gt2eltfvpia.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldrgctaz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tianlin.xyz/Article/details/gt2asaqtsdh.html

C#:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xycwrfej.html

[B08] do-while（至少执行一次）
来源：http://dali.chenzaomai.com/Article/details/gt2qjwygade.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nanxuanxn.top/Article/details/gt2zeztnzzh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.pycfn.com/Article/details/gt2ntmekygb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kcjpvovq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gt2kerpnhau.html

Java: do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwtfsnly.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2saeqqlag.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xinyue.icu/Article/details/gt2fjkvacxs.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gt2viwieddy.html

[B09] break 与 continue
来源：http://dali.tianlin.xyz/Article/details/gt2cgsjeirx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.316326.xyz/Article/details/gt2rswyuoyr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gt2bntpclwh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gt2czwkzswj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2crpftvkr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gt2dqmhhewc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuanzhike.top/Article/details/gt2vfrkdqne.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gt2xqvlkpxd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gt2nttyklcv.html

[B10] 遍历同时拿索引
来源：http://dali.smart0.xyz/Article/details/gt2xifaaqco.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jlsjyb.cn/Article/details/gt2vodkymug.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhengqikj.top/Article/details/gt2xhitbxwb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gt2cvtxwtvv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gt2gboxossp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hysaishi.cn/Article/details/gt2ftaqtjrb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.dianchejie.cn/Article/details/gt2dhirnand.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenlongwang.top/Article/details/gt2zouxawvy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj20258888.top/Article/details/gt2udurodoz.html

[B11] 生成数字序列 / 区间
来源：http://dali.jqgfzy.top/Article/details/gt2mqhbolxi.html

Py:   list(range(0, 10, 2))
来源：http://dali.kuanghao11.cn/Article/details/gt2xmxcppkj.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gt2maxcgtyr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gt2zdeuoplz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gt2maybxuyv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xziqi.cn/Article/details/gt2dvjfkeuu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sufxvd.cn/Article/details/gt2nbwebbuy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cqqwz.cn/Article/details/gt2bgwqnoaf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhixingplan.top/Article/details/gt2ldfmmktl.html

[B12] 跳出多层循环
来源：http://dali.yj20258888.top/Article/details/gt2nbuaapmy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daria6918.cn/Article/details/gt2oowpscoi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ydzc1.top/Article/details/gt2tfosbtcz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gt2jvyjsqym.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gt2mjvmlvvx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2duxpjpun.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxinkj.top/Article/details/gt2xyauakdo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fzhhl.top/Article/details/gt2ayiekcdj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhixingplan.top/Article/details/gt2wdmoltdm.html

[B13] 判断是否为数字
来源：http://dali.yanxiufei.cn/Article/details/gt2ujfitdet.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258.top/Article/details/gt2cmkekoww.html

PHP:  is_numeric($x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2acooskjz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gt2ucxbsifw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gt2xparxsdz.html

Java: x instanceof Number
来源：http://dali.cheryme.top/Article/details/gt2cvngopux.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aibaodan.cn/Article/details/gt2fsfryndv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yanxiufei.cn/Article/details/gt2ywnkmbji.html

C#:   x is int or double or decimal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukezcdht.html

[B14] 判断值是否在集合内
来源：http://dali.yanxiufei.cn/Article/details/gt2sggrhrqj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xylfe.cn/Article/details/gt2ybuxwenr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.iojbl.cn/Article/details/gt2bhcjikad.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2egyvbtid.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2frltwwpz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuanzx.com/Article/details/gt2wzysciaq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guowangkeji.top/Article/details/gt2eipyfxht.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ielcynky.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258.top/Article/details/gt2dncyfank.html

[B15] 布尔运算与取反
来源：http://dali.c1oappe.top/Article/details/gt2lfyupldm.html

Py:   a and b or not c
来源：http://dali.hnqzz.top/Article/details/gt2hkfdheds.html

PHP:  $a && $b || !$c
来源：http://dali.sxryk.cn/Article/details/gt2xyklksls.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2xahxzydk.html

TS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2rluratrd.html

Java: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgebbsmc.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2ngxhfzgf.html

Ruby: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2bpxolgbo.html

C#:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gt2tcqpxxyl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.smart0.xyz/Article/details/gt2dreylxjf.html

Py:   if not data: return
来源：http://dali.fengsongda.top/Article/details/gt2yaqdovtk.html

PHP:  if (!$data) { return; }
来源：http://dali.yangfankeji.com/Article/details/gt2voitvfwb.html

JS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gt2uqoochxd.html

TS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gt2grzybmtj.html

Java: if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bjinncvo.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gt2hopoohiq.html

Ruby: return if data.nil?
来源：http://dali.ydzc1.top/Article/details/gt2sjljdysm.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gt2bjryfzjk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2rmalmhgx.html

C. 函数与作用域
来源：http://dali.hnqzz.top/Article/details/gt2xukqjill.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2beyaclaz.html

[C01] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gt2tdfnhhzg.html

Py:   def add(a, b): return a + b
来源：http://dali.fengsongda.top/Article/details/gt2yghldroe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2uhkyvvad.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2stzkkvsr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2ozmxlfvn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gt2kricnnel.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gt2edepwksv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gt2ytagnycw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2zekqedyg.html

[C02] 默认参数
来源：http://dali.zdqjudy.top/Article/details/gt2cvmibpvk.html

Py:   def greet(name="World"): return name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbmhkdjm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gt2ihlsngca.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2qeqrmjul.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2aixjdmuk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fzhhl.top/Article/details/gt2viminflh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gt2zqwimdkz.html

Ruby: def greet(name = "World") = name
来源：http://dali.dashuyun.cn/Article/details/gt2qaqqyalg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cashguo.top/Article/details/gt2vkvyrmoo.html

[C03] 可变参数
来源：http://dali.gzhubu.top/Article/details/gt2mmflmrew.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gt2eozunfdx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nanxuanxn.top/Article/details/gt2leerwubg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gt2pjzjaqbi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eghzbfpb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gt2aalxtpdh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.316326.xyz/Article/details/gt2pxnqiqvl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oesolofg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bnfbratu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gt2zlgsacgu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangdashe.top/Article/details/gt2gkxynbel.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ppjwa.cn/Article/details/gt2cmoojwms.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ydfvalzi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gt2fpzjuqxj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aibaodan.cn/Article/details/gt2sfzenqtz.html

Go:   // 无：用配置结构体参数
来源：http://dali.svipenyu.cn/Article/details/gt2xzydngod.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gt2ruihyfmd.html

C#:   f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2wccfmscx.html

[C05] 返回多个值
来源：http://dali.xuanzx.com/Article/details/gt2nyeiskny.html

Py:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbaedczd.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gt2bvkaztdg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2josekybi.html

TS:   return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gt2zvriivvs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sufxvd.cn/Article/details/gt2frbfbrya.html

Go:   return a, b
来源：http://dali.iojbl.cn/Article/details/gt2shtjtdmp.html

Ruby: return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gt2acgcnyxu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gt2gfrteiou.html


<!-- 参考信息 -->