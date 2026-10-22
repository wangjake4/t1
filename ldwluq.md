代发 wailian999

[A14] 注释写法
来源：http://dali.yongpay.top/Article/details/gtjjrvpovs.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yonumen.top/Article/details/gtvhmtkssh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtebxykllz.html

JS:   // 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gtwnvlllsf.html

TS:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gtzxpibgar.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyqtxvfl.html

Go:   // 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gtjjlcnvdg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yangfankeji.com/Article/details/gtndfkisoi.html

C#:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtnevtrdaf.html

[A15] 空值判断与默认值
来源：http://dali.nwbrower.top/Article/details/gtexgggzwn.html

Py:   value = data or "默认值"
来源：http://dali.guannengcc.top/Article/details/gtlnibpgkg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.wangdashe.top/Article/details/gtbvtpvlty.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhiwuduotai.top/Article/details/gtarqvzamq.html

TS:   const value = data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gtbghynnnn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xinyue.icu/Article/details/gtoeudmrwi.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yonumen.top/Article/details/gtruvlwafp.html

Ruby: value = data || "默认值"
来源：http://dali.hywenlv.cn/Article/details/gtnygydjmf.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhongyouzk.top/Article/details/gtkwrjbayf.html

[A16] 真假值判断规则
来源：http://dali.kuanghao11.cn/Article/details/gtlujjusik.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.9152youxi.cn/Article/details/gtbdlessmi.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jianghu66.top/Article/details/gtwwbyosmk.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sweek.top/Article/details/gtrrbuttie.html

TS:   if (!x) {}
来源：http://dali.pycfn.com/Article/details/gtfvimlqtf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shzxlz.cn/Article/details/gtelqvglpy.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsthkqkaa.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gtoddpbvzp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ydzc1.top/Article/details/gtpcdfxvyv.html

[A17] 位运算
来源：http://dali.yj20258.top/Article/details/gtjxrarsax.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gtxmrerodg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnspdcauj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtsgixleoz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gteauerifv.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtgpvgtmgq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtjljibzfa.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtckzinnxh.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gthwbsgape.html

[A18] 字符与 ASCII 码互转
来源：http://dali.tanke756.top/Article/details/gtycvxkfax.html

Py:   ord("A"); chr(65)
来源：http://dali.xinyue.icu/Article/details/gtbbnwfbdi.html

PHP:  ord("A"); chr(65)
来源：http://dali.ppjwa.cn/Article/details/gtfsgjgooi.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xylfe.cn/Article/details/gtaizzpbmt.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.quarkkingdee.top/Article/details/gtnykhwoin.html

Java: (int) 'A'; (char) 65
来源：http://dali.jiagoushi.top/Article/details/gtskqywgyg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zdqjudy.top/Article/details/gtkvqwoyue.html

Ruby: "A".ord; 65.chr
来源：http://dali.nanxuanxn.top/Article/details/gtgkwhbhgj.html

C#:   (int)'A'; (char)65
来源：http://dali.yj20258.top/Article/details/gthgmdozuy.html

[A19] 交换两个变量
来源：http://dali.tanke756.top/Article/details/gtahadgtda.html

Py:   a, b = b, a
来源：http://dali.zhongyouzk.top/Article/details/gtoilxanvm.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.chenlongwang.top/Article/details/gtnynhlchp.html

JS:   [a, b] = [b, a];
来源：http://dali.gotoacloud.top/Article/details/gtilklvpww.html

TS:   [a, b] = [b, a];
来源：http://dali.tianlin.xyz/Article/details/gtyvucojzj.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhoulong.xyz/Article/details/gtdvukdvxi.html

Go:   a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gtdlzgxjux.html

Ruby: a, b = b, a
来源：http://dali.ydzc1.top/Article/details/gtjzmzslpa.html

C#:   (a, b) = (b, a);
来源：http://dali.dashuyun.cn/Article/details/gtjgeotgdb.html

[A20] 读取标准输入
来源：http://dali.kuanghao11.cn/Article/details/gtdhcgokjc.html

Py:   name = input("请输入：")
来源：http://dali.xuanzx.com/Article/details/gtitrrlhoh.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xinyue.icu/Article/details/gtwyoaruif.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwiakiqp.html

TS:   // Node.js：readline 模块
来源：http://dali.hongshengwenyu.top/Article/details/gthvxpmxpb.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.sxryk.cn/Article/details/gtdbpazphw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.dashuyun.cn/Article/details/gtwgnkddwg.html

Ruby: gets.chomp
来源：http://dali.pengpengdd.cyou/Article/details/gtmsbsjgva.html

C#:   Console.ReadLine();
来源：http://dali.quarkkingdee.top/Article/details/gtwcntynaw.html

[A21] 保留指定小数位输出
来源：http://dali.yuanzhike.top/Article/details/gtimgvnrrm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xuanzx.com/Article/details/gtltszoshs.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.chenjidiqi.icu/Article/details/gtlhybxdwc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gtlbcvjruo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gtvyforkfo.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gtprybyrvd.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gttvgraumu.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gtmiadmfyk.html

C#:   3.14159.ToString("F2")
来源：http://dali.bjfxy.top/Article/details/gtmdxizpys.html

[A22] 获取字符串长度
来源：http://dali.pycfn.com/Article/details/gtwwtjszej.html

Py:   len(s)
来源：http://dali.jianghu66.top/Article/details/gtpeopbzru.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yangfankeji.com/Article/details/gtuakpkecy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.aibaodan.cn/Article/details/gtwwrgnyym.html

TS:   s.length
来源：http://dali.sufxvd.cn/Article/details/gtgxwigtlu.html

Java: s.length()
来源：http://dali.ppjwa.cn/Article/details/gtplzjhqpy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shzxlz.cn/Article/details/gtnikgebah.html

Ruby: s.length
来源：http://dali.hfpthk.cn/Article/details/gtwyulniuf.html

C#:   s.Length
来源：http://dali.jiagoushi.top/Article/details/gtyxjpwfly.html

[A23] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtkixbkycf.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.mhx1999.top/Article/details/gtiaowavrg.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.kuanghao11.cn/Article/details/gtexlufrja.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gtuqocnkev.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zdqjudy.top/Article/details/gtihdbyujm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.andypj.xyz/Article/details/gtlluucssb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.bjfxy.top/Article/details/gtyyjwwwsq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gtkxzwsobj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhixingplan.top/Article/details/gttnvfspdf.html

[A24] 去除首尾空白
来源：http://dali.guowangkeji.top/Article/details/gtyihiuqiv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.havefunace.top/Article/details/gturetjvas.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gzhubu.top/Article/details/gtaxzugwin.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.aizwys.cn/Article/details/gtkulycnpv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yongpay.top/Article/details/gtyxcpagmt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj202588.top/Article/details/gtzhqahied.html

Go:   strings.TrimSpace(s)
来源：http://dali.gaohongyu789.top/Article/details/gtcmozxwuw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yongpay.top/Article/details/gtollqrysx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gtslapicsg.html

[A25] 字符串比较
来源：http://dali.cheryme.top/Article/details/gtndupqsao.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jqgufenzy.top/Article/details/gtcfdmnxcp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj20258.top/Article/details/gtfwjtnyzv.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.havefunace.top/Article/details/gtkjorcnbq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgelwdrs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbogkgbfq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhixingplan.top/Article/details/gtvwhksase.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfspnbdv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cashguo.top/Article/details/gtkhxsynna.html

[A26] 类型转换总览
来源：http://dali.dashuyun.cn/Article/details/gtmxwrenqy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.quarkkingdee.top/Article/details/gtiqfarmie.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shangyingyoupin.top/Article/details/gtasbynqzr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.pengpengdd.cyou/Article/details/gtbmpmeans.html

TS:   Number() String() Boolean() x as number
来源：http://dali.guannengcc.top/Article/details/gtxpturbga.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrvnjjpk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ybcxt.top/Article/details/gtjkpaquea.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.kuanghao11.cn/Article/details/gtnwjoluek.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefhpezzs.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtvqgrucwy.html

B. 流程控制
来源：http://dali.snrcjt.cn/Article/details/gtsrjdqmyh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtcmbrswwv.html

[B01] 条件判断 if / else
来源：http://dali.bjfxy.top/Article/details/gtorodaskx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhengqikj.top/Article/details/gtgihoqnfp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zdqjudy.top/Article/details/gtrugudrai.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtrrlnzlac.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gtmcjgvrof.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrwfmluh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuxming.cn/Article/details/gtsrpjvkor.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jlsjyb.cn/Article/details/gtzsqfjitn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gtdqqozgch.html

[B02] 多分支 else if / elif
来源：http://dali.smart0.xyz/Article/details/gtqkcjxqrs.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangdashe.top/Article/details/gtwqpfgvms.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.aibaodan.cn/Article/details/gtsgihtecb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gtpiauvslj.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtognpshmc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gtgdhrphto.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jiagoushi.top/Article/details/gtepmwylur.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ydzc1.top/Article/details/gtlntrmhyx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtwuuqkclk.html

[B03] switch / match / case
来源：http://dali.feifeiyinyue.top/Article/details/gtxcxnkvdo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yonumen.top/Article/details/gtoibxyqwr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzexafyc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gtfhigxcfu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gtaxnmfkmi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtrxnfvuek.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jiagoushi.top/Article/details/gtzfnvsldy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwpgnsdq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.mhx1999.top/Article/details/gtlvqijcxk.html

[B04] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gtsotiehhb.html

Py:   for i in range(10): print(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqlmgrkt.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yuxming.cn/Article/details/gtfosopitg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxinkj.top/Article/details/gtuhyvymcv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gtewuscims.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hammf.cn/Article/details/gtiaynazvn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.havefunace.top/Article/details/gtwtqwemit.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gtgspzcsrb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xuanzx.com/Article/details/gtvimbhnsf.html

[B05] 遍历数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gtmninlxfe.html

Py:   for item in arr: print(item)
来源：http://dali.xziqi.cn/Article/details/gtasujvitu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xylfe.cn/Article/details/gthdrgdzzi.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.316326.xyz/Article/details/gthwwznnyr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gtvclushwt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gzhubu.top/Article/details/gtafvdhrdo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xuetiantiany.cn/Article/details/gttsnkbrnc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hongshengwenyu.top/Article/details/gtdexjoswx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenlongwang.top/Article/details/gtxwqxgrwa.html

[B06] 遍历字典 / 对象
来源：http://dali.cheryme.top/Article/details/gtzhfaehim.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gotoacloud.top/Article/details/gtjwsazptt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hammf.cn/Article/details/gtvnrvnhca.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gtbxudmjjv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gtochpbgjy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.havefunace.top/Article/details/gttonfkoul.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hfpthk.cn/Article/details/gttixpficf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yueranfly.top/Article/details/gtggyhpiar.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmsexnpqw.html

[B07] while 循环
来源：http://dali.hysaishi.cn/Article/details/gtglfnodxd.html

Py:   while i < 10: i += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsbxdmdr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgfzy.top/Article/details/gtnlhhnqwx.html

JS:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtbmidphps.html

TS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtagypggpd.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtpmulvvpg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cheryme.top/Article/details/gttlehtryh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shuidangran.top/Article/details/gtkoywoxxq.html

C#:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvjgbbndv.html

[B08] do-while（至少执行一次）
来源：http://dali.zhixingplan.top/Article/details/gtrsmcasrx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.svipenyu.cn/Article/details/gtjdpybuhm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtaemxsnip.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtlqkrbsdl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtcbtfvkxv.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazidbkgf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwpykejn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jlsjyb.cn/Article/details/gtmitjsmsx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtglrkwljf.html

[B09] break 与 continue
来源：http://dali.gotoacloud.top/Article/details/gtmgjnwhov.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nwbrower.top/Article/details/gtnroobkic.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtzyxqdyvt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtrdtrfzgi.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtvagyjaaa.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtdveactyl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.redwolf501.top/Article/details/gtwpnpzcgg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangdashe.top/Article/details/gteogumyxb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtxoukvevu.html

[B10] 遍历同时拿索引
来源：http://dali.yj202588.top/Article/details/gtryllglkj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gtmorxjqjq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmkptupl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gtncziuqfe.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gtimzxnvqi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xziqi.cn/Article/details/gthzzhrvis.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fengsongda.top/Article/details/gtqfhqsyld.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhcusnjd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.iojbl.cn/Article/details/gtdibmiskj.html

[B11] 生成数字序列 / 区间
来源：http://dali.hongshengwenyu.top/Article/details/gtfsdmjaze.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuanzx.com/Article/details/gtlxdrbwcu.html

PHP:  range(0, 10, 2);
来源：http://dali.sweek.top/Article/details/gtfvmpqakx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gtuklnflrb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtkkwqibjl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.smart0.xyz/Article/details/gthprwbyos.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gtntxtmkhx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gtsnztvivf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jiagoushi.top/Article/details/gtgtlpxzde.html

[B12] 跳出多层循环
来源：http://dali.jiagoushi.top/Article/details/gtnxabwzew.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jlsjyb.cn/Article/details/gtgopsdmba.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtehpyftxq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtvqplorlv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmiqtdyo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtsmgoywkk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.haohaochexian.top/Article/details/gtoktaowmb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gtygxuouft.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.vqdsnc.cn/Article/details/gtqbirepmz.html

[B13] 判断是否为数字
来源：http://dali.ehwqpu.com/Article/details/gtswbfrxqi.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj202588.top/Article/details/gtbnjwokmd.html

PHP:  is_numeric($x)
来源：http://dali.hfpthk.cn/Article/details/gtrazqbmve.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gtiiayddfh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtpsrehmzy.html

Java: x instanceof Number
来源：http://dali.cdnleiting.top/Article/details/gtovgxmwmu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gtiaodqquv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guannengcc.top/Article/details/gtxcccrixx.html

C#:   x is int or double or decimal
来源：http://dali.zhengqikj.top/Article/details/gtbzfuuwjx.html

[B14] 判断值是否在集合内
来源：http://dali.feifeiyinyue.top/Article/details/gtyilcxzrt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258.top/Article/details/gtqejrcqzw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cqqwz.cn/Article/details/gtirbxltkm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtlnecgjuk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gtxgtmujyx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuxming.cn/Article/details/gtqhjfoymz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shzxlz.cn/Article/details/gtjycfkkfw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gtfzkcvezg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtlbnzdtqx.html

[B15] 布尔运算与取反
来源：http://dali.andypj.xyz/Article/details/gtptmocbvw.html

Py:   a and b or not c
来源：http://dali.yj202588.top/Article/details/gttsqbqfnq.html

PHP:  $a && $b || !$c
来源：http://dali.tianlin.xyz/Article/details/gtytthyhfn.html

JS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtxhdppehu.html

TS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtvmooxjzm.html

Java: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtexailelh.html

Go:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtwmrxujft.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtbnuwvzjd.html

C#:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtfuwyhkzl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbaldjbw.html

Py:   if not data: return
来源：http://dali.nanxuanxn.top/Article/details/gtedhntbcv.html

PHP:  if (!$data) { return; }
来源：http://dali.ehwqpu.com/Article/details/gtxlxmpvrk.html

JS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqnzjygi.html

TS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gtmhpvhgvg.html

Java: if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gtlbwewpmd.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gtmxjssztc.html

Ruby: return if data.nil?
来源：http://dali.hysaishi.cn/Article/details/gtgvnxjlgb.html

C#:   if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtfbbhswjf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtppzozfwy.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gtxrugleen.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtebqqbkgp.html

[C01] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtfugzrxbw.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gtzeuqgzta.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtagzkorpj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrmysxgxk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtqvgintpn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtmgkhrgfi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.havefunace.top/Article/details/gtuanedlax.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gttflmsynr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtjiqgwqpi.html

[C02] 默认参数
来源：http://dali.snrcjt.cn/Article/details/gtxadroqyu.html

Py:   def greet(name="World"): return name
来源：http://dali.ydzc1.top/Article/details/gtiuzqxklk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gtbnobfzaa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtdcsjqhjk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtfsqmnyzo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.haohaochexian.top/Article/details/gtglaklbeb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gtewzrvkox.html

Ruby: def greet(name = "World") = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpdedwoe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigufen.top/Article/details/gtprbgoefe.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gtvcrcwkaz.html

Py:   def total(*args): return sum(args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwpfwcse.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cdnleiting.top/Article/details/gtuhsaggwc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gttnbwjodd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtxriigbsw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tian-w.cn/Article/details/gtxfilprys.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.havefunace.top/Article/details/gtgmleenvk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daria6918.cn/Article/details/gtxuwttcgh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aizwys.cn/Article/details/gttgfknikz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gtuzohhpid.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gtieyessmw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhoulong.xyz/Article/details/gtcgsdqzbl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtjzybltww.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gtipynxivk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gaohongyu789.top/Article/details/gtrckqwosw.html


<!-- 参考信息 -->