代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.pycfn.com/Article/details/gtudfmfptd.html

C#:   var value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gtmtahiqca.html

[A16] 真假值判断规则
来源：http://dali.zhengqikj.top/Article/details/gtsjeletlu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinqigfzy.top/Article/details/gtavhqxuls.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yj20258888.top/Article/details/gtpxyueytj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shzxlz.cn/Article/details/gthapkactd.html

TS:   if (!x) {}
来源：http://dali.yuanzhike.top/Article/details/gthvghldvc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yuxming.cn/Article/details/gtkiuohldk.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalkscwwn.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ehwqpu.com/Article/details/gtxlnzfedm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ydzc1.top/Article/details/gtrgwwcggs.html

[A17] 位运算
来源：http://dali.iojbl.cn/Article/details/gtexurblhe.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtlixuzywd.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtlqbvaxmj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtkhbuea.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtlhlvwjxa.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtfhhktdfa.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtnywlqess.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gtrhtefyrj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gtgnhzqjku.html

[A18] 字符与 ASCII 码互转
来源：http://dali.316326.xyz/Article/details/gthjgsxbni.html

Py:   ord("A"); chr(65)
来源：http://dali.yangfankeji.com/Article/details/gtsqpkelci.html

PHP:  ord("A"); chr(65)
来源：http://dali.jiagoushi.top/Article/details/gtyckhhztu.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dianchejie.cn/Article/details/gtgmsxrcmv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ybcxt.top/Article/details/gthdqscjpf.html

Java: (int) 'A'; (char) 65
来源：http://dali.aizwys.cn/Article/details/gtfnjwulsg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.cdnleiting.top/Article/details/gtfjjcgbkr.html

Ruby: "A".ord; 65.chr
来源：http://dali.sweek.top/Article/details/gtbakqllbt.html

C#:   (int)'A'; (char)65
来源：http://dali.shangyingyoupin.top/Article/details/gtkoahdjkh.html

[A19] 交换两个变量
来源：http://dali.guannengcc.top/Article/details/gtaiwkjhun.html

Py:   a, b = b, a
来源：http://dali.jqgufenzy.top/Article/details/gtqbwlajxa.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsbbhadh.html

JS:   [a, b] = [b, a];
来源：http://dali.feifeiyinyue.top/Article/details/gtpkobszyl.html

TS:   [a, b] = [b, a];
来源：http://dali.zycfv.cn/Article/details/gtnapeccne.html

Java: int t = a; a = b; b = t;
来源：http://dali.yj20258888.top/Article/details/gtgdkmuxcj.html

Go:   a, b = b, a
来源：http://dali.shuidangran.top/Article/details/gtsgqzmfwn.html

Ruby: a, b = b, a
来源：http://dali.daria6918.cn/Article/details/gtwiyiweix.html

C#:   (a, b) = (b, a);
来源：http://dali.bjfxy.top/Article/details/gteeinoije.html

[A20] 读取标准输入
来源：http://dali.yuanzhike.top/Article/details/gtdnkofltq.html

Py:   name = input("请输入：")
来源：http://dali.cashguo.top/Article/details/gtpcmkhavk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.iojbl.cn/Article/details/gtdaktykim.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhongyouzk.top/Article/details/gtvlqczymv.html

TS:   // Node.js：readline 模块
来源：http://dali.jlsjyb.cn/Article/details/gtyaiaqiof.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.iojbl.cn/Article/details/gtqjlzadzp.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.haohaochexian.top/Article/details/gtrulaliku.html

Ruby: gets.chomp
来源：http://dali.gzhubu.top/Article/details/gtniplbhxh.html

C#:   Console.ReadLine();
来源：http://dali.yongpay.top/Article/details/gtlfgpcolp.html

[A21] 保留指定小数位输出
来源：http://dali.hfpthk.cn/Article/details/gtykebvmxi.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jqgufenzy.top/Article/details/gtwelpcwju.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gtsgvndhxb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.aizwys.cn/Article/details/gttbvhhqwg.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfwptatd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gtpnixihfu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gtwbvujzzv.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gtuqeofjcu.html

C#:   3.14159.ToString("F2")
来源：http://dali.yonumen.top/Article/details/gtsyfeduly.html

[A22] 获取字符串长度
来源：http://dali.sweek.top/Article/details/gtvocxgpxd.html

Py:   len(s)
来源：http://dali.haohaochexian.top/Article/details/gtjagcdyjq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pengpengdd.cyou/Article/details/gtwbqchgms.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.smart0.xyz/Article/details/gtfxifekhg.html

TS:   s.length
来源：http://dali.yonumen.top/Article/details/gtfuvegvjl.html

Java: s.length()
来源：http://dali.andypj.xyz/Article/details/gtdhrwrbgs.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xylfe.cn/Article/details/gtjiyziyii.html

Ruby: s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtftnofrgp.html

C#:   s.Length
来源：http://dali.sxryk.cn/Article/details/gtfuhlsiiz.html

[A23] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtloexdsyi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cqqwz.cn/Article/details/gtkuwdqrtu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xinyue.icu/Article/details/gtaljcedkg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.guannengcc.top/Article/details/gtdsuplmai.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gtnfwsfitv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gtvjaghwaj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xylfe.cn/Article/details/gtgagrekav.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tian-w.cn/Article/details/gtblaljryc.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.chenjidiqi.icu/Article/details/gtqtqatwfp.html

[A24] 去除首尾空白
来源：http://dali.yj20258.top/Article/details/gtvlwjnwwi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqttktkb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zdqjudy.top/Article/details/gtcrzdewbl.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnqzz.top/Article/details/gtlpbkqtqt.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gtrevuqrri.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.mhx1999.top/Article/details/gtobdigobs.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj20258.top/Article/details/gtzijjbegy.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jianghu66.top/Article/details/gtgodxfrqn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj202588.top/Article/details/gtlhyxxxzt.html

[A25] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtonsrzazx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xylfe.cn/Article/details/gtgbigxvyc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtncrpebwy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cdnleiting.top/Article/details/gtltzbaznq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtblqpwewg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtipuwyucj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hywenlv.cn/Article/details/gtldzxpqww.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.quarkkingdee.top/Article/details/gtqjyshysa.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gtivvwcaai.html

[A26] 类型转换总览
来源：http://dali.gaohongyu789.top/Article/details/gthfcmbwrk.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hongshengwenyu.top/Article/details/gtacimiqmp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ppjwa.cn/Article/details/gtyglbwpos.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hysaishi.cn/Article/details/gtawualhxa.html

TS:   Number() String() Boolean() x as number
来源：http://dali.quarkkingdee.top/Article/details/gtimimgyuy.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.quarkkingdee.top/Article/details/gtccilmjex.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.kuanghao11.cn/Article/details/gtluubdeqk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhixingplan.top/Article/details/gtrcmbkklg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoeedvlhk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtmsarrslo.html

B. 流程控制
来源：http://dali.yj20258.top/Article/details/gtvrnaygob.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtnjvhgpyg.html

[B01] 条件判断 if / else
来源：http://dali.daria6918.cn/Article/details/gtnjqedmzl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.fzhhl.top/Article/details/gtnjifbhyk.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shuidangran.top/Article/details/gtwcuttvok.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gthpxvabwv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtwjsikkrw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gtytjmuczr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sxryk.cn/Article/details/gtswlahirj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zycfv.cn/Article/details/gtxvlvzjwa.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gttfttxkeo.html

[B02] 多分支 else if / elif
来源：http://dali.chenzaomai.com/Article/details/gtlmpjwmer.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhixingplan.top/Article/details/gtazdwqjuw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cdnleiting.top/Article/details/gtujjuxaau.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gtqspswxnw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtfpwipwxt.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtmxybjpod.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cashguo.top/Article/details/gtychhzbzo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jyoumei.cn/Article/details/gtfqxrrvch.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gtvjofkils.html

[B03] switch / match / case
来源：http://dali.ybcxt.top/Article/details/gtpatqnqil.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ehwqpu.com/Article/details/gtlrkzmbhr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtabybbyfe.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhsduwpb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtgaayfexz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtonitcqlv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.meibo888.top/Article/details/gtivhdrnvf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gotoacloud.top/Article/details/gthskvetgj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.iojbl.cn/Article/details/gttrybxfsj.html

[B04] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvbpqjox.html

Py:   for i in range(10): print(i)
来源：http://dali.yuanzhike.top/Article/details/gtxtqgtgfa.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shuidangran.top/Article/details/gtgqtvfzsc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtpixtxjjy.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigufen.top/Article/details/gtrziapasl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hammf.cn/Article/details/gtrburmbud.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hywenlv.cn/Article/details/gtfdyycghs.html

Ruby: 10.times { |i| puts i }
来源：http://dali.svipenyu.cn/Article/details/gtbvgwqfbm.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.0kj1m.cn/Article/details/gtojoffrty.html

[B05] 遍历数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gtdhuidqap.html

Py:   for item in arr: print(item)
来源：http://dali.yj20258888.top/Article/details/gtnqfrwxgz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.andypj.xyz/Article/details/gtsdftgfes.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gtsuynrkvc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuxming.cn/Article/details/gttsckkyae.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.pycfn.com/Article/details/gtvbqkfpfv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sweek.top/Article/details/gtlhxqmegw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zycfv.cn/Article/details/gtqvexwshg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtiuerxcfv.html

[B06] 遍历字典 / 对象
来源：http://dali.zhengqikj.top/Article/details/gtxrmiavyg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.andypj.xyz/Article/details/gtandaawxc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgufenzy.top/Article/details/gtvtykvdad.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ehwqpu.com/Article/details/gtltknlauo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gtnxsuklzn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhongyouzk.top/Article/details/gtbflmtjfv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnqzz.top/Article/details/gtfbmipxki.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.9152youxi.cn/Article/details/gtpypqvyfc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gzhubu.top/Article/details/gtwitjrihe.html

[B07] while 循环
来源：http://dali.jlsjyb.cn/Article/details/gthagjzppf.html

Py:   while i < 10: i += 1
来源：http://dali.tanke756.top/Article/details/gtuscajsmg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gogol.net.cn/Article/details/gtngwjmxwr.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtvghekcko.html

TS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtkvjtxane.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtqoomwpqh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgejwlbsd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zycfv.cn/Article/details/gtizqlmzbg.html

C#:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtucxnehfm.html

[B08] do-while（至少执行一次）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlvovvei.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hongshengwenyu.top/Article/details/gtincwivve.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtborlckkq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gtuuysidts.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtvzihlvmq.html

Java: do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtvoyxgcew.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhengqikj.top/Article/details/gtddscyijc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xylfe.cn/Article/details/gtnzzoatpy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtbvjjrigx.html

[B09] break 与 continue
来源：http://dali.birdmap.top/Article/details/gtceqcxhgp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xinyue.icu/Article/details/gtrefgfosi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtsabtgjyg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtrwbzhfvm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gttaqrkpaq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gthbyuzmwi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcijjhvi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ybcxt.top/Article/details/gtwhemhmug.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtcvgegnqn.html

[B10] 遍历同时拿索引
来源：http://dali.mhx1999.top/Article/details/gtadrocajk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.feifeiyinyue.top/Article/details/gtpcnufsnu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gtjzjtqlvz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytgjeogq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xylfe.cn/Article/details/gtqdgkgopo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenjidiqi.icu/Article/details/gtsnlquicn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fengsongda.top/Article/details/gtgltvhnvz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hongshengwenyu.top/Article/details/gtuujmxpqg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtgcvymbmj.html

[B11] 生成数字序列 / 区间
来源：http://dali.shzxlz.cn/Article/details/gtauivyqxn.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuanzhike.top/Article/details/gtnizkpifd.html

PHP:  range(0, 10, 2);
来源：http://dali.smart0.xyz/Article/details/gtxxcwbhfi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gtuuofvzlk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtheclguna.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacakzhpo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ivvv.top/Article/details/gtiqfnhkvl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dashuyun.cn/Article/details/gtnkmopbwu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xylfe.cn/Article/details/gtpwesxaaq.html

[B12] 跳出多层循环
来源：http://dali.dianchejie.cn/Article/details/gtzeidkcva.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258.top/Article/details/gtmgzbdjlq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jiagoushi.top/Article/details/gtdzfcoxhg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtukmgbrxc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtexhetgol.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtnopnjher.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hfpthk.cn/Article/details/gtsxmazpua.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gzhubu.top/Article/details/gtgxdqrnbk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yongpay.top/Article/details/gtymkeaffe.html

[B13] 判断是否为数字
来源：http://dali.jiagoushi.top/Article/details/gtfjsdhsrb.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutezlmgf.html

PHP:  is_numeric($x)
来源：http://dali.cqqwz.cn/Article/details/gtdkenziio.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtcqealhkk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtukvaauyv.html

Java: x instanceof Number
来源：http://dali.cqqwz.cn/Article/details/gtfpvbuwba.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.birdmap.top/Article/details/gtgxlmqvwn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pycfn.com/Article/details/gtjctgvoou.html

C#:   x is int or double or decimal
来源：http://dali.jqgufenzy.top/Article/details/gthbjrcoax.html

[B14] 判断值是否在集合内
来源：http://dali.mhx1999.top/Article/details/gtbgkqbegf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gtnzmgjzfr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbjcyfgd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gtxkidauvm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtbrjqpgto.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gteyeifilt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuhhmmfi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtdwnjyloo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtdlfqbntq.html

[B15] 布尔运算与取反
来源：http://dali.316326.xyz/Article/details/gtyejtqgsf.html

Py:   a and b or not c
来源：http://dali.aibaodan.cn/Article/details/gtuwwjnmli.html

PHP:  $a && $b || !$c
来源：http://dali.xinyue.icu/Article/details/gtikxznfli.html

JS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gttvrmldsb.html

TS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtfwkqzlpd.html

Java: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtdplmmroc.html

Go:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtyhlmplsg.html

Ruby: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtgmdiinhk.html

C#:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtcycqdlrw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.bjfxy.top/Article/details/gtsxmytzco.html

Py:   if not data: return
来源：http://dali.fzhhl.top/Article/details/gtjlyhdtlg.html

PHP:  if (!$data) { return; }
来源：http://dali.zycfv.cn/Article/details/gtthlvseqv.html

JS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtqkzpwkjz.html

TS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtnyrlhpmr.html

Java: if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtjxeebqpx.html

Go:   if data == nil { return }
来源：http://dali.yanxiufei.cn/Article/details/gtgtvibgfv.html

Ruby: return if data.nil?
来源：http://dali.zhiwuduotai.top/Article/details/gtnojnvcrh.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gtpsqbemml.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthpijzijt.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtrkxzqpep.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtxzndftrs.html

[C01] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gttfsmuucg.html

Py:   def add(a, b): return a + b
来源：http://dali.havefunace.top/Article/details/gtkopuwpei.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrixzxao.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtfyqrqbwd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixsybxsa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gticcjjvcn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yonumen.top/Article/details/gtmxgbwcpu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ydzc1.top/Article/details/gtstcyvffl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtzukzfdoo.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtfqpdsuhy.html

Py:   def greet(name="World"): return name
来源：http://dali.redwolf501.top/Article/details/gtujgutcmf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenzaomai.com/Article/details/gtrcsezimn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gteblcwgve.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gtzahrcwae.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuanzx.com/Article/details/gtjwwbgdkn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yongpay.top/Article/details/gttzbpfbyz.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gthnsiklvr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cheryme.top/Article/details/gtyzkfietg.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gtkxhfssxs.html

Py:   def total(*args): return sum(args)
来源：http://dali.c1oappe.top/Article/details/gtkbnexfud.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmsouvpq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtjofmhebw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtlsstegfv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gzhubu.top/Article/details/gtqdauyopj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuxming.cn/Article/details/gtmmciqhsg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gaohongyu789.top/Article/details/gtesxggina.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuanzhike.top/Article/details/gtuujowztg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.havefunace.top/Article/details/gtrufnhnzc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenzaomai.com/Article/details/gtakblwgww.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gtdiwekwne.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gtdzfhsxnk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gtogzxeiwk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sxryk.cn/Article/details/gttpjybgji.html

Go:   // 无：用配置结构体参数
来源：http://dali.cucudq.cn/Article/details/gtjbsiiypm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtabkkrrln.html

C#:   f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtvkssuvlp.html

[C05] 返回多个值
来源：http://dali.yuxming.cn/Article/details/gtespeagoe.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtskxjrghw.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gtzxgoqwxh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gtwgjjrhtq.html

TS:   return { a, b };
来源：http://dali.yvedp.cn/Article/details/gtoqlenwek.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhiwuduotai.top/Article/details/gtwvtywtwb.html

Go:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtrentoecr.html

Ruby: return a, b
来源：http://dali.svipenyu.cn/Article/details/gtcokdyqxy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaflkayrv.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gtugdpdufe.html

Py:   square = lambda x: x * x
来源：http://dali.cheryme.top/Article/details/gtbacqbfye.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hywenlv.cn/Article/details/gtszqbpnlh.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtuuuatdvx.html


<!-- 参考信息 -->