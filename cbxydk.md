代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.dashuyun.cn/Article/details/gteihlcqiy.html

TS:   const value = data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gteatfasjo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zdqjudy.top/Article/details/gtggxdhpce.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.316326.xyz/Article/details/gtxkggzlou.html

Ruby: value = data || "默认值"
来源：http://dali.chenlongwang.top/Article/details/gtuzzndqfc.html

C#:   var value = data ?? "默认值";
来源：http://dali.xuetiantiany.cn/Article/details/gtibaujngn.html

[A16] 真假值判断规则
来源：http://dali.hywenlv.cn/Article/details/gtqrgeercc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.guowangkeji.top/Article/details/gtvgsgcuqg.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shuidangran.top/Article/details/gttrnrsweq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvfajwch.html

TS:   if (!x) {}
来源：http://dali.jianghu66.top/Article/details/gtmxmkobok.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtluylfdyy.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.kuanghao11.cn/Article/details/gtvrjldvzr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yangfankeji.com/Article/details/gtdszzmnhg.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.c1oappe.top/Article/details/gtpeojhpgh.html

[A17] 位运算
来源：http://dali.tanke756.top/Article/details/gtmbixxydb.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtfakhjtlh.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtadclmgva.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtrroqchny.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gtdtdwwqyc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gtymsgorna.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtjhzeakxn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtepprjnrd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtgjjfeidm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.gzhubu.top/Article/details/gtnjhjwhun.html

Py:   ord("A"); chr(65)
来源：http://dali.birdmap.top/Article/details/gthtryssfi.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinqigfzy.top/Article/details/gtdolklcdt.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pycfn.com/Article/details/gtmvitdjqr.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.daxiang520.top/Article/details/gtjtdlxubx.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhiwuduotai.top/Article/details/gtqkbgmaqt.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.0kj1m.cn/Article/details/gtsbjypfsy.html

Ruby: "A".ord; 65.chr
来源：http://dali.yj20258.top/Article/details/gttkdexkyy.html

C#:   (int)'A'; (char)65
来源：http://dali.sxryk.cn/Article/details/gtjzjqdmre.html

[A19] 交换两个变量
来源：http://dali.smart0.xyz/Article/details/gtyicezdcr.html

Py:   a, b = b, a
来源：http://dali.wangshuangyany.cn/Article/details/gtojiqnrjo.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.dianchejie.cn/Article/details/gtlmyfwzzq.html

JS:   [a, b] = [b, a];
来源：http://dali.hywenlv.cn/Article/details/gtddbjwlqg.html

TS:   [a, b] = [b, a];
来源：http://dali.pycfn.com/Article/details/gthdqqmitz.html

Java: int t = a; a = b; b = t;
来源：http://dali.iojbl.cn/Article/details/gtxfyglnfs.html

Go:   a, b = b, a
来源：http://dali.wangdashe.top/Article/details/gtuwugmfkv.html

Ruby: a, b = b, a
来源：http://dali.hnxiangtu.top/Article/details/gtuxkcredz.html

C#:   (a, b) = (b, a);
来源：http://dali.jiagoushi.top/Article/details/gtfuobzkft.html

[A20] 读取标准输入
来源：http://dali.jqgufenzy.top/Article/details/gtwluzbdmz.html

Py:   name = input("请输入：")
来源：http://dali.chenlongwang.top/Article/details/gtifdsqkhe.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.dianchejie.cn/Article/details/gtnjjrofvk.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zycfv.cn/Article/details/gtrjcvhpcy.html

TS:   // Node.js：readline 模块
来源：http://dali.guannengcc.top/Article/details/gtpqakfxcp.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinghuilouyu.cn/Article/details/gtabxmjhvd.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jianghu66.top/Article/details/gtwmcbhbuc.html

Ruby: gets.chomp
来源：http://dali.yanxiufei.cn/Article/details/gtyseosynh.html

C#:   Console.ReadLine();
来源：http://dali.zhiwuduotai.top/Article/details/gtwdsshtpd.html

[A21] 保留指定小数位输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqduquytf.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhiwuduotai.top/Article/details/gthgvgtyuf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gtujmqhvzr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gtcfimgjyw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtgflgewqd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtwovaheny.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtztjisaky.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gtgnwnxybk.html

C#:   3.14159.ToString("F2")
来源：http://dali.nwbrower.top/Article/details/gtkoqwnxmq.html

[A22] 获取字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtuwasfxkg.html

Py:   len(s)
来源：http://dali.ppjwa.cn/Article/details/gtstaushct.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pycfn.com/Article/details/gtvllttrqx.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ehwqpu.com/Article/details/gtjuygqzto.html

TS:   s.length
来源：http://dali.tianlin.xyz/Article/details/gtgjtjcfxb.html

Java: s.length()
来源：http://dali.ydzc1.top/Article/details/gtlanefxfb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtkbqyjjay.html

Ruby: s.length
来源：http://dali.daria6918.cn/Article/details/gtzrsizqte.html

C#:   s.Length
来源：http://dali.yuanzhike.top/Article/details/gtzmndeodb.html

[A23] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gttrdzsgbk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sweek.top/Article/details/gtrcujkddk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.redwolf501.top/Article/details/gtnyparqrd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gtahljkagh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zycfv.cn/Article/details/gtsljbzvwe.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gtpkempfyr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gaohongyu789.top/Article/details/gtzndziunj.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gtadyluoca.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.snrcjt.cn/Article/details/gttnkmnhvv.html

[A24] 去除首尾空白
来源：http://dali.tianlin.xyz/Article/details/gthgtnrosk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cheryme.top/Article/details/gtzfdzxtnb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyohvmhcw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gtxiwzggcc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenzaomai.com/Article/details/gtxjylfnpi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.mhx1999.top/Article/details/gtcuvwtdwv.html

Go:   strings.TrimSpace(s)
来源：http://dali.gogol.net.cn/Article/details/gtoadzzvii.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jqgfzy.top/Article/details/gtcnmgvmyv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.c1oappe.top/Article/details/gtamwvhzfj.html

[A25] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbtizwrw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tian-w.cn/Article/details/gtihpwrzwg.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hnqzz.top/Article/details/gtcwzzqjvj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fengsongda.top/Article/details/gtvhqzwtqw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258.top/Article/details/gtxifocytj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258888.top/Article/details/gtjtbdgvkm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jiagoushi.top/Article/details/gtpnvezixf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hnxiangtu.top/Article/details/gtvcwlwlok.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cqqwz.cn/Article/details/gtmdnhwfgp.html

[A26] 类型转换总览
来源：http://dali.ehwqpu.com/Article/details/gtnzpxnxtv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daria6918.cn/Article/details/gteldimhwy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jyoumei.cn/Article/details/gtgqaetnoi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.redwolf501.top/Article/details/gtfqinfyfy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.meibo888.top/Article/details/gtvrkzofty.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jianghu66.top/Article/details/gtrxmmgpfu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohhmjixe.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.vqdsnc.cn/Article/details/gtthkdylkl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cdnleiting.top/Article/details/gtnldfhtxf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtuzkmwpxs.html

B. 流程控制
来源：http://dali.hnxiangtu.top/Article/details/gtyheghyip.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjfmhdkey.html

[B01] 条件判断 if / else
来源：http://dali.pycfn.com/Article/details/gtsgtguhex.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.9152youxi.cn/Article/details/gtaokygtoc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jyoumei.cn/Article/details/gtjzijvlqt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtgzvsqwiy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtuqiatqfv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gtzqblonif.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.redwolf501.top/Article/details/gtbnzrtdcc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shangyingyoupin.top/Article/details/gtlyzfetck.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtocwovkkc.html

[B02] 多分支 else if / elif
来源：http://dali.hysaishi.cn/Article/details/gtmgajakes.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tianlin.xyz/Article/details/gtpmlbirwg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.quarkkingdee.top/Article/details/gtbfhmvvzx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtawwonwak.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtrhszfvau.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gtcyjcnpoz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cdnleiting.top/Article/details/gtevrirtgr.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.daria6918.cn/Article/details/gtqaizenrz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gttalhmlfp.html

[B03] switch / match / case
来源：http://dali.chenzaomai.com/Article/details/gtsrdbwixt.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.meibo888.top/Article/details/gtkkndkkxm.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtkhsyyvjz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtneppadtv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtzoofrtta.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtwjjbwgjk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guannengcc.top/Article/details/gtcanrmtlk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nwbrower.top/Article/details/gtfzifmsel.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.aizwys.cn/Article/details/gtamfptxhg.html

[B04] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gtwauadeyv.html

Py:   for i in range(10): print(i)
来源：http://dali.shzxlz.cn/Article/details/gtgjabwxrq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj202588.top/Article/details/gtjdontolz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqeehnclh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shzxlz.cn/Article/details/gtpacgecfc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cdnleiting.top/Article/details/gtctwrlxre.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hysaishi.cn/Article/details/gtjiabbrjh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yonumen.top/Article/details/gtczxzgagk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nwbrower.top/Article/details/gtgdegbtgb.html

[B05] 遍历数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtubyrnzvr.html

Py:   for item in arr: print(item)
来源：http://dali.hysaishi.cn/Article/details/gtmwibdhxr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhiwuduotai.top/Article/details/gtndexppji.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtjexrswpk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gtbdernqrg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zycfv.cn/Article/details/gtunwxedcp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrifgtcpi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hongshengwenyu.top/Article/details/gtadimoyeo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfcaqqeah.html

[B06] 遍历字典 / 对象
来源：http://dali.birdmap.top/Article/details/gttzlduukf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hfpthk.cn/Article/details/gtdxvbkgpl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xinyue.icu/Article/details/gtiswhtubn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenzaomai.com/Article/details/gtsbdnmoyu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyjtldeu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cheryme.top/Article/details/gtmgaznrlm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hywenlv.cn/Article/details/gtsegigpul.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.havefunace.top/Article/details/gtswzbzkoe.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenlongwang.top/Article/details/gttdynijmq.html

[B07] while 循环
来源：http://dali.cdnleiting.top/Article/details/gtmfekqboh.html

Py:   while i < 10: i += 1
来源：http://dali.yonumen.top/Article/details/gtsxskikdd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zdqjudy.top/Article/details/gtyfyrgdux.html

JS:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gtnodizyhp.html

TS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpeujahme.html

Java: while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtyfoavekj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujmdwdzd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hfpthk.cn/Article/details/gtryswttpi.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtvnwxlizi.html

[B08] do-while（至少执行一次）
来源：http://dali.shzxlz.cn/Article/details/gtqlvhplgr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.kuanghao11.cn/Article/details/gtorjniwzx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.c1oappe.top/Article/details/gtzwlqjgke.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtzhmyrmvf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtarnlqyer.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtoccupxev.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gtyttpqtja.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gtckaskfes.html

C#:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gteawkkhgb.html

[B09] break 与 continue
来源：http://dali.wangdashe.top/Article/details/gtwtxmvavb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gtyiyujlkr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtjapuuwef.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtnrrtcyzv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtksqrwvje.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtxutlcaxs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gtztuaytjc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.havefunace.top/Article/details/gtlssjcxin.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtuuzebnqi.html

[B10] 遍历同时拿索引
来源：http://dali.jqgufenzy.top/Article/details/gtrxegbhbg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.quarkkingdee.top/Article/details/gtudofrrou.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258888.top/Article/details/gtifuabsrw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gtkvifbtdp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gtejunstcy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiaqgrkzx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tianlin.xyz/Article/details/gtioarqths.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtebzguirp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shzxlz.cn/Article/details/gteqogxcim.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlprrumm.html

Py:   list(range(0, 10, 2))
来源：http://dali.guannengcc.top/Article/details/gtfbytsjay.html

PHP:  range(0, 10, 2);
来源：http://dali.yuxming.cn/Article/details/gtehfotwvw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvseautyh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gtjxadnjeb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigfzy.top/Article/details/gthdowzxpz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.316326.xyz/Article/details/gtegcgglfm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sxryk.cn/Article/details/gtlnnrtkis.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jlsjyb.cn/Article/details/gthouekufl.html

[B12] 跳出多层循环
来源：http://dali.zhoulong.xyz/Article/details/gtxbopgjvz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.316326.xyz/Article/details/gtclnkbwrp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ivvv.top/Article/details/gtpmzsqmps.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtrpwemjty.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtvmritxay.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtjfzmhgpd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxuanxn.top/Article/details/gtjfkbqgsu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuanzx.com/Article/details/gtijmmdcek.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ivvv.top/Article/details/gtvisbdjnp.html

[B13] 判断是否为数字
来源：http://dali.andypj.xyz/Article/details/gtfudewozd.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgfzy.top/Article/details/gtrobfymoo.html

PHP:  is_numeric($x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykdnnzwe.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gthdrytzhb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtuwhvnzfq.html

Java: x instanceof Number
来源：http://dali.jlsjyb.cn/Article/details/gtnaicltvh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pengpengdd.cyou/Article/details/gtypnvwdsf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gtqggnqupx.html

C#:   x is int or double or decimal
来源：http://dali.xinyue.icu/Article/details/gthuzmgoqj.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gtcluwcyyn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.c1oappe.top/Article/details/gtsotxdwew.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sxryk.cn/Article/details/gtvohvewnf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtnnhfblto.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtfnvsnrvl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtvnhkioed.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jlsjyb.cn/Article/details/gtbxwjifvh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gthqxopgnh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtdlsahmss.html

[B15] 布尔运算与取反
来源：http://dali.yangfankeji.com/Article/details/gtlyouhrqe.html

Py:   a and b or not c
来源：http://dali.sufxvd.cn/Article/details/gtokmieamh.html

PHP:  $a && $b || !$c
来源：http://dali.mhx1999.top/Article/details/gtzatmvrav.html

JS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gttqiiqgdt.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtyfbnsuhc.html

Java: a && b || !c
来源：http://dali.yj202588.top/Article/details/gtdjjeykww.html

Go:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtjumpdamv.html

Ruby: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtaizjnnqn.html

C#:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtzyaiogvg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yongpay.top/Article/details/gtkscbdqxp.html

Py:   if not data: return
来源：http://dali.shzxlz.cn/Article/details/gtzeybhxcg.html

PHP:  if (!$data) { return; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbheyqfnm.html

JS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtcbfjxarz.html

TS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gthzbfzaxj.html

Java: if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gthlreqcrh.html

Go:   if data == nil { return }
来源：http://dali.hnxiangtu.top/Article/details/gtmobzlnus.html

Ruby: return if data.nil?
来源：http://dali.yj202588.top/Article/details/gtklwhjija.html

C#:   if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gtdpunwcif.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gteytwmvsz.html

C. 函数与作用域
来源：http://dali.shzxlz.cn/Article/details/gtfyqbqyra.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtlglokjaj.html

[C01] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtcyhkeytt.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gthpsajgxz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtqugfrlfs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtyzfnzrje.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfjtamll.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkogvqgqm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ydzc1.top/Article/details/gtvxcefdwf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuanzhike.top/Article/details/gtomqwmzaa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtwceutldt.html

[C02] 默认参数
来源：http://dali.chenzaomai.com/Article/details/gtbaxnauil.html

Py:   def greet(name="World"): return name
来源：http://dali.yonumen.top/Article/details/gtpkbdcrxn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigfzy.top/Article/details/gtewicbndk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtandbcdtu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtiubmnbeo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gthaqodrbw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hysaishi.cn/Article/details/gtmonfgdxf.html

Ruby: def greet(name = "World") = name
来源：http://dali.kuanghao11.cn/Article/details/gtjzbbnxnd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aibaodan.cn/Article/details/gtfrevtutn.html

[C03] 可变参数
来源：http://dali.bjfxy.top/Article/details/gtscfydmgb.html

Py:   def total(*args): return sum(args)
来源：http://dali.tianlin.xyz/Article/details/gtcyrowvlk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gtlauprpyz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtsabgwzsv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gtodjcuvqk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.mhx1999.top/Article/details/gtobdewcus.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gtnsrrzbqh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gtjhgadjgg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuxming.cn/Article/details/gtcyomfwhd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gtoardttxk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlshfroed.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gtgqnsniyu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gtwjlgname.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgfzy.top/Article/details/gtjqvfvbqv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gtyuyyglmd.html

Go:   // 无：用配置结构体参数
来源：http://dali.hammf.cn/Article/details/gthabvrjaf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gttjyenuor.html

C#:   f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtypbxrxtu.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gtgatjvpkp.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gtcsdgdzvt.html

PHP:  return [$a, $b];
来源：http://dali.gzhubu.top/Article/details/gtnjbvbxtl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258888.top/Article/details/gtajbsarkw.html

TS:   return { a, b };
来源：http://dali.xziqi.cn/Article/details/gtzdjgztxy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gtlxbjyajz.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfblxxxss.html

Ruby: return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohdurdwg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zdqjudy.top/Article/details/gtqkahoeec.html


<!-- 参考信息 -->