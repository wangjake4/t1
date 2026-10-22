代发 wailian999

[A14] 注释写法
来源：http://dali.zhixingplan.top/Article/details/gtpwxfkrfy.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sufxvd.cn/Article/details/gttjazkvzv.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jqgufenzy.top/Article/details/gtwytvjbgm.html

JS:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gtaxhremei.html

TS:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gthoavynab.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxaprexq.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gtioudgmpt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.316326.xyz/Article/details/gtwgckngew.html

C#:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gtqorjtcku.html

[A15] 空值判断与默认值
来源：http://dali.mhx1999.top/Article/details/gtxvrqusku.html

Py:   value = data or "默认值"
来源：http://dali.zhiwuduotai.top/Article/details/gtqzzrijhw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtsotibgop.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyxdhbko.html

TS:   const value = data ?? "默认值";
来源：http://dali.yj20258.top/Article/details/gtnhccapsc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbofgnxta.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.0kj1m.cn/Article/details/gtixttkgmh.html

Ruby: value = data || "默认值"
来源：http://dali.yuxming.cn/Article/details/gtbatzmifw.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gtoplcpzwm.html

[A16] 真假值判断规则
来源：http://dali.jyoumei.cn/Article/details/gtajupduqz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cheryme.top/Article/details/gtbtfeknbw.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xylfe.cn/Article/details/gtacgflzcz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zdqjudy.top/Article/details/gtwcoiopio.html

TS:   if (!x) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtksawsk.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtujvzbvyi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yj20258888.top/Article/details/gtdavvcdls.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.dashuyun.cn/Article/details/gtqwcbwhru.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtengoayps.html

[A17] 位运算
来源：http://dali.chenzaomai.com/Article/details/gtqlcjkoix.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtirfketcu.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gtvlaggroj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtvyyqznyl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtdbibqvhq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtywsexqsq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtfnawavfi.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtaeurdttl.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtrszobhvr.html

[A18] 字符与 ASCII 码互转
来源：http://dali.chenjidiqi.icu/Article/details/gttvjzlztb.html

Py:   ord("A"); chr(65)
来源：http://dali.pycfn.com/Article/details/gtjmewfbnh.html

PHP:  ord("A"); chr(65)
来源：http://dali.shangyingyoupin.top/Article/details/gtpflsokyw.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nwbrower.top/Article/details/gtuzqbvcgv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xziqi.cn/Article/details/gtmwmwgrhz.html

Java: (int) 'A'; (char) 65
来源：http://dali.hnxiangtu.top/Article/details/gtrsbwidir.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.andypj.xyz/Article/details/gtvcmbvwdq.html

Ruby: "A".ord; 65.chr
来源：http://dali.xinyue.icu/Article/details/gtbazlteus.html

C#:   (int)'A'; (char)65
来源：http://dali.316326.xyz/Article/details/gtxdgaxojl.html

[A19] 交换两个变量
来源：http://dali.hnxiangtu.top/Article/details/gtwglbuovz.html

Py:   a, b = b, a
来源：http://dali.ybcxt.top/Article/details/gtwiaygqho.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gogol.net.cn/Article/details/gtatthyoaz.html

JS:   [a, b] = [b, a];
来源：http://dali.kuanghao11.cn/Article/details/gtrdwsmxww.html

TS:   [a, b] = [b, a];
来源：http://dali.tanke756.top/Article/details/gtqvjfzesd.html

Java: int t = a; a = b; b = t;
来源：http://dali.yangfankeji.com/Article/details/gtrdnddrzc.html

Go:   a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gtwnwvkica.html

Ruby: a, b = b, a
来源：http://dali.ydzc1.top/Article/details/gtphyvyqoi.html

C#:   (a, b) = (b, a);
来源：http://dali.yanxiufei.cn/Article/details/gttezdvfjf.html

[A20] 读取标准输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwkmkfxi.html

Py:   name = input("请输入：")
来源：http://dali.ybcxt.top/Article/details/gtbhipalfb.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.fengsongda.top/Article/details/gtwybczbiw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shanyushiyangtech.top/Article/details/gtefcnhggi.html

TS:   // Node.js：readline 模块
来源：http://dali.ehwqpu.com/Article/details/gtfmpfwpbw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gotoacloud.top/Article/details/gthhiggudu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.svipenyu.cn/Article/details/gtcmofwhqs.html

Ruby: gets.chomp
来源：http://dali.redwolf501.top/Article/details/gtgiolkpxj.html

C#:   Console.ReadLine();
来源：http://dali.sysykeji.top/Article/details/gtpgmxhykm.html

[A21] 保留指定小数位输出
来源：http://dali.daxiang520.top/Article/details/gtlulycjpo.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xylfe.cn/Article/details/gtipasesyx.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xinyue.icu/Article/details/gtdntwtcgv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtncekyigb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtiqmuigxb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtavykwjhd.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zdqjudy.top/Article/details/gtcducfibk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gtajcveulk.html

C#:   3.14159.ToString("F2")
来源：http://dali.shangyingyoupin.top/Article/details/gtghhlhjke.html

[A22] 获取字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtuopgozau.html

Py:   len(s)
来源：http://dali.hysaishi.cn/Article/details/gtghtbwbdy.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.dianchejie.cn/Article/details/gthxvurvzw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.wangdashe.top/Article/details/gtpaoaptck.html

TS:   s.length
来源：http://dali.smart0.xyz/Article/details/gtdzihqngg.html

Java: s.length()
来源：http://dali.zycfv.cn/Article/details/gttzebrzyp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cqqwz.cn/Article/details/gtwaaldovw.html

Ruby: s.length
来源：http://dali.daxiang520.top/Article/details/gtqlyqtpio.html

C#:   s.Length
来源：http://dali.xinyue.icu/Article/details/gtkuhumjly.html

[A23] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtwaltnuzz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yj20258.top/Article/details/gtdjoryhpu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.pycfn.com/Article/details/gtxuowttmd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gtqcwroysx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jiagoushi.top/Article/details/gtqjzxuzms.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sufxvd.cn/Article/details/gtfljohmcc.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cdnleiting.top/Article/details/gtwtbydiyc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyztgkfzl.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdrrkenu.html

[A24] 去除首尾空白
来源：http://dali.jinqigufen.top/Article/details/gtpapqqbhu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.aibaodan.cn/Article/details/gtgsuwsgly.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.aibaodan.cn/Article/details/gtsxxmojol.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.haohaochexian.top/Article/details/gtksvwvgug.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gtrarxpjrl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzaogcvr.html

Go:   strings.TrimSpace(s)
来源：http://dali.sufxvd.cn/Article/details/gtiribskbj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shangyingyoupin.top/Article/details/gtvlwqttkx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cheryme.top/Article/details/gtrycnilub.html

[A25] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtostbyqdv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxgtkbdp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hammf.cn/Article/details/gtzcmctkbq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxuanxn.top/Article/details/gtzckjkmmq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yanxiufei.cn/Article/details/gtgnfdaeai.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.0kj1m.cn/Article/details/gtpavbhexp.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj20258.top/Article/details/gtlktzigyj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xziqi.cn/Article/details/gtzvscnfme.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gtnxqkvuhl.html

[A26] 类型转换总览
来源：http://dali.guowangkeji.top/Article/details/gtivwoxndv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nanxinkj.top/Article/details/gtxnsnxjkz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.smart0.xyz/Article/details/gtyfghiknu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gzhubu.top/Article/details/gtdtqkkdtq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.guannengcc.top/Article/details/gtqakzekgz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.andypj.xyz/Article/details/gtvrnzdflg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yanxiufei.cn/Article/details/gtmotwslet.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.haohaochexian.top/Article/details/gtrpzmjqle.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzsawofd.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnlfefwfy.html

B. 流程控制
来源：http://dali.iojbl.cn/Article/details/gtjbrjzekz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtfujanqrw.html

[B01] 条件判断 if / else
来源：http://dali.zhijiandao.cn/Article/details/gtzptihljv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.meibo888.top/Article/details/gtpwxujogt.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuxming.cn/Article/details/gtgxcxwbex.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtpsgwbghw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gttclkjeki.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gtkwocbwsv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zdqjudy.top/Article/details/gtokklfgbg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.wangshuangyany.cn/Article/details/gtcxhajwsy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gtcdhpddjg.html

[B02] 多分支 else if / elif
来源：http://dali.jlsjyb.cn/Article/details/gtweutmixb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sxryk.cn/Article/details/gtlqbixxla.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sxryk.cn/Article/details/gtvkrgpgpd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gtlzirwhpl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtmynzrzpm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtpaicxhoy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xylfe.cn/Article/details/gthuteldkc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.dashuyun.cn/Article/details/gtnwdqoylw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtujixajmm.html

[B03] switch / match / case
来源：http://dali.yj20258.top/Article/details/gtzufrjtfh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinqigfzy.top/Article/details/gtakiuefcr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gtwqqdcwmi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtasupquvm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtffqfrffe.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtdqfczyqw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yangfankeji.com/Article/details/gtmhlyefnq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj202588.top/Article/details/gtgrmygndu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gtmusadlzn.html

[B04] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteczhvxdf.html

Py:   for i in range(10): print(i)
来源：http://dali.mhx1999.top/Article/details/gteuymfsll.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhoulong.xyz/Article/details/gtqxegmkao.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ydzc1.top/Article/details/gtzgmnkexu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gtgqjxhwsx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yangfankeji.com/Article/details/gtroctzkoi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.haohaochexian.top/Article/details/gtgqimkucs.html

Ruby: 10.times { |i| puts i }
来源：http://dali.havefunace.top/Article/details/gtxztzxlaf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.dianchejie.cn/Article/details/gtygqyhaxk.html

[B05] 遍历数组 / 列表
来源：http://dali.havefunace.top/Article/details/gtxftwxxcc.html

Py:   for item in arr: print(item)
来源：http://dali.cashguo.top/Article/details/gtijmafgfe.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwricocso.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.mhx1999.top/Article/details/gtxpxtxdtm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigufen.top/Article/details/gtdqnhjuov.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hywenlv.cn/Article/details/gtdvolgjtf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhiwuduotai.top/Article/details/gtxbmbxtym.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fzhhl.top/Article/details/gtdbyfegsa.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwjwffyyp.html

[B06] 遍历字典 / 对象
来源：http://dali.316326.xyz/Article/details/gtxrdnwngi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.andypj.xyz/Article/details/gtrjylajgk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.aibaodan.cn/Article/details/gtbalpsadz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gtovicmywy.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgfzy.top/Article/details/gtodngempf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.redwolf501.top/Article/details/gttpyfuslo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yvedp.cn/Article/details/gtxvbppoat.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hammf.cn/Article/details/gtqbpnrpql.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtlitrwq.html

[B07] while 循环
来源：http://dali.shuidangran.top/Article/details/gtwyulypks.html

Py:   while i < 10: i += 1
来源：http://dali.jqgufenzy.top/Article/details/gtszekvjvj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtruptzxbo.html

JS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxivpkxmc.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtuiliogco.html

Java: while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqjafelr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yueranfly.top/Article/details/gtxovroxgb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ybcxt.top/Article/details/gtajyxwkut.html

C#:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtpfkoeuvg.html

[B08] do-while（至少执行一次）
来源：http://dali.mhx1999.top/Article/details/gtbhxgbyxa.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.meibo888.top/Article/details/gtbpnbyyib.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yvedp.cn/Article/details/gtavbveidc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gttpqlifyi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtaoogqoys.html

Java: do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtoouspfeb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxprzkfmv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.feifeiyinyue.top/Article/details/gtzahhuudw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtxbvsnuim.html

[B09] break 与 continue
来源：http://dali.guannengcc.top/Article/details/gtdolgiyft.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yonumen.top/Article/details/gtrmarrxcn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtavclmini.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtflwgfwuq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtskjxxule.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtdacdklzh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj202588.top/Article/details/gtsnelpong.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.birdmap.top/Article/details/gtogohxzlz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtgvyoovih.html

[B10] 遍历同时拿索引
来源：http://dali.fzhhl.top/Article/details/gthauuzzyh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjogatey.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukuqkzmi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtfbezzhlz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gtksprfwtq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.c1oappe.top/Article/details/gtuymgauoe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuxming.cn/Article/details/gternzadbb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ivvv.top/Article/details/gtubvswlkt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenzaomai.com/Article/details/gtzmwnplww.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhoulong.xyz/Article/details/gtjpnpvpyy.html

Py:   list(range(0, 10, 2))
来源：http://dali.shangyingyoupin.top/Article/details/gtkjqzbxyo.html

PHP:  range(0, 10, 2);
来源：http://dali.yongpay.top/Article/details/gtyexrozbd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gtxsfuacpe.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gtimpuacgp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sweek.top/Article/details/gtyvtafpzs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.quarkkingdee.top/Article/details/gtfxmmeyhp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj202588.top/Article/details/gthkymoyhl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenlongwang.top/Article/details/gtqijklerq.html

[B12] 跳出多层循环
来源：http://dali.svipenyu.cn/Article/details/gtamwoxxww.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gtaoucgzaj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hammf.cn/Article/details/gtnxqmmhop.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtsuxgkntc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtdciuwzom.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gthxunncng.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jlsjyb.cn/Article/details/gtiiygdgzs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cqqwz.cn/Article/details/gtujhjlmgp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cucudq.cn/Article/details/gtzwwzmgau.html

[B13] 判断是否为数字
来源：http://dali.yvedp.cn/Article/details/gtaovjbuvy.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenjidiqi.icu/Article/details/gtzffpgtmd.html

PHP:  is_numeric($x)
来源：http://dali.hnqzz.top/Article/details/gtiupbmawi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gtjynubhmp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtehguzezc.html

Java: x instanceof Number
来源：http://dali.gogol.net.cn/Article/details/gtctsntdox.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pengpengdd.cyou/Article/details/gtvtprszgs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tianlin.xyz/Article/details/gtuvggdkbl.html

C#:   x is int or double or decimal
来源：http://dali.zdqjudy.top/Article/details/gtgojzxvjd.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gtgkxtlgii.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhoulong.xyz/Article/details/gtpowmhaij.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuanzhike.top/Article/details/gtaeyuxgmq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtbzrqfttt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtbhlbqudy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gthxjmikrx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj202588.top/Article/details/gtwofwlgiw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gtwtfvfaui.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtfuczhnrl.html

[B15] 布尔运算与取反
来源：http://dali.hnqzz.top/Article/details/gtswnmayij.html

Py:   a and b or not c
来源：http://dali.smart0.xyz/Article/details/gtgwbqidtb.html

PHP:  $a && $b || !$c
来源：http://dali.chenjidiqi.icu/Article/details/gtftskgxpf.html

JS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtjlcgpdmz.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtufkgcmrh.html

Java: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtgjhbwado.html

Go:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtxrilgghx.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gteuenkido.html

C#:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtptquzjcs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gtzkqwpwrm.html

Py:   if not data: return
来源：http://dali.yueranfly.top/Article/details/gtdarpshui.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gtspjummzp.html

JS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gtkuujnyur.html

TS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxsehube.html

Java: if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtzbbjfjtg.html

Go:   if data == nil { return }
来源：http://dali.aibaodan.cn/Article/details/gtmgnypvsv.html

Ruby: return if data.nil?
来源：http://dali.gogol.net.cn/Article/details/gtinwgaacv.html

C#:   if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtpaahiype.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtkdxjcsgx.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakhncuau.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtxnnfzyfk.html

[C01] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtgvlsnpou.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtpxwkzlmr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtlakevxde.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtidqdumsv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtqegehwxz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gttdbepcqx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sysykeji.top/Article/details/gtnaepzdqw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gtypafqpak.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtgnqeihya.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gtaspjsbzi.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gtfufippqj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cashguo.top/Article/details/gtnzwifpiq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtbxvzjbem.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnrfdpvfc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgufenzy.top/Article/details/gtvjszikyy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sufxvd.cn/Article/details/gtaohycinh.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnxiangtu.top/Article/details/gtkshxffyb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gtkgwwysmz.html

[C03] 可变参数
来源：http://dali.jiagoushi.top/Article/details/gtknmzytav.html

Py:   def total(*args): return sum(args)
来源：http://dali.daxiang520.top/Article/details/gtjhvixmsv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.vqdsnc.cn/Article/details/gtolkghrcd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gtjrvgxtav.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtarbofovt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ppjwa.cn/Article/details/gtuwlkbubp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.redwolf501.top/Article/details/gthhobuqny.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxinkj.top/Article/details/gtygjzooxn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhongyouzk.top/Article/details/gtbjaxblzs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.c1oappe.top/Article/details/gtcelcjxbg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhengqikj.top/Article/details/gtrtgycuvy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gtirekxthv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtvtublxue.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhwnrxpq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gttehrfbcp.html


<!-- 参考信息 -->