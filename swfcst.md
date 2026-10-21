代发 wailian999

Java: "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtqrwnivsz.html

Go:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtxldiqjwh.html

Ruby: "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gteoresnxk.html

C#:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gtjxcwbjiw.html

[A14] 注释写法
来源：http://dali.cqqwz.cn/Article/details/gtjojahfnk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.meibo888.top/Article/details/gtzvwiyosi.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.tanke756.top/Article/details/gtshkrqkzg.html

JS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtsxnyekin.html

TS:   // 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gtbeshgovt.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xuetiantiany.cn/Article/details/gtgiizdbys.html

Go:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gtjxxuzecv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sweek.top/Article/details/gtugfpvhba.html

C#:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gtcucthcxg.html

[A15] 空值判断与默认值
来源：http://dali.316326.xyz/Article/details/gtwezyfcmt.html

Py:   value = data or "默认值"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxxdclki.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhiwuduotai.top/Article/details/gtadnstpak.html

JS:   const value = data ?? "默认值";
来源：http://dali.gzhubu.top/Article/details/gtrmplxpoe.html

TS:   const value = data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gtbbazjzco.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.birdmap.top/Article/details/gtuqptybrp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cashguo.top/Article/details/gtnlrjnjpv.html

Ruby: value = data || "默认值"
来源：http://dali.zhiwuduotai.top/Article/details/gtxybzcuvm.html

C#:   var value = data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gtwptwcecq.html

[A16] 真假值判断规则
来源：http://dali.jyoumei.cn/Article/details/gtlsrdebps.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinqigufen.top/Article/details/gtrqalwikw.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yj202588.top/Article/details/gtfmkxljke.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkyzjmvf.html

TS:   if (!x) {}
来源：http://dali.hnxiangtu.top/Article/details/gttwzjjhpd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.chenlongwang.top/Article/details/gtnjcwydai.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.dashuyun.cn/Article/details/gtqlsrgboc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.pengpengdd.cyou/Article/details/gtpsjcidnx.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gthztcgowm.html

[A17] 位运算
来源：http://dali.ppjwa.cn/Article/details/gthvasvjvh.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtlyxydhsv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtxciuaeen.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkfozxkz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtyxvrnjtw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnfurzzm.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtdywgnhti.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtfcnsrrnv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtvpycbcna.html

[A18] 字符与 ASCII 码互转
来源：http://dali.kuanghao11.cn/Article/details/gtiuzkpucf.html

Py:   ord("A"); chr(65)
来源：http://dali.cashguo.top/Article/details/gtryzmersh.html

PHP:  ord("A"); chr(65)
来源：http://dali.shangyingyoupin.top/Article/details/gtboclaaau.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.c1oappe.top/Article/details/gtzolyzpvv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tanke756.top/Article/details/gtmmnlwmdc.html

Java: (int) 'A'; (char) 65
来源：http://dali.jqgufenzy.top/Article/details/gtmbprxpbc.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gogol.net.cn/Article/details/gtunyboriv.html

Ruby: "A".ord; 65.chr
来源：http://dali.pycfn.com/Article/details/gtykreqkkv.html

C#:   (int)'A'; (char)65
来源：http://dali.daria6918.cn/Article/details/gthltebqpg.html

[A19] 交换两个变量
来源：http://dali.mhx1999.top/Article/details/gtcyqpbkoh.html

Py:   a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gtzbsbeqhe.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gaohongyu789.top/Article/details/gtzvzyjkbu.html

JS:   [a, b] = [b, a];
来源：http://dali.zhiwuduotai.top/Article/details/gtyarsybuc.html

TS:   [a, b] = [b, a];
来源：http://dali.shanyushiyangtech.top/Article/details/gtvutkakqe.html

Java: int t = a; a = b; b = t;
来源：http://dali.xuanzx.com/Article/details/gtnagoqssb.html

Go:   a, b = b, a
来源：http://dali.bjfxy.top/Article/details/gttoegsape.html

Ruby: a, b = b, a
来源：http://dali.shuidangran.top/Article/details/gtpoxlummj.html

C#:   (a, b) = (b, a);
来源：http://dali.jinqigfzy.top/Article/details/gtsqplirck.html

[A20] 读取标准输入
来源：http://dali.xinyue.icu/Article/details/gtwhqbdswa.html

Py:   name = input("请输入：")
来源：http://dali.zhixingplan.top/Article/details/gtxndaijjc.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.nanxuanxn.top/Article/details/gtuwumurzw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.wangdashe.top/Article/details/gtfptwjncw.html

TS:   // Node.js：readline 模块
来源：http://dali.daxiang520.top/Article/details/gtounjgsmd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zdqjudy.top/Article/details/gtijzychfd.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhengqikj.top/Article/details/gturxydiai.html

Ruby: gets.chomp
来源：http://dali.havefunace.top/Article/details/gtqmxvjevn.html

C#:   Console.ReadLine();
来源：http://dali.ppjwa.cn/Article/details/gtpaxceeku.html

[A21] 保留指定小数位输出
来源：http://dali.yangfankeji.com/Article/details/gtdrfzytkz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cdnleiting.top/Article/details/gtwdaavvje.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yangfankeji.com/Article/details/gtwzgfvciy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gtcipueccv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gtuhldpwmp.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gtqpevwmtc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrhydacw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gtqgjgtbzi.html

C#:   3.14159.ToString("F2")
来源：http://dali.shuidangran.top/Article/details/gtifcnnwhi.html

[A22] 获取字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtxyvtqxkc.html

Py:   len(s)
来源：http://dali.yvedp.cn/Article/details/gtcvfpdmfa.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.dianchejie.cn/Article/details/gtiuvjyelj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xinyue.icu/Article/details/gtpnifswkr.html

TS:   s.length
来源：http://dali.chenzaomai.com/Article/details/gtuflpxqqs.html

Java: s.length()
来源：http://dali.hammf.cn/Article/details/gtukdbqnkj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.iojbl.cn/Article/details/gtrdtjnqlh.html

Ruby: s.length
来源：http://dali.hnqzz.top/Article/details/gtyjsgancv.html

C#:   s.Length
来源：http://dali.zhixingplan.top/Article/details/gtghcvoyup.html

[A23] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtjunbvbex.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ehwqpu.com/Article/details/gtuuuucmha.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cheryme.top/Article/details/gtazbnqyxe.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yanxiufei.cn/Article/details/gtjihvxooe.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gtbqdqopmg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cheryme.top/Article/details/gtfwillyag.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.svipenyu.cn/Article/details/gtdurkienj.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ivvv.top/Article/details/gtsyhenyvs.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hnqzz.top/Article/details/gtsjjmbmrm.html

[A24] 去除首尾空白
来源：http://dali.jqgufenzy.top/Article/details/gtbnaxrfzv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.smart0.xyz/Article/details/gtrowcajgf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cdnleiting.top/Article/details/gtwuwyknoi.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hongshengwenyu.top/Article/details/gtfwwaucxg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cashguo.top/Article/details/gtfmfrdcpk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hfpthk.cn/Article/details/gtjmzadfac.html

Go:   strings.TrimSpace(s)
来源：http://dali.cdnleiting.top/Article/details/gtkxsyhbsp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jiagoushi.top/Article/details/gtxfewptpa.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.0kj1m.cn/Article/details/gtydfswqni.html

[A25] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gtrtmpivob.html

Py:   s1 == s2; s1 != s2
来源：http://dali.guannengcc.top/Article/details/gtrsexjqsp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.andypj.xyz/Article/details/gtlxoxdtae.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigfzy.top/Article/details/gtiuajxeal.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fzhhl.top/Article/details/gtwizgbrul.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.mhx1999.top/Article/details/gtupznvgdv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.svipenyu.cn/Article/details/gtzwgdjpwb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.quarkkingdee.top/Article/details/gtypwkniod.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jyoumei.cn/Article/details/gthdtjmwyc.html

[A26] 类型转换总览
来源：http://dali.jiagoushi.top/Article/details/gtusxqawnf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.meibo888.top/Article/details/gtxyppswid.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hammf.cn/Article/details/gtydgxswdr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ppjwa.cn/Article/details/gtkvdcwfyi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yueranfly.top/Article/details/gtpvrizaaw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gtkvghpfck.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.feifeiyinyue.top/Article/details/gtmnuvacue.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtddhxyegt.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sweek.top/Article/details/gtuitcvqxi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcxfonjmn.html

B. 流程控制
来源：http://dali.dianchejie.cn/Article/details/gtiotuzutc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxctfzokc.html

[B01] 条件判断 if / else
来源：http://dali.snrcjt.cn/Article/details/gtnsawijnd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258888.top/Article/details/gtmtsayvqh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jiagoushi.top/Article/details/gtlkloqoxt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gtoxraztym.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gtzqyoxqwm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtehcpmzzo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258888.top/Article/details/gtuzjbkoaz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hnqzz.top/Article/details/gtazcyivbi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtutuhqaem.html

[B02] 多分支 else if / elif
来源：http://dali.guannengcc.top/Article/details/gtfubquapn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sxryk.cn/Article/details/gtrkzzbifj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xziqi.cn/Article/details/gtxiqozwlq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gthsblhyqx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxhtiodg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gtnzxnjzqe.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gtbeazzcyg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hammf.cn/Article/details/gtjyaawmlp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gtcobdvexb.html

[B03] switch / match / case
来源：http://dali.chenlongwang.top/Article/details/gtgdydspnu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yanxiufei.cn/Article/details/gtgsvxoyhr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtgqffgamo.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtvvmcocel.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtvkxjdhiu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gtkxzxsbmw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gzhubu.top/Article/details/gtsoiezxot.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fengsongda.top/Article/details/gtfbewyyky.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gttafuvqyt.html

[B04] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtfupwtywm.html

Py:   for i in range(10): print(i)
来源：http://dali.zycfv.cn/Article/details/gtzihfqwzg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cashguo.top/Article/details/gtjzcinswp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.haohaochexian.top/Article/details/gtobybczlk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtdwpdrfhb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.andypj.xyz/Article/details/gtjbkvrapd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hfpthk.cn/Article/details/gtkrauiglg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigfzy.top/Article/details/gtpvwqyjlx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.haohaochexian.top/Article/details/gtsevdwbln.html

[B05] 遍历数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gtroilholl.html

Py:   for item in arr: print(item)
来源：http://dali.hnxiangtu.top/Article/details/gtsowucfsw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.smart0.xyz/Article/details/gtmmxumegh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gtzckudbuq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gtreixgumt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtdybkphuo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gogol.net.cn/Article/details/gtakgvskxg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.pengpengdd.cyou/Article/details/gtiougeljg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jianghu66.top/Article/details/gtsxamgmnd.html

[B06] 遍历字典 / 对象
来源：http://dali.cdnleiting.top/Article/details/gtivymhtht.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlfhniaq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgfzy.top/Article/details/gtklwwzxrs.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zycfv.cn/Article/details/gtvzamdmck.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigufen.top/Article/details/gtlraemrro.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.haohaochexian.top/Article/details/gtmbzopisd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenjidiqi.icu/Article/details/gtpkmrzzpa.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ivvv.top/Article/details/gteorudnxy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhengqikj.top/Article/details/gthbfomtdf.html

[B07] while 循环
来源：http://dali.xuetiantiany.cn/Article/details/gtsfeqdzkk.html

Py:   while i < 10: i += 1
来源：http://dali.smart0.xyz/Article/details/gtvnxlrfro.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtisxwtwjx.html

JS:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtqivjjzad.html

TS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtrdxtbnbo.html

Java: while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtklntngnl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenjidiqi.icu/Article/details/gtazywvhnh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gaohongyu789.top/Article/details/gtflwagigo.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtoepfgifn.html

[B08] do-while（至少执行一次）
来源：http://dali.aibaodan.cn/Article/details/gtnfdyephv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenlongwang.top/Article/details/gtfvupgpyu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guannengcc.top/Article/details/gtbendzpdl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtxbfhvpoh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrxcmgqi.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtalubqovl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtzffphsmm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ybcxt.top/Article/details/gthgyovvjl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtxuwvcsyo.html

[B09] break 与 continue
来源：http://dali.fzhhl.top/Article/details/gtverydnte.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pycfn.com/Article/details/gtymtgcqsw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtlrxuumxn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtwknsqcas.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpmkrticu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzeekatjx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cashguo.top/Article/details/gtumrbcxya.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.bjfxy.top/Article/details/gtymcrlarh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtrljrqhla.html

[B10] 遍历同时拿索引
来源：http://dali.chenjidiqi.icu/Article/details/gtfehadbth.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yvedp.cn/Article/details/gtwtdkfvnz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.vqdsnc.cn/Article/details/gtnjtykinw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gtjvdflymi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gotoacloud.top/Article/details/gtmncohqkl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ydzc1.top/Article/details/gthdwgbvit.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pycfn.com/Article/details/gtybwnmarp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cashguo.top/Article/details/gtvvlgxcqo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yvedp.cn/Article/details/gtzxxyujku.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuanzhike.top/Article/details/gtkdxhpvxe.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenzaomai.com/Article/details/gtkvubgjhv.html

PHP:  range(0, 10, 2);
来源：http://dali.zhengqikj.top/Article/details/gtjixmzdzp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gtepbakcza.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gtbpthfily.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gotoacloud.top/Article/details/gthfjhzwsl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shuidangran.top/Article/details/gtkwiisnxj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryoqsaec.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuanzhike.top/Article/details/gtzvidjekk.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gttxgxwott.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhoulong.xyz/Article/details/gtaztohgrf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258.top/Article/details/gtkcvjcdvg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtkjaohwhm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gtgjhetwxa.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtmmltecwu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ehwqpu.com/Article/details/gtphnaxens.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aizwys.cn/Article/details/gtnovfzdox.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yanxiufei.cn/Article/details/gttmmkbqri.html

[B13] 判断是否为数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqgmmpyb.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gthixqliou.html

PHP:  is_numeric($x)
来源：http://dali.zdqjudy.top/Article/details/gtwcvddusx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gtjzkzhtxo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gtnsqmlnoh.html

Java: x instanceof Number
来源：http://dali.jinqigufen.top/Article/details/gtcxvkzezp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj202588.top/Article/details/gtadlqpqjl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cqqwz.cn/Article/details/gtjibzsmwk.html

C#:   x is int or double or decimal
来源：http://dali.cucudq.cn/Article/details/gtfefcigfm.html

[B14] 判断值是否在集合内
来源：http://dali.gzhubu.top/Article/details/gtxgqrnjst.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cqqwz.cn/Article/details/gtgugizyhz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.bjfxy.top/Article/details/gtchwaxiiz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtmzfzbtkm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gtgzfvnftb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvlzrkgn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jlsjyb.cn/Article/details/gtzmtikuab.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hfpthk.cn/Article/details/gtpbmqbufq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gttuornnwz.html

[B15] 布尔运算与取反
来源：http://dali.0kj1m.cn/Article/details/gtfnojbytd.html

Py:   a and b or not c
来源：http://dali.316326.xyz/Article/details/gtfyuzsiga.html

PHP:  $a && $b || !$c
来源：http://dali.shuidangran.top/Article/details/gtmvsrtmzx.html

JS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtdjvbuwdl.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtsqclrnxb.html

Java: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtshbgebkd.html

Go:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtscvmlbhd.html

Ruby: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtjlpfqddl.html

C#:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtnvgzctwi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpvgrpqq.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gtcaibsafd.html

PHP:  if (!$data) { return; }
来源：http://dali.gaohongyu789.top/Article/details/gtnesuqjhr.html

JS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gtpjkiqlfk.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gttuhcnxmu.html

Java: if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtmogannih.html

Go:   if data == nil { return }
来源：http://dali.aizwys.cn/Article/details/gtbzndgxdv.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gtkwyxeqxg.html

C#:   if (data == null) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttewljosy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtobarmmab.html

C. 函数与作用域
来源：http://dali.cdnleiting.top/Article/details/gtezmiedtz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgouwncgb.html

[C01] 定义函数
来源：http://dali.yj20258888.top/Article/details/gtsxgfuvuk.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gtxwrlvzdc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtmolqsngl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtsojvdmab.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtlxmnaegc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuchiqkzt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nwbrower.top/Article/details/gtsryljybw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigfzy.top/Article/details/gtyfegexcz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtibxxdmln.html

[C02] 默认参数
来源：http://dali.xziqi.cn/Article/details/gtysgmtipw.html

Py:   def greet(name="World"): return name
来源：http://dali.yangfankeji.com/Article/details/gtantcltey.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gtjhethjhm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtqbiuhjqr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtiiszhnly.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ybcxt.top/Article/details/gtrpcziyav.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gtvuvxlkpr.html

Ruby: def greet(name = "World") = name
来源：http://dali.havefunace.top/Article/details/gtjxlcoslk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xinyue.icu/Article/details/gtqectwdaz.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvhmmhim.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gtweptlmay.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ybcxt.top/Article/details/gtscvgueyp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gtaabyjmhz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtnzhbupba.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.smart0.xyz/Article/details/gttwvyvfvj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgufenzy.top/Article/details/gtktzykcvu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dashuyun.cn/Article/details/gtxvejpfvp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pengpengdd.cyou/Article/details/gtqwsffgfc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.redwolf501.top/Article/details/gtcsmymdme.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqgicjgh.html


<!-- 参考信息 -->