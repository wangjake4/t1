代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhoulong.xyz/Article/details/gtbwyffgkt.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yj20258.top/Article/details/gtmiwmiktf.html

TS:   if (!x) {}
来源：http://dali.0kj1m.cn/Article/details/gtcxjkitvj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jianghu66.top/Article/details/gtzryofqka.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinqigufen.top/Article/details/gtuzirnfhd.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jqgfzy.top/Article/details/gtbksmbctr.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cdnleiting.top/Article/details/gtkjmeqhjl.html

[A17] 位运算
来源：http://dali.redwolf501.top/Article/details/gtvdxemylb.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtaxnktfue.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtrvievryb.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecrkbgio.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtqmufqavb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtqhgyypcg.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtualfsqlb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gtmfojegov.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtgwnucqnl.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcoazwuq.html

Py:   ord("A"); chr(65)
来源：http://dali.ydzc1.top/Article/details/gtnzucpcvs.html

PHP:  ord("A"); chr(65)
来源：http://dali.yueranfly.top/Article/details/gtcojxjkut.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jqgufenzy.top/Article/details/gtetohozuz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ivvv.top/Article/details/gtcsomlyql.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinqigfzy.top/Article/details/gtfjwhrkcd.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yuxming.cn/Article/details/gtoryablbq.html

Ruby: "A".ord; 65.chr
来源：http://dali.ppjwa.cn/Article/details/gtsovyatdq.html

C#:   (int)'A'; (char)65
来源：http://dali.cdnleiting.top/Article/details/gtclaoiswr.html

[A19] 交换两个变量
来源：http://dali.yj20258.top/Article/details/gthggjzvce.html

Py:   a, b = b, a
来源：http://dali.xinyue.icu/Article/details/gtikxrruvt.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.bjfxy.top/Article/details/gthbkwgqwx.html

JS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gtccphhymi.html

TS:   [a, b] = [b, a];
来源：http://dali.sysykeji.top/Article/details/gthptndayu.html

Java: int t = a; a = b; b = t;
来源：http://dali.vqdsnc.cn/Article/details/gtnhjrztmj.html

Go:   a, b = b, a
来源：http://dali.meibo888.top/Article/details/gtdxezevoh.html

Ruby: a, b = b, a
来源：http://dali.yongpay.top/Article/details/gtlosgxasd.html

C#:   (a, b) = (b, a);
来源：http://dali.xziqi.cn/Article/details/gtuodnnayc.html

[A20] 读取标准输入
来源：http://dali.chenlongwang.top/Article/details/gtgxznfzen.html

Py:   name = input("请输入：")
来源：http://dali.bjfxy.top/Article/details/gtzpuwtizp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jianghu66.top/Article/details/gtqynnfyrw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hysaishi.cn/Article/details/gtefzldrjm.html

TS:   // Node.js：readline 模块
来源：http://dali.hysaishi.cn/Article/details/gttbufxhjd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cashguo.top/Article/details/gtmyyhyoqv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tianlin.xyz/Article/details/gtltdeevdp.html

Ruby: gets.chomp
来源：http://dali.yj202588.top/Article/details/gtbdnmbbyz.html

C#:   Console.ReadLine();
来源：http://dali.ydzc1.top/Article/details/gthbtgqsen.html

[A21] 保留指定小数位输出
来源：http://dali.haohaochexian.top/Article/details/gtxvmiqvza.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hywenlv.cn/Article/details/gtfkgtelee.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yangfankeji.com/Article/details/gteorpthud.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sweek.top/Article/details/gtmwdoddgm.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtbvrbxocb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtkqxfarlq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hongshengwenyu.top/Article/details/gtzipybaxe.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gtgenjbpxa.html

C#:   3.14159.ToString("F2")
来源：http://dali.redwolf501.top/Article/details/gtkyiuqfuk.html

[A22] 获取字符串长度
来源：http://dali.smart0.xyz/Article/details/gthqkmbocf.html

Py:   len(s)
来源：http://dali.tianlin.xyz/Article/details/gtlkekbonu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jqgfzy.top/Article/details/gtvsmwzkfy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sysykeji.top/Article/details/gtpgfcbbkq.html

TS:   s.length
来源：http://dali.yj20258.top/Article/details/gtvyxeylyt.html

Java: s.length()
来源：http://dali.chenzaomai.com/Article/details/gttblorhfk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtfldwafvq.html

Ruby: s.length
来源：http://dali.jqgufenzy.top/Article/details/gtxeyouinl.html

C#:   s.Length
来源：http://dali.dianchejie.cn/Article/details/gtwuxyvgli.html

[A23] 大小写转换
来源：http://dali.meibo888.top/Article/details/gttzxrisuz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jqgufenzy.top/Article/details/gtigshizit.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.aizwys.cn/Article/details/gtiqtsfldl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shzxlz.cn/Article/details/gtgbfyykid.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yueranfly.top/Article/details/gtzvkzishr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoorxgino.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.chenlongwang.top/Article/details/gtpwvceytt.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gtcmprsqbk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.9152youxi.cn/Article/details/gtxcjwigtp.html

[A24] 去除首尾空白
来源：http://dali.yueranfly.top/Article/details/gtqqmyklpg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xylfe.cn/Article/details/gtyxmnbczg.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.redwolf501.top/Article/details/gtahcldzzp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtxdtfauff.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gtfgtjnggi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.smart0.xyz/Article/details/gtgozfpleg.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhengqikj.top/Article/details/gtvedyhpbn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hongshengwenyu.top/Article/details/gtlfrbxiel.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cdnleiting.top/Article/details/gtwiwnvurn.html

[A25] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtvbdyumtx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tian-w.cn/Article/details/gtwagacqmv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yvedp.cn/Article/details/gtffjyhzbm.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258.top/Article/details/gtbthfdauh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gogol.net.cn/Article/details/gtlfwjkhoa.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hfpthk.cn/Article/details/gtuuxlxoes.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.svipenyu.cn/Article/details/gtaxsrweiq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jianghu66.top/Article/details/gtbeyvxujt.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gtadvfrybn.html

[A26] 类型转换总览
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyuhvcjz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hongshengwenyu.top/Article/details/gtcfuanfgm.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xziqi.cn/Article/details/gtwpugefhy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ydzc1.top/Article/details/gtqpofwwzn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ppjwa.cn/Article/details/gttdytudln.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pengpengdd.cyou/Article/details/gtqtctufrd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhengqikj.top/Article/details/gtwgcxzdfl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hywenlv.cn/Article/details/gtsbilifyx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.gzhubu.top/Article/details/gtmafkkfyd.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtzbintebi.html

B. 流程控制
来源：http://dali.yongpay.top/Article/details/gtmvtjankq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtydhrehhq.html

[B01] 条件判断 if / else
来源：http://dali.cdnleiting.top/Article/details/gtcgqnhacg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.0kj1m.cn/Article/details/gtcabnlijl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gthdophtxz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtufgtrkpi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtkzwqoowy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gthquvojgx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ybcxt.top/Article/details/gthpjusfoz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.aizwys.cn/Article/details/gtotxfzdgd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gtmscxipho.html

[B02] 多分支 else if / elif
来源：http://dali.aibaodan.cn/Article/details/gtwmktkawi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fzhhl.top/Article/details/gtqwkgiaqn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jqgufenzy.top/Article/details/gtunllkqib.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gtsamjjoah.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtqmaxvnyw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtezlduaks.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jyoumei.cn/Article/details/gtvfinaeeo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrtcbftq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtnffgzfhr.html

[B03] switch / match / case
来源：http://dali.aibaodan.cn/Article/details/gtutfpkmir.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.316326.xyz/Article/details/gtmmfqpoai.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gtnafxtqyh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtplbnxyfd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sweek.top/Article/details/gtsrcfyhff.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtdnchqjvr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.haohaochexian.top/Article/details/gtbcswvdbw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.kuanghao11.cn/Article/details/gtonkonjfs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gtowshxmbg.html

[B04] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtsjcnuzgh.html

Py:   for i in range(10): print(i)
来源：http://dali.hfpthk.cn/Article/details/gtzhqhknht.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cdnleiting.top/Article/details/gtouvjwlgy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gtllfhtmla.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtsnaeajnp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hywenlv.cn/Article/details/gtmpyvqslu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnxiangtu.top/Article/details/gtopxvlbkq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.fengsongda.top/Article/details/gtpoqtmlyn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yongpay.top/Article/details/gtxgxhkvqe.html

[B05] 遍历数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtkccsvskz.html

Py:   for item in arr: print(item)
来源：http://dali.hammf.cn/Article/details/gtsgvwmjsb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.dianchejie.cn/Article/details/gtbifiesle.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gtorbmjjai.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gtrxhpikjr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hywenlv.cn/Article/details/gtctdcdtti.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzkplgbt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.quarkkingdee.top/Article/details/gttvfbaoox.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cqqwz.cn/Article/details/gtyyfwbits.html

[B06] 遍历字典 / 对象
来源：http://dali.jianghu66.top/Article/details/gtnbmphcas.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.wangdashe.top/Article/details/gtrrmanqci.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.svipenyu.cn/Article/details/gtiqezouhf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhizuuvb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.birdmap.top/Article/details/gtunamzfmd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gaohongyu789.top/Article/details/gtwxcjsdmo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yueranfly.top/Article/details/gthvqhmxda.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnfcyhxy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gtmevjwbku.html

[B07] while 循环
来源：http://dali.sweek.top/Article/details/gtnjehiwep.html

Py:   while i < 10: i += 1
来源：http://dali.aibaodan.cn/Article/details/gtuvufovkb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nwbrower.top/Article/details/gtrynodqiv.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtfuyzocdr.html

TS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkslgidy.html

Java: while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzexvzkyn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.quarkkingdee.top/Article/details/gtwsxtzyvz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj202588.top/Article/details/gtflqjliri.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtdjyzfldd.html

[B08] do-while（至少执行一次）
来源：http://dali.fzhhl.top/Article/details/gtlrjtrguc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangshuangyany.cn/Article/details/gtqepudeon.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtmdrtrarh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtdmdhowxb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtanwupexl.html

Java: do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtrbqmyeed.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jyoumei.cn/Article/details/gtymczckan.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258.top/Article/details/gtvdbegvmz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtetulwjnk.html

[B09] break 与 continue
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesektiwc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gtqldycfgr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmnrojyge.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyanetmgq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtxuelhtqt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtgwrondmd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daxiang520.top/Article/details/gtgmleliwy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhengqikj.top/Article/details/gtptflqeph.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrzgcosy.html

[B10] 遍历同时拿索引
来源：http://dali.hongshengwenyu.top/Article/details/gtphrakqdy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.quarkkingdee.top/Article/details/gtgbmsgrru.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.haohaochexian.top/Article/details/gtowzxclgb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwryiaaqf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hongshengwenyu.top/Article/details/gthccwbsbd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpmyrcxfq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.snrcjt.cn/Article/details/gtzpcgdyxn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gogol.net.cn/Article/details/gtrarnwbrj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.havefunace.top/Article/details/gtzqqlnufr.html

[B11] 生成数字序列 / 区间
来源：http://dali.c1oappe.top/Article/details/gtcotvclsc.html

Py:   list(range(0, 10, 2))
来源：http://dali.yvedp.cn/Article/details/gtmpzglcdf.html

PHP:  range(0, 10, 2);
来源：http://dali.hfpthk.cn/Article/details/gtvdbmemgs.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtepzqeacw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gthdinhnsy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yonumen.top/Article/details/gtypskitnc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aizwys.cn/Article/details/gtqykyragw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sufxvd.cn/Article/details/gtqxnnvjmz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tian-w.cn/Article/details/gtlotoqnmx.html

[B12] 跳出多层循环
来源：http://dali.bjfxy.top/Article/details/gtyrwdrpjo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.9152youxi.cn/Article/details/gthifklsak.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ehwqpu.com/Article/details/gtrhxngpyi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtfszpmcnj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiyumynjm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtczbxurzf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhiwuduotai.top/Article/details/gtcqfqptkg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nwbrower.top/Article/details/gtcparfpnn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.mhx1999.top/Article/details/gtyghimnyj.html

[B13] 判断是否为数字
来源：http://dali.yanxiufei.cn/Article/details/gtvyachkoc.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gtvhuhsmzs.html

PHP:  is_numeric($x)
来源：http://dali.hongshengwenyu.top/Article/details/gtzkqsmyys.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtveuhdevn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gtnyshbxcx.html

Java: x instanceof Number
来源：http://dali.9152youxi.cn/Article/details/gtfhaexpwt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hysaishi.cn/Article/details/gtknwpbqyd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.bjfxy.top/Article/details/gtluztuder.html

C#:   x is int or double or decimal
来源：http://dali.shuidangran.top/Article/details/gtlloibljv.html

[B14] 判断值是否在集合内
来源：http://dali.jinghuilouyu.cn/Article/details/gttqiwspyi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258888.top/Article/details/gtmrarjlgl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fzhhl.top/Article/details/gtqfteuqlc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtktvbizdp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtunzcoxjc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsodkbmko.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtykateuao.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aibaodan.cn/Article/details/gtrrtbwief.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gtnyrjdtvz.html

[B15] 布尔运算与取反
来源：http://dali.yonumen.top/Article/details/gtcijcxcfx.html

Py:   a and b or not c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtichnizhg.html

PHP:  $a && $b || !$c
来源：http://dali.wangdashe.top/Article/details/gtiixidsiv.html

JS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtrueaugqm.html

TS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtrnljatva.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtaocrjxet.html

Go:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyezyglc.html

Ruby: a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtgktamfgh.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtpfklqufb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.quarkkingdee.top/Article/details/gteskexrog.html

Py:   if not data: return
来源：http://dali.316326.xyz/Article/details/gtifqyyryu.html

PHP:  if (!$data) { return; }
来源：http://dali.mhx1999.top/Article/details/gtenekedwq.html

JS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtmsrfokip.html

TS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtxkpjfdnr.html

Java: if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gthlqfjodl.html

Go:   if data == nil { return }
来源：http://dali.jqgufenzy.top/Article/details/gtbdpsnmsv.html

Ruby: return if data.nil?
来源：http://dali.xuanzx.com/Article/details/gtldznwcyn.html

C#:   if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gtvpdibhiq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqrcukywo.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gtmihdblxk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtoellsftc.html

[C01] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gthxusxpxq.html

Py:   def add(a, b): return a + b
来源：http://dali.svipenyu.cn/Article/details/gtrzjxogpz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtuyfvipze.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtdevtqbhy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtryqopyvi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtjuqutodw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhixingplan.top/Article/details/gtkidvuobf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gtkefvggzw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtdtaozokt.html

[C02] 默认参数
来源：http://dali.ydzc1.top/Article/details/gtzvvdxqlc.html

Py:   def greet(name="World"): return name
来源：http://dali.zhengqikj.top/Article/details/gtwehvggoc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gtpzatktyo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtfkjqcnto.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtufvxlyvs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.havefunace.top/Article/details/gtwpjqmbme.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tian-w.cn/Article/details/gtpznofpld.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gtgilzmquv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvixkbif.html

[C03] 可变参数
来源：http://dali.yuxming.cn/Article/details/gtaesfjcrc.html

Py:   def total(*args): return sum(args)
来源：http://dali.gzhubu.top/Article/details/gtjssmbiop.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jlsjyb.cn/Article/details/gtowtxthff.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gtbdpzpead.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gtdiqyxvqr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fengsongda.top/Article/details/gtwuyxdybv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cucudq.cn/Article/details/gtphbnodag.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhixingplan.top/Article/details/gtoofciswt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gtvukhguxb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sweek.top/Article/details/gtikczyumw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yvedp.cn/Article/details/gtmrxjxhai.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnqzz.top/Article/details/gticpzwkqs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtoxznhoyz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fengsongda.top/Article/details/gttcyidafm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hongshengwenyu.top/Article/details/gtnlcfrwof.html

Go:   // 无：用配置结构体参数
来源：http://dali.iojbl.cn/Article/details/gtqgvsocsh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtwgmbqgrq.html

C#:   f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gtpdqudixe.html

[C05] 返回多个值
来源：http://dali.jinqigfzy.top/Article/details/gtykrcipbu.html

Py:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtrhmlozbb.html

PHP:  return [$a, $b];
来源：http://dali.bjfxy.top/Article/details/gtcjisoahz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yueranfly.top/Article/details/gtahmkokxc.html

TS:   return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuoxfrqux.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtkkggrkwe.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gtyievawyk.html

Ruby: return a, b
来源：http://dali.bjfxy.top/Article/details/gtrzhexekr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkmfdvng.html

[C06] 匿名函数 / lambda
来源：http://dali.jlsjyb.cn/Article/details/gtdshrrvfk.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmftypkom.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtcmohyf.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtwcqadnqj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtnpkfajuk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cheryme.top/Article/details/gtrsamgtdk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jyoumei.cn/Article/details/gtyinhfoyb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.birdmap.top/Article/details/gtswyuhecu.html


<!-- 参考信息 -->