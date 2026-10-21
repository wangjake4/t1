代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gtupaawwvh.html

[A15] 空值判断与默认值
来源：http://dali.hfpthk.cn/Article/details/gtrnnpttob.html

Py:   value = data or "默认值"
来源：http://dali.smart0.xyz/Article/details/gtlwzbwaba.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gtuavpmrjj.html

JS:   const value = data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gtyntpoyca.html

TS:   const value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gtgqrlaflt.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.dianchejie.cn/Article/details/gtaquahxbl.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sxryk.cn/Article/details/gtkkkmcbxm.html

Ruby: value = data || "默认值"
来源：http://dali.dashuyun.cn/Article/details/gttspimtva.html

C#:   var value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gtpbgzmjwk.html

[A16] 真假值判断规则
来源：http://dali.sufxvd.cn/Article/details/gtsejbklar.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.9152youxi.cn/Article/details/gtpwpmjsuy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.aibaodan.cn/Article/details/gtfhbxdwwk.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.daria6918.cn/Article/details/gtmpbzsdfz.html

TS:   if (!x) {}
来源：http://dali.hfpthk.cn/Article/details/gtfdqcejmw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsbmfvgf.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenjidiqi.icu/Article/details/gteujxbcpg.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hammf.cn/Article/details/gtqzsmurhb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sufxvd.cn/Article/details/gtihmflrvn.html

[A17] 位运算
来源：http://dali.andypj.xyz/Article/details/gtqqbhaapy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtabcwgaqg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.cashguo.top/Article/details/gtgzhbegfa.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtmfyvfecc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gtndbayuwj.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtfslmethh.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gtbyoyhrtz.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gtdubmifug.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtyfxbhlyg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hywenlv.cn/Article/details/gtlyeknwtn.html

Py:   ord("A"); chr(65)
来源：http://dali.dianchejie.cn/Article/details/gtcvwswwqm.html

PHP:  ord("A"); chr(65)
来源：http://dali.hnqzz.top/Article/details/gtqoayejqb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zdqjudy.top/Article/details/gtvvtegogo.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yonumen.top/Article/details/gtarbmelsc.html

Java: (int) 'A'; (char) 65
来源：http://dali.kuanghao11.cn/Article/details/gtigggcxfw.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yueranfly.top/Article/details/gtqfnnsjty.html

Ruby: "A".ord; 65.chr
来源：http://dali.ivvv.top/Article/details/gtsjibxeke.html

C#:   (int)'A'; (char)65
来源：http://dali.yj20258.top/Article/details/gtfkjadamn.html

[A19] 交换两个变量
来源：http://dali.xylfe.cn/Article/details/gtcartwhgx.html

Py:   a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gtiorobtdw.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.dashuyun.cn/Article/details/gtfirnlfjs.html

JS:   [a, b] = [b, a];
来源：http://dali.havefunace.top/Article/details/gtpltklall.html

TS:   [a, b] = [b, a];
来源：http://dali.jqgfzy.top/Article/details/gtqhqdhyja.html

Java: int t = a; a = b; b = t;
来源：http://dali.dashuyun.cn/Article/details/gtkvtmzucs.html

Go:   a, b = b, a
来源：http://dali.sufxvd.cn/Article/details/gthklbgzbl.html

Ruby: a, b = b, a
来源：http://dali.cqqwz.cn/Article/details/gtbyqnuafi.html

C#:   (a, b) = (b, a);
来源：http://dali.ppjwa.cn/Article/details/gtipxrjvsz.html

[A20] 读取标准输入
来源：http://dali.dianchejie.cn/Article/details/gtmmjewxoa.html

Py:   name = input("请输入：")
来源：http://dali.hywenlv.cn/Article/details/gtiktikaay.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sweek.top/Article/details/gtwowarvyg.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.daria6918.cn/Article/details/gtvftgfdqr.html

TS:   // Node.js：readline 模块
来源：http://dali.zhoulong.xyz/Article/details/gtwfgjztxj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xylfe.cn/Article/details/gtrpaokhfr.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shangyingyoupin.top/Article/details/gtywfqnfzm.html

Ruby: gets.chomp
来源：http://dali.haohaochexian.top/Article/details/gtsraekrii.html

C#:   Console.ReadLine();
来源：http://dali.xuanzx.com/Article/details/gtpvggldlg.html

[A21] 保留指定小数位输出
来源：http://dali.yangfankeji.com/Article/details/gtnxqdforc.html

Py:   f"{3.14159:.2f}"
来源：http://dali.kuanghao11.cn/Article/details/gttmkbclyp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqxdpirh.html

JS:   (3.14159).toFixed(2)
来源：http://dali.snrcjt.cn/Article/details/gtqxjgsjbs.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtbkvihgse.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gtctinyyoo.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.haohaochexian.top/Article/details/gtqpmxvqhi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gtcvqseabl.html

C#:   3.14159.ToString("F2")
来源：http://dali.jinqigfzy.top/Article/details/gtvxrtlbmt.html

[A22] 获取字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtovrabcvn.html

Py:   len(s)
来源：http://dali.0kj1m.cn/Article/details/gtqpxxqmsn.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ydzc1.top/Article/details/gtixlcdhgt.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.smart0.xyz/Article/details/gtuavchjsn.html

TS:   s.length
来源：http://dali.zdqjudy.top/Article/details/gtdjeiserx.html

Java: s.length()
来源：http://dali.xylfe.cn/Article/details/gtzeajjchv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cqqwz.cn/Article/details/gtwxcfqlvo.html

Ruby: s.length
来源：http://dali.bjfxy.top/Article/details/gtavjumyln.html

C#:   s.Length
来源：http://dali.aizwys.cn/Article/details/gtvogtmiaa.html

[A23] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtjofhytwc.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gteggluqya.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.bjfxy.top/Article/details/gtocesbpqd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gtftaktwyv.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpbuqtvl.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.iojbl.cn/Article/details/gtpenqhtaj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.dianchejie.cn/Article/details/gtuvirobcc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gtyxjpasjv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yanxiufei.cn/Article/details/gtjgtxtgat.html

[A24] 去除首尾空白
来源：http://dali.jqgfzy.top/Article/details/gtcwzlqnow.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.pycfn.com/Article/details/gtmozjcbba.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.wangdashe.top/Article/details/gttjynlqoz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gtyiprtaee.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zycfv.cn/Article/details/gtlhahyvqu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.andypj.xyz/Article/details/gtluxnbwyt.html

Go:   strings.TrimSpace(s)
来源：http://dali.jinqigfzy.top/Article/details/gtkctibpra.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shanyushiyangtech.top/Article/details/gtjclpfusf.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.haohaochexian.top/Article/details/gtydulbhuv.html

[A25] 字符串比较
来源：http://dali.jianghu66.top/Article/details/gtxuvzhygz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.birdmap.top/Article/details/gtwrjpfspc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cucudq.cn/Article/details/gtegvfakao.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcxoyahs.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.svipenyu.cn/Article/details/gtulvomaij.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hysaishi.cn/Article/details/gtdnekajap.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zdqjudy.top/Article/details/gtdwivtjhr.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.aizwys.cn/Article/details/gtrdgjbzua.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gtjkizqmib.html

[A26] 类型转换总览
来源：http://dali.xziqi.cn/Article/details/gtqtpufjoy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.aizwys.cn/Article/details/gtbvxfbfid.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.bjfxy.top/Article/details/gtlcceenys.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yueranfly.top/Article/details/gtitncabad.html

TS:   Number() String() Boolean() x as number
来源：http://dali.bjfxy.top/Article/details/gtdvvhuieh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xuetiantiany.cn/Article/details/gthbcxfafs.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cucudq.cn/Article/details/gtlzljdtry.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj20258.top/Article/details/gtmhbzjpoo.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.guowangkeji.top/Article/details/gtaiplaley.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtczotjueu.html

B. 流程控制
来源：http://dali.zhengqikj.top/Article/details/gtukpjhbii.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrfimyjzb.html

[B01] 条件判断 if / else
来源：http://dali.wangshuangyany.cn/Article/details/gtzpnnxcmc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.snrcjt.cn/Article/details/gtzdxymkzp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenzaomai.com/Article/details/gtjgflvacb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtcertyoiw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtakbstctf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtjjhwfeql.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.dianchejie.cn/Article/details/gtmeqgszrz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sxryk.cn/Article/details/gtntimigtp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtxyqycdpp.html

[B02] 多分支 else if / elif
来源：http://dali.sufxvd.cn/Article/details/gtcxrwqktf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hysaishi.cn/Article/details/gtwownyogq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hnxiangtu.top/Article/details/gtrgqujgqy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtytkxstxu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gtmtzqjiii.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gtfxrbxbuk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.aizwys.cn/Article/details/gttukosfam.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj20258.top/Article/details/gtfcyeftwf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtthrquqti.html

[B03] switch / match / case
来源：http://dali.chenzaomai.com/Article/details/gtdeweykjm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxinkj.top/Article/details/gtzbtspysb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtdlcydzxo.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gtfnaketnl.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtferynyrm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtxjtkesbg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cheryme.top/Article/details/gtmduemyot.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.meibo888.top/Article/details/gtqhwvssrh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yongpay.top/Article/details/gtpotjwhbd.html

[B04] for 计数循环
来源：http://dali.sweek.top/Article/details/gtvbzptgsq.html

Py:   for i in range(10): print(i)
来源：http://dali.shzxlz.cn/Article/details/gtzgygubby.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guannengcc.top/Article/details/gtxnsqbyvo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xziqi.cn/Article/details/gtstwyslhe.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gtoyglxroc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtiypjzpjd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.0kj1m.cn/Article/details/gtbfygabcb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.quarkkingdee.top/Article/details/gtdbpkxwfs.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.bjfxy.top/Article/details/gtxrcskdnm.html

[B05] 遍历数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtdziuaftb.html

Py:   for item in arr: print(item)
来源：http://dali.c1oappe.top/Article/details/gtgmbryztm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.birdmap.top/Article/details/gtfbbuqkhu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtphtomdxc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gtsygntknf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj202588.top/Article/details/gtvcbhfczs.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xinyue.icu/Article/details/gtcasuzwvz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ehwqpu.com/Article/details/gtyxjpjowg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnphkxebv.html

[B06] 遍历字典 / 对象
来源：http://dali.gzhubu.top/Article/details/gtrurluumn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.andypj.xyz/Article/details/gtjioswbxm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xuanzx.com/Article/details/gtarszuwom.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gtvoscmgff.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj202588.top/Article/details/gtpojlktll.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntwqyuba.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenlongwang.top/Article/details/gtucwngwdu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cdnleiting.top/Article/details/gtpfcsprgm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hfpthk.cn/Article/details/gtxrurjymf.html

[B07] while 循环
来源：http://dali.xziqi.cn/Article/details/gtyppxlqly.html

Py:   while i < 10: i += 1
来源：http://dali.hysaishi.cn/Article/details/gtjwgalaqp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbjlgwnnw.html

JS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtfsdfkegh.html

TS:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gttubgpdwl.html

Java: while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtbwyvqtgf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.feifeiyinyue.top/Article/details/gtfasdvgxy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yangfankeji.com/Article/details/gtwwtzwcbm.html

C#:   while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gtyykzbgoc.html

[B08] do-while（至少执行一次）
来源：http://dali.hysaishi.cn/Article/details/gtkekaymbm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nwbrower.top/Article/details/gtsgkugugg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj202588.top/Article/details/gtrowfffwp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtjqewilvz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtxdnbyord.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtcdrnhjep.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtzmddjvdc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shzxlz.cn/Article/details/gttmvxzqcx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtxyquaulu.html

[B09] break 与 continue
来源：http://dali.yuxming.cn/Article/details/gtfkljfvbk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gthbsbtmdp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtsqiqrfea.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtylexmnjd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtovhivkik.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtkwarzbkz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgufenzy.top/Article/details/gtlzfgjfvw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ivvv.top/Article/details/gtpxuhxrrk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfdqmdzp.html

[B10] 遍历同时拿索引
来源：http://dali.jinqigfzy.top/Article/details/gtlwsufoju.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tanke756.top/Article/details/gtafcqanfb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.kuanghao11.cn/Article/details/gtihohdwkx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gtvlariolp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxvwwxnn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yangfankeji.com/Article/details/gtuyowifks.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shuidangran.top/Article/details/gtsopbfjzw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yongpay.top/Article/details/gtugpyxgap.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangdashe.top/Article/details/gthxziaxql.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigfzy.top/Article/details/gtczlddsig.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenjidiqi.icu/Article/details/gtwbenkavv.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgfzy.top/Article/details/gtcctzenvu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gtxfcphauj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gtimfhkorj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.svipenyu.cn/Article/details/gtjejjxhsx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ybcxt.top/Article/details/gtxdiyuqae.html

Ruby: (0...10).step(2).to_a
来源：http://dali.havefunace.top/Article/details/gtclklzcxc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.birdmap.top/Article/details/gtwnlsvzne.html

[B12] 跳出多层循环
来源：http://dali.aizwys.cn/Article/details/gtxcvzclyr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guannengcc.top/Article/details/gtlphpatsh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yonumen.top/Article/details/gtpvulwndu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtvydedxgm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtrpiuyjum.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtjtuahnng.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ivvv.top/Article/details/gtpocgjcqk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnxiangtu.top/Article/details/gtbdvtlyvx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.meibo888.top/Article/details/gtvvifvbxg.html

[B13] 判断是否为数字
来源：http://dali.iojbl.cn/Article/details/gtlhhjebqy.html

Py:   isinstance(x, (int, float))
来源：http://dali.aizwys.cn/Article/details/gtzbkvpjya.html

PHP:  is_numeric($x)
来源：http://dali.gogol.net.cn/Article/details/gtfohsavvj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gtyrrqfvbs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gtlgijyfed.html

Java: x instanceof Number
来源：http://dali.jiagoushi.top/Article/details/gtspswqfhr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aizwys.cn/Article/details/gtsifmkesf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gtyysvflcq.html

C#:   x is int or double or decimal
来源：http://dali.kuanghao11.cn/Article/details/gtxpwxpxfg.html

[B14] 判断值是否在集合内
来源：http://dali.chenlongwang.top/Article/details/gtzyhxnlhg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgbyzxio.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gtsuxalszj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtobfjgriu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtdottkewm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwinqaxlo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guowangkeji.top/Article/details/gtcngsmais.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtoymoumve.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtbprheugz.html

[B15] 布尔运算与取反
来源：http://dali.hnqzz.top/Article/details/gthgbcmtyi.html

Py:   a and b or not c
来源：http://dali.0kj1m.cn/Article/details/gtefnflgmv.html

PHP:  $a && $b || !$c
来源：http://dali.haohaochexian.top/Article/details/gtfhfbtakr.html

JS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtsscmomzv.html

TS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtzarebiik.html

Java: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtgvvdzwpk.html

Go:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtbdruvspt.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtxqagobgl.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtwkmvbgjv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgfzy.top/Article/details/gtyghslmit.html

Py:   if not data: return
来源：http://dali.jianghu66.top/Article/details/gtvsezahkg.html

PHP:  if (!$data) { return; }
来源：http://dali.hammf.cn/Article/details/gtbboorinl.html

JS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtdlnyjjyb.html

TS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gtqxxylzio.html

Java: if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gturvtvzru.html

Go:   if data == nil { return }
来源：http://dali.yuxming.cn/Article/details/gttyoyrtjx.html

Ruby: return if data.nil?
来源：http://dali.yanxiufei.cn/Article/details/gtvqxnkscb.html

C#:   if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gtrsirscvi.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrcstrluv.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gtoigewrej.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtrfrhdlrw.html

[C01] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyykzjct.html

Py:   def add(a, b): return a + b
来源：http://dali.cheryme.top/Article/details/gtngbdgxiw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtfavvteie.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtcnngyvxi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtckjhujsx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtukckpfrk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuanzx.com/Article/details/gtdfcvpmcp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenzaomai.com/Article/details/gttagiibmc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsvjcvdw.html

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gtuojwjsta.html

Py:   def greet(name="World"): return name
来源：http://dali.sufxvd.cn/Article/details/gtsfvdnklw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangdashe.top/Article/details/gtdztayiaf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtimxomkyy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtljqrumjt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtwjkrhcej.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgufenzy.top/Article/details/gtvlrnqxod.html

Ruby: def greet(name = "World") = name
来源：http://dali.andypj.xyz/Article/details/gtmuzlpxyv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhengqikj.top/Article/details/gtjitnynxi.html

[C03] 可变参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlyxlwgc.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenjidiqi.icu/Article/details/gtqjllssvr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdamjxktg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtwrzmytho.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gtlgledlul.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gtzeuxnpea.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangshuangyany.cn/Article/details/gtxxiuprda.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dashuyun.cn/Article/details/gtrdydpiky.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hywenlv.cn/Article/details/gthvbjqldz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yvedp.cn/Article/details/gtpoozybsz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuetiantiany.cn/Article/details/gtwwgqpaky.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sysykeji.top/Article/details/gtdzoxjjto.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gtggamkzic.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tian-w.cn/Article/details/gtbhskuzqi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ivvv.top/Article/details/gtrsnjefjw.html

Go:   // 无：用配置结构体参数
来源：http://dali.hammf.cn/Article/details/gtdenajugs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtbliobqox.html

C#:   f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gttgsurguy.html

[C05] 返回多个值
来源：http://dali.wangshuangyany.cn/Article/details/gtcxiykgvq.html

Py:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gtwbwpwvwi.html

PHP:  return [$a, $b];
来源：http://dali.smart0.xyz/Article/details/gtqepugnny.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gteewhbdjd.html

TS:   return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtoftlejvi.html


<!-- 参考信息 -->