代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.bjfxy.top/Article/details/gtnqntyrfs.html

JS:   `Hello, ${name}!`
来源：http://dali.ybcxt.top/Article/details/gtyekcqhdk.html

TS:   `Hello, ${name}!`
来源：http://dali.yueranfly.top/Article/details/gttjopjwmr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.nwbrower.top/Article/details/gtqzxaevoh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhongyouzk.top/Article/details/gtpiujqore.html

Ruby: "Hello, #{name}!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtylzzsdho.html

C#:   $"Hello, {name}!"
来源：http://dali.tanke756.top/Article/details/gtzhrbbxbl.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xuetiantiany.cn/Article/details/gtxdchpbed.html

Py:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gtzygytazj.html

PHP:  "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtllydtvai.html

JS:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gthsewihqa.html

TS:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtnmxsuaeo.html

Java: "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtbcjncbbi.html

Go:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtooeptirk.html

Ruby: "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdtqyhgi.html

C#:   "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gtnnpnajbf.html

[A14] 注释写法
来源：http://dali.sysykeji.top/Article/details/gtlcxxwbys.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.birdmap.top/Article/details/gtgorjvycd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtqzfwyqey.html

JS:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtboycydps.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozldyqlj.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.nwbrower.top/Article/details/gtzgkoenex.html

Go:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtlilkwqya.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sysykeji.top/Article/details/gtfebiiyjc.html

C#:   // 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gtbfloyxdy.html

[A15] 空值判断与默认值
来源：http://dali.havefunace.top/Article/details/gtrvmokhtv.html

Py:   value = data or "默认值"
来源：http://dali.feifeiyinyue.top/Article/details/gtmnjmxppx.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gtjpvuvplm.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqdlegpi.html

TS:   const value = data ?? "默认值";
来源：http://dali.ehwqpu.com/Article/details/gtanmomicu.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhengqikj.top/Article/details/gtwpfhzlhl.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.dianchejie.cn/Article/details/gtnsdvgjco.html

Ruby: value = data || "默认值"
来源：http://dali.mhx1999.top/Article/details/gtdhzojhwt.html

C#:   var value = data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gthdsyhibe.html

[A16] 真假值判断规则
来源：http://dali.gotoacloud.top/Article/details/gtddcicoeo.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhongyouzk.top/Article/details/gtwxszrjaa.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jqgfzy.top/Article/details/gtwnydrtld.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.smart0.xyz/Article/details/gtwezwamsk.html

TS:   if (!x) {}
来源：http://dali.yj202588.top/Article/details/gtmyqyjmwn.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwnuzeya.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hywenlv.cn/Article/details/gtxbcjsnge.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.kuanghao11.cn/Article/details/gtfomnuknb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shuidangran.top/Article/details/gtbuxnvckn.html

[A17] 位运算
来源：http://dali.0kj1m.cn/Article/details/gtszshqkem.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtmvhwzyae.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtdgunttqs.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtqyuhanay.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtjhnogpbz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtqdffjkfe.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtdqmcnykm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtufazgqlk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gtigzwyxsu.html

[A18] 字符与 ASCII 码互转
来源：http://dali.ivvv.top/Article/details/gtciafcopf.html

Py:   ord("A"); chr(65)
来源：http://dali.jianghu66.top/Article/details/gttqxetuae.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinqigufen.top/Article/details/gtcejutjfr.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.redwolf501.top/Article/details/gtyyjqgzve.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gaohongyu789.top/Article/details/gtburbxxoe.html

Java: (int) 'A'; (char) 65
来源：http://dali.zycfv.cn/Article/details/gtwauvxvrb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.daxiang520.top/Article/details/gtzzyfrajo.html

Ruby: "A".ord; 65.chr
来源：http://dali.guowangkeji.top/Article/details/gtidpnnsxy.html

C#:   (int)'A'; (char)65
来源：http://dali.hongshengwenyu.top/Article/details/gtthmwgvva.html

[A19] 交换两个变量
来源：http://dali.xuetiantiany.cn/Article/details/gtdtavhrqj.html

Py:   a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gtsjcyignz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.pycfn.com/Article/details/gtvjexlljn.html

JS:   [a, b] = [b, a];
来源：http://dali.wangdashe.top/Article/details/gtjgwbqogo.html

TS:   [a, b] = [b, a];
来源：http://dali.guowangkeji.top/Article/details/gtnujtaccu.html

Java: int t = a; a = b; b = t;
来源：http://dali.haohaochexian.top/Article/details/gtikqfnrbt.html

Go:   a, b = b, a
来源：http://dali.haohaochexian.top/Article/details/gtpbovmlug.html

Ruby: a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gtmzwgnokt.html

C#:   (a, b) = (b, a);
来源：http://dali.yuanzhike.top/Article/details/gtlzkcwogn.html

[A20] 读取标准输入
来源：http://dali.guowangkeji.top/Article/details/gtmxmzazdo.html

Py:   name = input("请输入：")
来源：http://dali.meibo888.top/Article/details/gtgzphljgz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yuanzhike.top/Article/details/gtzuvzpefx.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhongyouzk.top/Article/details/gtwieyhgqz.html

TS:   // Node.js：readline 模块
来源：http://dali.sufxvd.cn/Article/details/gtijftokjq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yj20258.top/Article/details/gtapippkyl.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.316326.xyz/Article/details/gtqtyuquxc.html

Ruby: gets.chomp
来源：http://dali.9152youxi.cn/Article/details/gtxrslcqry.html

C#:   Console.ReadLine();
来源：http://dali.yongpay.top/Article/details/gtjukeqeen.html

[A21] 保留指定小数位输出
来源：http://dali.cdnleiting.top/Article/details/gtorfgwxcl.html

Py:   f"{3.14159:.2f}"
来源：http://dali.aizwys.cn/Article/details/gtebdfggpr.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hfpthk.cn/Article/details/gtpzwhfnjy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gtfklvelzm.html

TS:   (3.14159).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtazaxsvdg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xinyue.icu/Article/details/gtubzujtsb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gtwvoagyvl.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtzwrslzib.html

C#:   3.14159.ToString("F2")
来源：http://dali.yuanzhike.top/Article/details/gtrhptszci.html

[A22] 获取字符串长度
来源：http://dali.yueranfly.top/Article/details/gtlycrsmyt.html

Py:   len(s)
来源：http://dali.ppjwa.cn/Article/details/gtqbtskwtu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.wangdashe.top/Article/details/gtorfasxvl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xinyue.icu/Article/details/gtngyuoazh.html

TS:   s.length
来源：http://dali.zycfv.cn/Article/details/gtpzgszfrw.html

Java: s.length()
来源：http://dali.c1oappe.top/Article/details/gtqdlycbws.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ybcxt.top/Article/details/gtbhtlwhsw.html

Ruby: s.length
来源：http://dali.gaohongyu789.top/Article/details/gtklumrrxj.html

C#:   s.Length
来源：http://dali.cashguo.top/Article/details/gtleoriwbl.html

[A23] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtqvdokboq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.mhx1999.top/Article/details/gtzoajrvka.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.pengpengdd.cyou/Article/details/gtcagnreor.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxbvrycj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.svipenyu.cn/Article/details/gtzeeocenn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.birdmap.top/Article/details/gtmwkghkyy.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xylfe.cn/Article/details/gteuizinxk.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.0kj1m.cn/Article/details/gtkawnhsxs.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yueranfly.top/Article/details/gthpawbinx.html

[A24] 去除首尾空白
来源：http://dali.yanxiufei.cn/Article/details/gtzmxqhtez.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sysykeji.top/Article/details/gtckolpzbb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.daxiang520.top/Article/details/gtaeizdkey.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenlongwang.top/Article/details/gtcirqvter.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zycfv.cn/Article/details/gtdqumwqeg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.svipenyu.cn/Article/details/gtnkrktwfm.html

Go:   strings.TrimSpace(s)
来源：http://dali.hysaishi.cn/Article/details/gtxudzkdsg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhijiandao.cn/Article/details/gtwjobuyhg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.svipenyu.cn/Article/details/gtknkwykwc.html

[A25] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gtkusrbgsf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.316326.xyz/Article/details/gtigwlmysq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hnqzz.top/Article/details/gtswxtculq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gtnbowlgwd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnqzz.top/Article/details/gtkqfptkgo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.316326.xyz/Article/details/gteegzpgkq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.0kj1m.cn/Article/details/gtzrtswped.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cucudq.cn/Article/details/gtjwxtcils.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gtkvcvfqmj.html

[A26] 类型转换总览
来源：http://dali.jiagoushi.top/Article/details/gtrqcnusjj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cdnleiting.top/Article/details/gtqseamiuh.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxinkj.top/Article/details/gtourfdsuf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xinyue.icu/Article/details/gtqcdbrizc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjhzowpo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gotoacloud.top/Article/details/gtjtsgchdz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykazztiv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hywenlv.cn/Article/details/gtmuwnucnh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hnqzz.top/Article/details/gtxqstfzkc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtygmjqrqc.html

B. 流程控制
来源：http://dali.jinqigufen.top/Article/details/gtymvhjwih.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtkjnlyaov.html

[B01] 条件判断 if / else
来源：http://dali.gotoacloud.top/Article/details/gtkxgsjuba.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ehwqpu.com/Article/details/gtpggrpfav.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jqgufenzy.top/Article/details/gtfynyhuri.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gtpiebiaku.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gtojfwbpxz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtpdfbiyki.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.svipenyu.cn/Article/details/gtceflbekw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gogol.net.cn/Article/details/gtreitdoda.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gtvvucqqzc.html

[B02] 多分支 else if / elif
来源：http://dali.ppjwa.cn/Article/details/gtducqigqi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenjidiqi.icu/Article/details/gtlmpfhajc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sweek.top/Article/details/gtbersckgj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtzzbunwrs.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gtuzgailbk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gthskcqncl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jlsjyb.cn/Article/details/gtsbmyyrub.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.fengsongda.top/Article/details/gtrdtiemqz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtgbqwxqmw.html

[B03] switch / match / case
来源：http://dali.yueranfly.top/Article/details/gtrsfaltet.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslvtqfye.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gtfyuahicd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtjzfzepxy.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtabhmgwxs.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtjwcxvade.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yonumen.top/Article/details/gtwbldddjo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.guowangkeji.top/Article/details/gtgluyipux.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sweek.top/Article/details/gttouxltxl.html

[B04] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtmqhactfl.html

Py:   for i in range(10): print(i)
来源：http://dali.jqgufenzy.top/Article/details/gtrvtuhmes.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shuidangran.top/Article/details/gtqcegjjme.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenzaomai.com/Article/details/gtwvxigmgm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpelllqsy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ybcxt.top/Article/details/gtqhnxyfdz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xuetiantiany.cn/Article/details/gthhpkiukl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuetiantiany.cn/Article/details/gtmvqjdrbp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gthkjkqthy.html

[B05] 遍历数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gtvbfrzppa.html

Py:   for item in arr: print(item)
来源：http://dali.yj202588.top/Article/details/gtmrxbdkum.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.guowangkeji.top/Article/details/gtepzhpizf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.fzhhl.top/Article/details/gtcgqjosdo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hfpthk.cn/Article/details/gtqfvdzxui.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ydzc1.top/Article/details/gtvoqlfput.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yanxiufei.cn/Article/details/gtbzjembnp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.haohaochexian.top/Article/details/gtouzmksqi.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jlsjyb.cn/Article/details/gtvhmktold.html

[B06] 遍历字典 / 对象
来源：http://dali.hnxiangtu.top/Article/details/gtluowvfst.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xinyue.icu/Article/details/gtjiukpeff.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhengqikj.top/Article/details/gtvsaoefua.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gtwqpltlhe.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnxiangtu.top/Article/details/gtzwfnpnhv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gaohongyu789.top/Article/details/gtkuzoshxw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.guowangkeji.top/Article/details/gtixlszapv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ehwqpu.com/Article/details/gtqxvwkzft.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tianlin.xyz/Article/details/gthnpqchjf.html

[B07] while 循环
来源：http://dali.yueranfly.top/Article/details/gtddpuoycs.html

Py:   while i < 10: i += 1
来源：http://dali.haohaochexian.top/Article/details/gttbrqtggi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangdashe.top/Article/details/gtzaeeijca.html

JS:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtrpbjbeey.html

TS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gttetybyry.html

Java: while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gthjonwnaf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gtxgszwmja.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pycfn.com/Article/details/gtraqpbhcn.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtzcgcyyjd.html

[B08] do-while（至少执行一次）
来源：http://dali.cucudq.cn/Article/details/gtjamehlsr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuanzx.com/Article/details/gtpyfzxsyp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtbawkimhs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtdksprkrv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtmuimuokg.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtertszpnr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.bjfxy.top/Article/details/gtqpwqlxfy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shuidangran.top/Article/details/gtbjsxurii.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtodvpwtgf.html

[B09] break 与 continue
来源：http://dali.zdqjudy.top/Article/details/gtsgbtjghk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yangfankeji.com/Article/details/gtbohhmtut.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtrnpnfnbl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtyfsuwthc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtvrxuyvdo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtcwdjbyzh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ivvv.top/Article/details/gtpflaikdd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sysykeji.top/Article/details/gthdwnqmgu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gthngdrxvb.html

[B10] 遍历同时拿索引
来源：http://dali.cucudq.cn/Article/details/gtjcqzqqub.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daxiang520.top/Article/details/gtgdupbxgo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sweek.top/Article/details/gtrqoeddcp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtqnkxeule.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gtdhfkmlbs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuanzx.com/Article/details/gtdcpkutzd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.andypj.xyz/Article/details/gtupczndiz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gotoacloud.top/Article/details/gtbxajsoum.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yongpay.top/Article/details/gtgiiyzqqe.html

[B11] 生成数字序列 / 区间
来源：http://dali.snrcjt.cn/Article/details/gtmocomtpk.html

Py:   list(range(0, 10, 2))
来源：http://dali.aibaodan.cn/Article/details/gtkvnzqbru.html

PHP:  range(0, 10, 2);
来源：http://dali.jianghu66.top/Article/details/gtfcottvnb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gtpuamuheg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtixhmpext.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigufen.top/Article/details/gtasoeectb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhongyouzk.top/Article/details/gtmwtunamk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.bjfxy.top/Article/details/gtkhaaamai.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gaohongyu789.top/Article/details/gtwexnjpmi.html

[B12] 跳出多层循环
来源：http://dali.zdqjudy.top/Article/details/gtlxoptkqp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jiagoushi.top/Article/details/gtwgaptxrw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.svipenyu.cn/Article/details/gtbwvgocdo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gtwftqvhgl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gturyxdnsu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtvcsuevfh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gtpbngpvss.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhoulong.xyz/Article/details/gtarmxaavx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hfpthk.cn/Article/details/gtqzmqditu.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gtghxltlbv.html

Py:   isinstance(x, (int, float))
来源：http://dali.smart0.xyz/Article/details/gtpozhdahh.html

PHP:  is_numeric($x)
来源：http://dali.aizwys.cn/Article/details/gtqsleifff.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtrttpjakg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtnowdfcuu.html

Java: x instanceof Number
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegdkwzyf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenlongwang.top/Article/details/gtbeoenljo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.9152youxi.cn/Article/details/gtghjgwztp.html

C#:   x is int or double or decimal
来源：http://dali.zdqjudy.top/Article/details/gtrbrezgry.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gtqsmqohkv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gtcdsknrbw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtciolnrcr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtebyioqye.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtrjoboacv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtlorqxyyx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxelksnx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yongpay.top/Article/details/gtckjgcomx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtmddkcxha.html

[B15] 布尔运算与取反
来源：http://dali.yuxming.cn/Article/details/gtjlktvnej.html

Py:   a and b or not c
来源：http://dali.ybcxt.top/Article/details/gtaudpyxeo.html

PHP:  $a && $b || !$c
来源：http://dali.andypj.xyz/Article/details/gtqvseuioz.html

JS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtqjqdfoyf.html

TS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtvmghyyvz.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtruxigqzx.html

Go:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtezqmqlpr.html

Ruby: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtcyuakziw.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtbggmgzfh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cqqwz.cn/Article/details/gtwsinstzy.html

Py:   if not data: return
来源：http://dali.yuxming.cn/Article/details/gtlkooqylg.html

PHP:  if (!$data) { return; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdbommfuf.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtkgvpdcya.html

TS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gteuqpnbxh.html

Java: if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgohxdowb.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gtjxyihyrk.html

Ruby: return if data.nil?
来源：http://dali.bjfxy.top/Article/details/gtjmviyihh.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtxbniclch.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfnfmzvxi.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtskicayzp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjmbmauom.html

[C01] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtagmkveab.html

Py:   def add(a, b): return a + b
来源：http://dali.yj202588.top/Article/details/gthkprxudl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtjaszjfbz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtjljqqchy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtdyonhgkx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtpltovkce.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuanzhike.top/Article/details/gthhemugpr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guowangkeji.top/Article/details/gtgydxrbac.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtitilelai.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtxjoufoko.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgfzy.top/Article/details/gtecmluhal.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daxiang520.top/Article/details/gtdwvtxghx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvbhmgof.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtrlutrjyg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aibaodan.cn/Article/details/gtfdzzddtb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.0kj1m.cn/Article/details/gtvmamdpse.html

Ruby: def greet(name = "World") = name
来源：http://dali.mhx1999.top/Article/details/gtllcqodjo.html


<!-- 参考信息 -->