代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.yonumen.top/Article/details/gtwntapmsf.html

Py:   ord("A"); chr(65)
来源：http://dali.shangyingyoupin.top/Article/details/gttpjfgxxk.html

PHP:  ord("A"); chr(65)
来源：http://dali.shzxlz.cn/Article/details/gttqbtkxis.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hywenlv.cn/Article/details/gtdkhvbdwh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.feifeiyinyue.top/Article/details/gtbvxtflbz.html

Java: (int) 'A'; (char) 65
来源：http://dali.yj20258888.top/Article/details/gtdgjqnpzu.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinqigufen.top/Article/details/gtwkqbzvji.html

Ruby: "A".ord; 65.chr
来源：http://dali.cucudq.cn/Article/details/gtmbcazush.html

C#:   (int)'A'; (char)65
来源：http://dali.shzxlz.cn/Article/details/gtvijsfcnh.html

[A19] 交换两个变量
来源：http://dali.hfpthk.cn/Article/details/gtntpelrln.html

Py:   a, b = b, a
来源：http://dali.9152youxi.cn/Article/details/gtkyrcrvdx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.andypj.xyz/Article/details/gtrjtqyomy.html

JS:   [a, b] = [b, a];
来源：http://dali.fengsongda.top/Article/details/gtlgowdfzk.html

TS:   [a, b] = [b, a];
来源：http://dali.meibo888.top/Article/details/gtrauklwii.html

Java: int t = a; a = b; b = t;
来源：http://dali.tian-w.cn/Article/details/gtsxtfoixv.html

Go:   a, b = b, a
来源：http://dali.yj20258888.top/Article/details/gtzoabassk.html

Ruby: a, b = b, a
来源：http://dali.aizwys.cn/Article/details/gtwjhlzyyl.html

C#:   (a, b) = (b, a);
来源：http://dali.xinyue.icu/Article/details/gtgsnodgox.html

[A20] 读取标准输入
来源：http://dali.redwolf501.top/Article/details/gtzjlswngl.html

Py:   name = input("请输入：")
来源：http://dali.chenlongwang.top/Article/details/gtneamzihl.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhiwuduotai.top/Article/details/gtwcxwvbld.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.svipenyu.cn/Article/details/gtkkhjfffw.html

TS:   // Node.js：readline 模块
来源：http://dali.xylfe.cn/Article/details/gtpbaifjjf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yj20258888.top/Article/details/gtcxjgxeer.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelloeazr.html

Ruby: gets.chomp
来源：http://dali.smart0.xyz/Article/details/gtbhgwdhcf.html

C#:   Console.ReadLine();
来源：http://dali.zycfv.cn/Article/details/gtpwqmshzk.html

[A21] 保留指定小数位输出
来源：http://dali.nanxuanxn.top/Article/details/gtrmdgnpgs.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jqgfzy.top/Article/details/gthnsjrofa.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gthuuvbtbb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtlihevfmv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gtvdrfniwh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gtvqevezsa.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gtdutoposc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtigygtdvi.html

C#:   3.14159.ToString("F2")
来源：http://dali.yj202588.top/Article/details/gttfeurjcm.html

[A22] 获取字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtrmyxidme.html

Py:   len(s)
来源：http://dali.cheryme.top/Article/details/gtzapkciot.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ppjwa.cn/Article/details/gtwlbrummn.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.pycfn.com/Article/details/gtppxpnfta.html

TS:   s.length
来源：http://dali.ivvv.top/Article/details/gtoqbzcyzt.html

Java: s.length()
来源：http://dali.tian-w.cn/Article/details/gtydxlbmdi.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hysaishi.cn/Article/details/gtdzdkfvub.html

Ruby: s.length
来源：http://dali.zhoulong.xyz/Article/details/gtkyzuwhvx.html

C#:   s.Length
来源：http://dali.ehwqpu.com/Article/details/gtogdiwsoo.html

[A23] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtizekayle.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zdqjudy.top/Article/details/gtgdqtggqp.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hfpthk.cn/Article/details/gtagcxqmhw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gtucacovcj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gtyjcotqxg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guannengcc.top/Article/details/gtuombiyhf.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhengqikj.top/Article/details/gtgfvuvxlo.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gtuitlagzz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daxiang520.top/Article/details/gtbhfuujbe.html

[A24] 去除首尾空白
来源：http://dali.tanke756.top/Article/details/gtklqylwgr.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yvedp.cn/Article/details/gtysjppzmd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hnxiangtu.top/Article/details/gtoddfomyn.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gtinleiiim.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtppkuckcx.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xylfe.cn/Article/details/gtsryaiqpw.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhongyouzk.top/Article/details/gtezjjwtdk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.andypj.xyz/Article/details/gtmgtjpamt.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.iojbl.cn/Article/details/gtllgkyhrf.html

[A25] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtfocmsqit.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xuetiantiany.cn/Article/details/gtguhjalbe.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotoudkpu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.mhx1999.top/Article/details/gtiiudezvm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.smart0.xyz/Article/details/gtyfrsoaat.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtsaxxlhms.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gttxljllnm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.fzhhl.top/Article/details/gtvyiuqnvr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtxkvupoak.html

[A26] 类型转换总览
来源：http://dali.yj202588.top/Article/details/gtnkoxhwgk.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xuanzx.com/Article/details/gtkklcqghy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.wangshuangyany.cn/Article/details/gtdnmantrd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.316326.xyz/Article/details/gtwbuslkeh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tian-w.cn/Article/details/gtpydszbfx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yj20258888.top/Article/details/gteiqajwcx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfudlccxe.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jiagoushi.top/Article/details/gtrvtftfks.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yanxiufei.cn/Article/details/gtyapzeomo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvqtmcwka.html

B. 流程控制
来源：http://dali.jinqigufen.top/Article/details/gtropdmmwp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtsrricvvt.html

[B01] 条件判断 if / else
来源：http://dali.redwolf501.top/Article/details/gtqrqjmbxh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.daxiang520.top/Article/details/gtajbrzlgi.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgcalhhw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtbkvkfzgz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gtljbuwadf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtjyhzyzlu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tian-w.cn/Article/details/gtfnbupdtj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jiagoushi.top/Article/details/gtwvsmwxxd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gtmtcwiayh.html

[B02] 多分支 else if / elif
来源：http://dali.svipenyu.cn/Article/details/gtuwpfoxby.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.snrcjt.cn/Article/details/gtcjjcriyp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcnchhokq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtzypaaqws.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gtburfpkcr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtltitmcdp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsqmheaw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cqqwz.cn/Article/details/gtlbqkgwto.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gthlwbzsay.html

[B03] switch / match / case
来源：http://dali.xylfe.cn/Article/details/gtbtpoyyuz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhengqikj.top/Article/details/gtnmzvwytb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtrxndasgc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtpwollxrn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtqpwalpuq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtqfhvnuye.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tianlin.xyz/Article/details/gteilixkwb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.tianlin.xyz/Article/details/gtwnrbhtqr.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ydzc1.top/Article/details/gthjejgndn.html

[B04] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gtczocoyql.html

Py:   for i in range(10): print(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzicsrkzv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ydzc1.top/Article/details/gtcqgmekyv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqrxacfxm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrujharji.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.redwolf501.top/Article/details/gtolbtzmjy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.quarkkingdee.top/Article/details/gtxshbtpnf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shanyushiyangtech.top/Article/details/gtegthnwlo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtdomuvpov.html

[B05] 遍历数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gttxwikkcs.html

Py:   for item in arr: print(item)
来源：http://dali.hnxiangtu.top/Article/details/gthxsazonv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.wangdashe.top/Article/details/gtnkplzfxo.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbpbqchj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.9152youxi.cn/Article/details/gtliyraehv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpddcxrar.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrwktzel.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shangyingyoupin.top/Article/details/gtybmotmlf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.guowangkeji.top/Article/details/gtxoyoynfd.html

[B06] 遍历字典 / 对象
来源：http://dali.chenlongwang.top/Article/details/gtrvngrcey.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ybcxt.top/Article/details/gtfhvuddch.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.vqdsnc.cn/Article/details/gtkpunazaz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj202588.top/Article/details/gtiszxdxyi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cucudq.cn/Article/details/gtosobsdgw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.iojbl.cn/Article/details/gtvvoquxfl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.feifeiyinyue.top/Article/details/gtkknygrjw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhixingplan.top/Article/details/gtphcddjov.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hysaishi.cn/Article/details/gtefsswypa.html

[B07] while 循环
来源：http://dali.snrcjt.cn/Article/details/gtiayvetyl.html

Py:   while i < 10: i += 1
来源：http://dali.zhoulong.xyz/Article/details/gtvhtsisou.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tianlin.xyz/Article/details/gtazckntzv.html

JS:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtvjfxwdmb.html

TS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtyddrkmbk.html

Java: while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gtzotujdbx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ehwqpu.com/Article/details/gtaqjuzhfd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hnqzz.top/Article/details/gtnimrtslz.html

C#:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtspinplmu.html

[B08] do-while（至少执行一次）
来源：http://dali.sxryk.cn/Article/details/gtxobyllgl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aibaodan.cn/Article/details/gtnfdjenni.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtpgwomkvd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtlqzjzjzk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gtipycmaaq.html

Java: do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gtedtfyufq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gtsoxtjdzz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cheryme.top/Article/details/gtzlobjlbw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtkikhwuym.html

[B09] break 与 continue
来源：http://dali.cdnleiting.top/Article/details/gtvylgtepl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.iojbl.cn/Article/details/gtvpreocqd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpersaymk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtjapfwkep.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gthqgfpnuy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtfvvnihkr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gogol.net.cn/Article/details/gtwmkihsye.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cashguo.top/Article/details/gtbnzdqfdm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfldgesv.html

[B10] 遍历同时拿索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoauyysd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenlongwang.top/Article/details/gtmdegbgno.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cheryme.top/Article/details/gtlyhpzwlv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cqqwz.cn/Article/details/gtenrctpaz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gtzngquerj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.redwolf501.top/Article/details/gttmakfydl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuxming.cn/Article/details/gtaotzmxua.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhengqikj.top/Article/details/gtvmflyurf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shuidangran.top/Article/details/gtjzjydthe.html

[B11] 生成数字序列 / 区间
来源：http://dali.mhx1999.top/Article/details/gtdkztxtsu.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnqzz.top/Article/details/gtpgxopzeg.html

PHP:  range(0, 10, 2);
来源：http://dali.guowangkeji.top/Article/details/gtgsscwqvy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtgssgtqxt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gtsopqzkha.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.smart0.xyz/Article/details/gtyebchqxg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yangfankeji.com/Article/details/gtgemkwvus.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuanzhike.top/Article/details/gtmhcqxihl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gtecbpphjv.html

[B12] 跳出多层循环
来源：http://dali.hywenlv.cn/Article/details/gtehmtiopj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dianchejie.cn/Article/details/gtjfdhzfhu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.vqdsnc.cn/Article/details/gtlxfotbuf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtiwnmfsrb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gthyjkazzc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtljsoockd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.wangdashe.top/Article/details/gtwphcvmrl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.redwolf501.top/Article/details/gtyqmebtkf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yonumen.top/Article/details/gtqnfdjtqm.html

[B13] 判断是否为数字
来源：http://dali.haohaochexian.top/Article/details/gtpwdpuijx.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenlongwang.top/Article/details/gtrblzlipy.html

PHP:  is_numeric($x)
来源：http://dali.tianlin.xyz/Article/details/gtgssfeiif.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gtfrbxszay.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtvconqfof.html

Java: x instanceof Number
来源：http://dali.sxryk.cn/Article/details/gtttvucutr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangshuangyany.cn/Article/details/gtrmqwgqda.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shzxlz.cn/Article/details/gtljluibxe.html

C#:   x is int or double or decimal
来源：http://dali.nanxinkj.top/Article/details/gtbeyvjaqu.html

[B14] 判断值是否在集合内
来源：http://dali.svipenyu.cn/Article/details/gtosgecfgs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cqqwz.cn/Article/details/gtypryltpo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtvrbnnc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gtcaianzux.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtlvbnzwjv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xziqi.cn/Article/details/gtkgfbjiyn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.c1oappe.top/Article/details/gtpzdsfabs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtkuzzvwbv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtweezqnaw.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gtfmgbquch.html

Py:   a and b or not c
来源：http://dali.yj202588.top/Article/details/gttshhppyu.html

PHP:  $a && $b || !$c
来源：http://dali.birdmap.top/Article/details/gtcolwspbs.html

JS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtugktgajc.html

TS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtxysgbewr.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtohnmbfpy.html

Go:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtkbpbgeey.html

Ruby: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtajjroqyx.html

C#:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtdsovqxac.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yonumen.top/Article/details/gtixepixmy.html

Py:   if not data: return
来源：http://dali.svipenyu.cn/Article/details/gtvyecwrfh.html

PHP:  if (!$data) { return; }
来源：http://dali.hfpthk.cn/Article/details/gtkvrzyjli.html

JS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gtkxiduqjo.html

TS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gtihtmmkts.html

Java: if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gtorwwxumr.html

Go:   if data == nil { return }
来源：http://dali.guannengcc.top/Article/details/gtfditlrxo.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gtkfcteksg.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gtdfgjwsqn.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmkujdzzx.html

C. 函数与作用域
来源：http://dali.yanxiufei.cn/Article/details/gtxornpznd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtstoyrnlb.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtahwycxuv.html

Py:   def add(a, b): return a + b
来源：http://dali.guannengcc.top/Article/details/gttczcplcw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtkjvkeavw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtskzygqle.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyjvkerm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtxgxdrjfz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.smart0.xyz/Article/details/gtqxxofqio.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gthugkvtlo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gthkqqikvm.html

[C02] 默认参数
来源：http://dali.0kj1m.cn/Article/details/gtkvfdalyx.html

Py:   def greet(name="World"): return name
来源：http://dali.yangfankeji.com/Article/details/gtqahooyhi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gtjapvcvlp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtjguiod.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gtkaqorxzm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxyempkt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gtrkamaxym.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gtqfphccci.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gaohongyu789.top/Article/details/gtcijycgbb.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gtidmtqtvu.html

Py:   def total(*args): return sum(args)
来源：http://dali.sysykeji.top/Article/details/gtikyxuwkl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shzxlz.cn/Article/details/gtilkyipgo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtubproqpr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtvlgzuejb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xylfe.cn/Article/details/gtscdvwxsk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258.top/Article/details/gtriisjodz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gtaipmivfd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gtmpibuhqw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tianlin.xyz/Article/details/gtlysmztgk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gtotgmzoij.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fzhhl.top/Article/details/gttbrcmpju.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtrsdxwgwt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yangfankeji.com/Article/details/gtjbsrwdhx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guowangkeji.top/Article/details/gtyioemeni.html

Go:   // 无：用配置结构体参数
来源：http://dali.cqqwz.cn/Article/details/gtcwbwwitf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtnxmojmuk.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtlrojrrfw.html

[C05] 返回多个值
来源：http://dali.gzhubu.top/Article/details/gtjhofntum.html

Py:   return a, b
来源：http://dali.cucudq.cn/Article/details/gtivvnzgtl.html

PHP:  return [$a, $b];
来源：http://dali.316326.xyz/Article/details/gthemaepuy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtxwwnzmhl.html

TS:   return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtwupawzpw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sysykeji.top/Article/details/gtlrgwdrer.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtqihyrjpn.html

Ruby: return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfyicmtr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258.top/Article/details/gtfjzsnush.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gtmezpcclq.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gtjgxmcnhf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gtpeprebia.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtieoolndj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtqogndfgb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jianghu66.top/Article/details/gtrieclvyw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gttanldhbd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dashuyun.cn/Article/details/gttfinmmrk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtbykaipvh.html

[C07] 把函数作为参数传入
来源：http://dali.ydzc1.top/Article/details/gtztwflgkd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gtbwcggpkn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xziqi.cn/Article/details/gtnyjyneaa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gotoacloud.top/Article/details/gtbgfannzc.html

TS:   arr.map(String)
来源：http://dali.cqqwz.cn/Article/details/gtifgsymph.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtcpcvuimu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.feifeiyinyue.top/Article/details/gtpxguuwhm.html

Ruby: arr.map(&:upcase)
来源：http://dali.vqdsnc.cn/Article/details/gtyebivhwz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gthqpbpzel.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gtdyreqlhc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gtalzwxtfi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.iojbl.cn/Article/details/gtafdzasmt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtoltawlfs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtbsylntnm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sufxvd.cn/Article/details/gtmudgizty.html


<!-- 参考信息 -->