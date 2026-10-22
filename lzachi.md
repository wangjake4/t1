代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.chenlongwang.top/Article/details/gtyhftgobg.html

[A15] 空值判断与默认值
来源：http://dali.fengsongda.top/Article/details/gtmbpglfnj.html

Py:   value = data or "默认值"
来源：http://dali.guannengcc.top/Article/details/gtyyjdljdw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gtmoqkambc.html

JS:   const value = data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gtqeuzfmjj.html

TS:   const value = data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gtdqvcqmqy.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.pengpengdd.cyou/Article/details/gtgtvoywsd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hnqzz.top/Article/details/gtxmyeknnj.html

Ruby: value = data || "默认值"
来源：http://dali.yanxiufei.cn/Article/details/gtrzglbqnd.html

C#:   var value = data ?? "默认值";
来源：http://dali.redwolf501.top/Article/details/gtosawgyyc.html

[A16] 真假值判断规则
来源：http://dali.ybcxt.top/Article/details/gtwjwcfnjn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shangyingyoupin.top/Article/details/gtkjjfcexe.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinqigfzy.top/Article/details/gtzdxsxzfx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yonumen.top/Article/details/gtucsenhje.html

TS:   if (!x) {}
来源：http://dali.kuanghao11.cn/Article/details/gtrexzeddl.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shzxlz.cn/Article/details/gtqyaexzzs.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.nwbrower.top/Article/details/gtwuulmiuk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ydzc1.top/Article/details/gtbeuhnopl.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.dianchejie.cn/Article/details/gthyqfujag.html

[A17] 位运算
来源：http://dali.jinqigufen.top/Article/details/gtqnzioyab.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gtgtezyhjp.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.sysykeji.top/Article/details/gtlxyrcddg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtzsekjmhg.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gtdywiaaaq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gthdqtvhoh.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gteauexoyn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtbndhbtpk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtjlwvzjlf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jqgfzy.top/Article/details/gtkxdvicsb.html

Py:   ord("A"); chr(65)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmfibbps.html

PHP:  ord("A"); chr(65)
来源：http://dali.tianlin.xyz/Article/details/gtdjdusawv.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sysykeji.top/Article/details/gtxnojmngt.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yuxming.cn/Article/details/gtzslirxcw.html

Java: (int) 'A'; (char) 65
来源：http://dali.pycfn.com/Article/details/gtxrjkdfms.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.wangshuangyany.cn/Article/details/gtmaxtdblo.html

Ruby: "A".ord; 65.chr
来源：http://dali.guannengcc.top/Article/details/gtouevedwz.html

C#:   (int)'A'; (char)65
来源：http://dali.vqdsnc.cn/Article/details/gtnthividp.html

[A19] 交换两个变量
来源：http://dali.tanke756.top/Article/details/gtvxdpcmqq.html

Py:   a, b = b, a
来源：http://dali.0kj1m.cn/Article/details/gtmdhacxis.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shangyingyoupin.top/Article/details/gtduuwgpkb.html

JS:   [a, b] = [b, a];
来源：http://dali.pycfn.com/Article/details/gtipvopupn.html

TS:   [a, b] = [b, a];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqtlgqua.html

Java: int t = a; a = b; b = t;
来源：http://dali.daxiang520.top/Article/details/gtndlwllyw.html

Go:   a, b = b, a
来源：http://dali.fengsongda.top/Article/details/gtvyzfsyhm.html

Ruby: a, b = b, a
来源：http://dali.guannengcc.top/Article/details/gtufqlawko.html

C#:   (a, b) = (b, a);
来源：http://dali.feifeiyinyue.top/Article/details/gtyredvnvb.html

[A20] 读取标准输入
来源：http://dali.pycfn.com/Article/details/gtwznsawmi.html

Py:   name = input("请输入：")
来源：http://dali.hammf.cn/Article/details/gtzvhsdhbm.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.nanxinkj.top/Article/details/gtrpgfdejf.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkczhoco.html

TS:   // Node.js：readline 模块
来源：http://dali.xziqi.cn/Article/details/gtppuvwfad.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.c1oappe.top/Article/details/gtvsguxdgk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbxmtvlr.html

Ruby: gets.chomp
来源：http://dali.hywenlv.cn/Article/details/gtfpotives.html

C#:   Console.ReadLine();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatsijnxz.html

[A21] 保留指定小数位输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvjtldzx.html

Py:   f"{3.14159:.2f}"
来源：http://dali.daxiang520.top/Article/details/gtajbrjimm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gtwkzgfgdw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtaispxfrh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hywenlv.cn/Article/details/gttllkuift.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gtaksfcnyu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gtmgrbfdbd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gtlyaggkdf.html

C#:   3.14159.ToString("F2")
来源：http://dali.svipenyu.cn/Article/details/gtufjryksz.html

[A22] 获取字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtvpkglyqb.html

Py:   len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndnxcdpl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yj20258.top/Article/details/gtyzyrwydu.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yonumen.top/Article/details/gtqgwzjcvm.html

TS:   s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtmmixczxr.html

Java: s.length()
来源：http://dali.guowangkeji.top/Article/details/gtixhfownz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sysykeji.top/Article/details/gtwjikqfwc.html

Ruby: s.length
来源：http://dali.kuanghao11.cn/Article/details/gttgtteyeg.html

C#:   s.Length
来源：http://dali.tanke756.top/Article/details/gtqqnolzzv.html

[A23] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtvjxhaoxy.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xziqi.cn/Article/details/gtimewrphe.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cdnleiting.top/Article/details/gtcpgqsmtg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shzxlz.cn/Article/details/gtoypxedoq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhxpjlvb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yueranfly.top/Article/details/gtkfnhghgo.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.birdmap.top/Article/details/gtbppmemnu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gtqyulfnmq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shzxlz.cn/Article/details/gtwlfmopsl.html

[A24] 去除首尾空白
来源：http://dali.c1oappe.top/Article/details/gtosmnufuo.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jianghu66.top/Article/details/gtwhhsmruw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.wangdashe.top/Article/details/gtujamiuif.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tianlin.xyz/Article/details/gtgsgxgnis.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gtefxjarhx.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.wangdashe.top/Article/details/gtnzsnzpqy.html

Go:   strings.TrimSpace(s)
来源：http://dali.shzxlz.cn/Article/details/gtltzqwlie.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenzaomai.com/Article/details/gtoxugrlnj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258.top/Article/details/gtgvmcorvd.html

[A25] 字符串比较
来源：http://dali.jianghu66.top/Article/details/gtrbgwbkzp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhixingplan.top/Article/details/gtyrvnulfr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nwbrower.top/Article/details/gtvcuxivyw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shangyingyoupin.top/Article/details/gtqnkhvkjd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.316326.xyz/Article/details/gtanxmuxwx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.dashuyun.cn/Article/details/gturhvvwwv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gtvuxwfvci.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ivvv.top/Article/details/gtrhvzyzym.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yj20258.top/Article/details/gtubwgreob.html

[A26] 类型转换总览
来源：http://dali.yuxming.cn/Article/details/gtvybyuqen.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jianghu66.top/Article/details/gtlgvfkptg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xuetiantiany.cn/Article/details/gtyurqyxzv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.aizwys.cn/Article/details/gtozqtfwpe.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cheryme.top/Article/details/gtzuuromee.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ivvv.top/Article/details/gtsgysrota.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yueranfly.top/Article/details/gtevwzprah.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.svipenyu.cn/Article/details/gtvpilldqx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tian-w.cn/Article/details/gtscejmxsj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtyhvlhvvv.html

B. 流程控制
来源：http://dali.daria6918.cn/Article/details/gtcdcftihs.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqxitkonk.html

[B01] 条件判断 if / else
来源：http://dali.sufxvd.cn/Article/details/gtiepbuqao.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.chenlongwang.top/Article/details/gtlkfmuhgo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuwmixfea.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gtjwzdkxbk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gttmejdfvx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtycabdwua.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ivvv.top/Article/details/gtbjgmwuut.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tian-w.cn/Article/details/gtawlojqlg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtqqckeupx.html

[B02] 多分支 else if / elif
来源：http://dali.aibaodan.cn/Article/details/gtginxablj.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenlongwang.top/Article/details/gtfikvrlcc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.guannengcc.top/Article/details/gtfofussgm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtxxpbpeuv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gtwepisxsn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gticzcqagq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.guowangkeji.top/Article/details/gtlmxzapfs.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.quarkkingdee.top/Article/details/gtsmhfaafh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gtufofjrns.html

[B03] switch / match / case
来源：http://dali.0kj1m.cn/Article/details/gtmozbhvfw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenzaomai.com/Article/details/gtisgwvmnq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtfnqltrfh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gtvjeqlxgz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtstfekqfq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gteayjwbww.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ydzc1.top/Article/details/gtlbfqynsj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.tian-w.cn/Article/details/gtdbufzozx.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.wangshuangyany.cn/Article/details/gtcnagqidp.html

[B04] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gtoidmlxnw.html

Py:   for i in range(10): print(i)
来源：http://dali.wangdashe.top/Article/details/gtccnwwuze.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.aizwys.cn/Article/details/gtvshadlzp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gtjbhebrjh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtaldqmzhl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.c1oappe.top/Article/details/gtuyxrfqkz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj20258.top/Article/details/gtatzwaixu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hywenlv.cn/Article/details/gtnkhnxuzi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.snrcjt.cn/Article/details/gtifohegzs.html

[B05] 遍历数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gtgufitkpm.html

Py:   for item in arr: print(item)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgysiakg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinqigufen.top/Article/details/gtemvktcte.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gtnljhnvff.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gtrcwidyki.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cucudq.cn/Article/details/gtfzuxquyc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cqqwz.cn/Article/details/gtexvyjsfs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jyoumei.cn/Article/details/gtrqbvovau.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hammf.cn/Article/details/gtuhofiibu.html

[B06] 遍历字典 / 对象
来源：http://dali.daria6918.cn/Article/details/gtvdezljca.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhoulong.xyz/Article/details/gtlemwgcrl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtykusbkyv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zycfv.cn/Article/details/gtqfjlgvws.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hfpthk.cn/Article/details/gtfmschdcj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jqgufenzy.top/Article/details/gtqdiqrdqh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.kuanghao11.cn/Article/details/gtmswjwqaa.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guannengcc.top/Article/details/gtygerjssk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fzhhl.top/Article/details/gtabjvaxft.html

[B07] while 循环
来源：http://dali.nanxinkj.top/Article/details/gtkaofcjxj.html

Py:   while i < 10: i += 1
来源：http://dali.gzhubu.top/Article/details/gttqrgqwtr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tanke756.top/Article/details/gtyqjhqgwk.html

JS:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtlzazwcnn.html

TS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtdgyyqypa.html

Java: while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtswvzmswh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.birdmap.top/Article/details/gtujplesjb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ehwqpu.com/Article/details/gtkinjdesw.html

C#:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtkpmtsaxc.html

[B08] do-while（至少执行一次）
来源：http://dali.fengsongda.top/Article/details/gtxqcjptyc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuxming.cn/Article/details/gtctmxeeim.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.smart0.xyz/Article/details/gtofhivolc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtgmuvrcpt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gthbtprzkg.html

Java: do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtyfdlnwfh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gtnykaykio.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xinyue.icu/Article/details/gtydegrgrl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtmxyjmigy.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gtwxasvulp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258888.top/Article/details/gtrnebkwtk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtzgsjhxad.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtnrqgmvrl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtdqyrfazx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyslajpvu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xziqi.cn/Article/details/gtgvofnikr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.andypj.xyz/Article/details/gtsyadgrhq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtwtinirnh.html

[B10] 遍历同时拿索引
来源：http://dali.fzhhl.top/Article/details/gtyxksgsni.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nanxuanxn.top/Article/details/gtsnatnekq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guannengcc.top/Article/details/gttqgdezdu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtuqgwutng.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pycfn.com/Article/details/gtiqyxnyaw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zdqjudy.top/Article/details/gtckgubhjy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cheryme.top/Article/details/gthhzmucxn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yueranfly.top/Article/details/gtowvegzvy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gtuvqqvemi.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenzaomai.com/Article/details/gtyyvdnrvs.html

Py:   list(range(0, 10, 2))
来源：http://dali.yonumen.top/Article/details/gtygodapfg.html

PHP:  range(0, 10, 2);
来源：http://dali.yuxming.cn/Article/details/gtdccvykkf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtkaqrjajt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gtkolcvojc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeeaazhh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cqqwz.cn/Article/details/gtjzayduih.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tanke756.top/Article/details/gtorpxosza.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.vqdsnc.cn/Article/details/gtefxseami.html

[B12] 跳出多层循环
来源：http://dali.zhongyouzk.top/Article/details/gtadwpipgv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jlsjyb.cn/Article/details/gtumtqwyyl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgufenzy.top/Article/details/gtbczuqdkl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtcltwnsol.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtzcqjtift.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gtnggeksqk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xylfe.cn/Article/details/gtxznzkxlc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fzhhl.top/Article/details/gtcfeavwbr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sweek.top/Article/details/gtelewszhf.html

[B13] 判断是否为数字
来源：http://dali.daxiang520.top/Article/details/gtkkaabcxa.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gtsasqlspd.html

PHP:  is_numeric($x)
来源：http://dali.316326.xyz/Article/details/gtrbeiaudi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtcickocim.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.redwolf501.top/Article/details/gtkkexwabh.html

Java: x instanceof Number
来源：http://dali.ivvv.top/Article/details/gtalrwrtaf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cheryme.top/Article/details/gthaqyrunj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shzxlz.cn/Article/details/gtvxrfrxvo.html

C#:   x is int or double or decimal
来源：http://dali.gzhubu.top/Article/details/gtzrzechjq.html

[B14] 判断值是否在集合内
来源：http://dali.andypj.xyz/Article/details/gttlgakgln.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sufxvd.cn/Article/details/gtyrxgwedq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgfzy.top/Article/details/gtqhmdxvpa.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtwjxmyrqp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gtsdpdgzam.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtwlmuhvji.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yonumen.top/Article/details/gtfoqvuand.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hfpthk.cn/Article/details/gtjydlsqer.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtrudwlmtt.html

[B15] 布尔运算与取反
来源：http://dali.nanxinkj.top/Article/details/gtnnhyfibu.html

Py:   a and b or not c
来源：http://dali.zhongyouzk.top/Article/details/gtmbbevrke.html

PHP:  $a && $b || !$c
来源：http://dali.ydzc1.top/Article/details/gtdcaupgmr.html

JS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtyasdxxqf.html

TS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtncsujzba.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtxfticlsi.html

Go:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtsdtjcoal.html

Ruby: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtgldwgjtn.html

C#:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtbkdgecau.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnncmevns.html

Py:   if not data: return
来源：http://dali.daxiang520.top/Article/details/gtmhqeelcl.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigfzy.top/Article/details/gtzdibmeps.html

JS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gtuxycsifg.html

TS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtzvuonkcl.html

Java: if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtzbzmxuil.html

Go:   if data == nil { return }
来源：http://dali.daria6918.cn/Article/details/gtikunbrga.html

Ruby: return if data.nil?
来源：http://dali.aizwys.cn/Article/details/gtjhpuipai.html

C#:   if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gttgilriyn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthxknwijr.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gththsvhho.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnidrdlbp.html

[C01] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjebazkn.html

Py:   def add(a, b): return a + b
来源：http://dali.gaohongyu789.top/Article/details/gtilxwroxd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkeeszxhw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtkzprcvch.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtdmvlbmva.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtxtuxgikq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtnlnmuvfg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gtlvfvtzsy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtdofwayfk.html

[C02] 默认参数
来源：http://dali.cqqwz.cn/Article/details/gtuvlcmdon.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gtanavlmmt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jyoumei.cn/Article/details/gtchnsvatq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtjaxtotsn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdsztbmp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dashuyun.cn/Article/details/gtzvtsrhdq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sweek.top/Article/details/gtjhfnfuwi.html

Ruby: def greet(name = "World") = name
来源：http://dali.svipenyu.cn/Article/details/gtfprcjgta.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hongshengwenyu.top/Article/details/gtkeobpliw.html

[C03] 可变参数
来源：http://dali.nwbrower.top/Article/details/gtxndyjoig.html

Py:   def total(*args): return sum(args)
来源：http://dali.bjfxy.top/Article/details/gtmeknmbiw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtmnkrljla.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtijeewdgw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gtzbeyzmig.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jyoumei.cn/Article/details/gtgavpwlgd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dashuyun.cn/Article/details/gtumhdbjfj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhongyouzk.top/Article/details/gtifdibemx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tianlin.xyz/Article/details/gtwdxgukuy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dashuyun.cn/Article/details/gtedpfkkfn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvromqsdj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gaohongyu789.top/Article/details/gtjektnqhv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyiqsxtzy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuanzhike.top/Article/details/gtwzemnoqm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pycfn.com/Article/details/gtidakcbal.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gtuciaxysf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtxfrppvpl.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtumnheorh.html

[C05] 返回多个值
来源：http://dali.yonumen.top/Article/details/gtwhfnwkzr.html

Py:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtkzjijxuc.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtfifzgirc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuxming.cn/Article/details/gtedvomhrn.html

TS:   return { a, b };
来源：http://dali.xziqi.cn/Article/details/gtlrflcwqw.html


<!-- 参考信息 -->