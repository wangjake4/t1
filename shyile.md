代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guowangkeji.top/Article/details/gt2achqclrg.html

Java: (int) 'A'; (char) 65
来源：http://dali.daria6918.cn/Article/details/gt2gjmrxixz.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.0kj1m.cn/Article/details/gt2jivvkdby.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhoulong.xyz/Article/details/gt2vmfztlos.html

C#:   (int)'A'; (char)65
来源：http://dali.pycfn.com/Article/details/gt2ueznomqb.html

[A19] 交换两个变量
来源：http://dali.snrcjt.cn/Article/details/gt2wxwxivhv.html

Py:   a, b = b, a
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzyqtakw.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinqigfzy.top/Article/details/gt2kjrmaxae.html

JS:   [a, b] = [b, a];
来源：http://dali.guannengcc.top/Article/details/gt2utjxiyek.html

TS:   [a, b] = [b, a];
来源：http://dali.nanxinkj.top/Article/details/gt2uxnqyqrf.html

Java: int t = a; a = b; b = t;
来源：http://dali.daria6918.cn/Article/details/gt2pdyqtkbn.html

Go:   a, b = b, a
来源：http://dali.redwolf501.top/Article/details/gt2pbkagkcw.html

Ruby: a, b = b, a
来源：http://dali.chenzaomai.com/Article/details/gt2dijfidei.html

C#:   (a, b) = (b, a);
来源：http://dali.fzhhl.top/Article/details/gt2flodvpon.html

[A20] 读取标准输入
来源：http://dali.9152youxi.cn/Article/details/gt2xcfaywmj.html

Py:   name = input("请输入：")
来源：http://dali.hammf.cn/Article/details/gt2ygebjvtb.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gaohongyu789.top/Article/details/gt2dvvqpabd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cashguo.top/Article/details/gt2xrbjuwnx.html

TS:   // Node.js：readline 模块
来源：http://dali.cucudq.cn/Article/details/gt2jdxdppbx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yangfankeji.com/Article/details/gt2izggmosc.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dtsonwhz.html

Ruby: gets.chomp
来源：http://dali.chenlongwang.top/Article/details/gt2oshugzur.html

C#:   Console.ReadLine();
来源：http://dali.jiagoushi.top/Article/details/gt2timpexuk.html

[A21] 保留指定小数位输出
来源：http://dali.cashguo.top/Article/details/gt2msltggcu.html

Py:   f"{3.14159:.2f}"
来源：http://dali.daxiang520.top/Article/details/gt2lafudkhf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqpicahb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gt2qkqcdgrn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gt2sllnnwmt.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gt2lqybxkue.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gt2zszfslaf.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gt2jstdlmsh.html

C#:   3.14159.ToString("F2")
来源：http://dali.tian-w.cn/Article/details/gt2coqdblwv.html

[A22] 获取字符串长度
来源：http://dali.haohaochexian.top/Article/details/gt2ehwlqraf.html

Py:   len(s)
来源：http://dali.ppjwa.cn/Article/details/gt2umtpzcrd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hnxiangtu.top/Article/details/gt2rybeakrt.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.svipenyu.cn/Article/details/gt2uhgyirdv.html

TS:   s.length
来源：http://dali.jyoumei.cn/Article/details/gt2afaecjyp.html

Java: s.length()
来源：http://dali.nwbrower.top/Article/details/gt2qdhurhwy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yongpay.top/Article/details/gt2pqevyhsb.html

Ruby: s.length
来源：http://dali.cashguo.top/Article/details/gt2wwwhnwss.html

C#:   s.Length
来源：http://dali.aizwys.cn/Article/details/gt2ctiszsxl.html

[A23] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdrgnjgn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jiagoushi.top/Article/details/gt2dvheimhu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jinqigufen.top/Article/details/gt2vlwurcaw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuanzhike.top/Article/details/gt2zghctnor.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyjriyez.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuanzhike.top/Article/details/gt2zjqzhbmt.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2frbsgzrf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gt2cdmaaqaw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.aibaodan.cn/Article/details/gt2kshkzmjk.html

[A24] 去除首尾空白
来源：http://dali.pengpengdd.cyou/Article/details/gt2jlzmkjjx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.wangshuangyany.cn/Article/details/gt2redltwwp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.meibo888.top/Article/details/gt2bblgcyad.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xylfe.cn/Article/details/gt2fifmevcw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fzhhl.top/Article/details/gt2gsdyfano.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tian-w.cn/Article/details/gt2beadbcch.html

Go:   strings.TrimSpace(s)
来源：http://dali.pycfn.com/Article/details/gt2ivhmaeco.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.sufxvd.cn/Article/details/gt2vljrpjpk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.bjfxy.top/Article/details/gt2gykmazof.html

[A25] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gt2wtbzjvgd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hywenlv.cn/Article/details/gt2yjdohfzs.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.bjfxy.top/Article/details/gt2gxpsqrum.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gt2ulxfsche.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shzxlz.cn/Article/details/gt2jqdvfufj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zycfv.cn/Article/details/gt2fkntvniy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jyoumei.cn/Article/details/gt2qgzsnidw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jqgufenzy.top/Article/details/gt2dprbdpcb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gt2bdmmemzc.html

[A26] 类型转换总览
来源：http://dali.yvedp.cn/Article/details/gt2yrivjbkn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.vqdsnc.cn/Article/details/gt2jfnjkqwz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hnqzz.top/Article/details/gt2zlizpsuh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yvedp.cn/Article/details/gt2kaoaajsj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhiwuduotai.top/Article/details/gt2xmopettt.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jqgufenzy.top/Article/details/gt2dclmueqz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.quarkkingdee.top/Article/details/gt2rwzeqymi.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tanke756.top/Article/details/gt2nlolvssm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.wangdashe.top/Article/details/gt2rznmtxaw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2kyvsbbtv.html

B. 流程控制
来源：http://dali.daria6918.cn/Article/details/gt2qmtywrgo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2msqafiqi.html

[B01] 条件判断 if / else
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxpbwrum.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yuxming.cn/Article/details/gt2yohuqpzv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj202588.top/Article/details/gt2xyysedfm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gt2phmvtqim.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gt2lomjqvod.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clubeqeh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.meibo888.top/Article/details/gt2ipchsbap.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cheryme.top/Article/details/gt2ayxvxlmg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gt2rsawbqes.html

[B02] 多分支 else if / elif
来源：http://dali.andypj.xyz/Article/details/gt2govfhyiz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xinyue.icu/Article/details/gt2uijmevbt.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.dianchejie.cn/Article/details/gt2flgfqszh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gt2jrsypvjo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gt2wgsqeyao.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gt2cbvwujuv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.9152youxi.cn/Article/details/gt2jrpjixva.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cucudq.cn/Article/details/gt2jitdusvh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gt2skpngqqm.html

[B03] switch / match / case
来源：http://dali.andypj.xyz/Article/details/gt2uozmtesc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shuidangran.top/Article/details/gt2wpckpnfe.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gt2apcdberl.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gt2ibaamfce.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2glpvbhmg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gt2ghstasmy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gt2afpndpqu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nwbrower.top/Article/details/gt2kdbyhrzm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.dianchejie.cn/Article/details/gt2xkpvjbtq.html

[B04] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gt2bcddxlam.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxinkj.top/Article/details/gt2suzgcklg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yonumen.top/Article/details/gt2hfaqsvqv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daria6918.cn/Article/details/gt2oxgmqgwv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gt2ocpbuuwd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fengsongda.top/Article/details/gt2aqunzpzu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhoulong.xyz/Article/details/gt2gsmcwzjw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sweek.top/Article/details/gt2wrdszgwi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ltyrrmiz.html

[B05] 遍历数组 / 列表
来源：http://dali.pycfn.com/Article/details/gt2bvietxlo.html

Py:   for item in arr: print(item)
来源：http://dali.zhongyouzk.top/Article/details/gt2ouvhjxar.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.316326.xyz/Article/details/gt2lcuvsaow.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hammf.cn/Article/details/gt2ontjtacj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nwbrower.top/Article/details/gt2nprhhqqf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.meibo888.top/Article/details/gt2uutpgxre.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edhppvjt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hfpthk.cn/Article/details/gt2kilxoclt.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.wangdashe.top/Article/details/gt2lddthxhj.html

[B06] 遍历字典 / 对象
来源：http://dali.snrcjt.cn/Article/details/gt2knwyutbr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2etvqipyg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.haohaochexian.top/Article/details/gt2nnbyzkmw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhongyouzk.top/Article/details/gt2wrwvmejn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aejkjvbf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangdashe.top/Article/details/gt2marxvdzt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xylfe.cn/Article/details/gt2atzhbrax.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yuanzhike.top/Article/details/gt2jolsprbk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj202588.top/Article/details/gt2uolgfteh.html

[B07] while 循环
来源：http://dali.zhoulong.xyz/Article/details/gt2xuuwscti.html

Py:   while i < 10: i += 1
来源：http://dali.pycfn.com/Article/details/gt2cslxoqcq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuxming.cn/Article/details/gt2otsggjnn.html

JS:   while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gt2lfcqxgjr.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2iuxbwfyf.html

Java: while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfbelezh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jiagoushi.top/Article/details/gt2kistuipn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hammf.cn/Article/details/gt2qfmikgut.html

C#:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gt2clfkgcfw.html

[B08] do-while（至少执行一次）
来源：http://dali.sweek.top/Article/details/gt2ctddeisv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aizwys.cn/Article/details/gt2uxhkbyii.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tanke756.top/Article/details/gt2aajoirro.html

JS:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2gbnkzaqg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gt2fwdpqbcq.html

Java: do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gt2tbatdouk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sxryk.cn/Article/details/gt2buiohnnn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shuidangran.top/Article/details/gt2swmvpfab.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2cikvhemq.html

[B09] break 与 continue
来源：http://dali.ybcxt.top/Article/details/gt2ogprcyyh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.birdmap.top/Article/details/gt2iekehjom.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qejviapi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2yfxbouca.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gt2jqqbjocp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2wztcwshv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuxming.cn/Article/details/gt2eqfzfmun.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ivvv.top/Article/details/gt2qyapcrid.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qpimsnkf.html

[B10] 遍历同时拿索引
来源：http://dali.tianlin.xyz/Article/details/gt2sjkphwlb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hywenlv.cn/Article/details/gt2okcaomvf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cqqwz.cn/Article/details/gt2zdegugwy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gt2cbbvbrui.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gt2eagirljn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daxiang520.top/Article/details/gt2jaxunifb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hysaishi.cn/Article/details/gt2xnmsdyvs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ppjwa.cn/Article/details/gt2fvxsamxj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigfzy.top/Article/details/gt2orzrwmgy.html

[B11] 生成数字序列 / 区间
来源：http://dali.ehwqpu.com/Article/details/gt2jaosycih.html

Py:   list(range(0, 10, 2))
来源：http://dali.cqqwz.cn/Article/details/gt2fxwivqcr.html

PHP:  range(0, 10, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jldqnvcc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gt2nhgkymqu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2oxtxnbhz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sxryk.cn/Article/details/gt2panbvtuc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gotoacloud.top/Article/details/gt2bczhcqap.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenzaomai.com/Article/details/gt2usnpejna.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yonumen.top/Article/details/gt2qmdkijcc.html

[B12] 跳出多层循环
来源：http://dali.dianchejie.cn/Article/details/gt2gjmgqhaq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.vqdsnc.cn/Article/details/gt2ycobbphf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gzhubu.top/Article/details/gt2kzaiujbn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gt2lswesqfe.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gt2ltheocqc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gt2qllrknyy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gt2bjavbdgg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.havefunace.top/Article/details/gt2resryfsv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daria6918.cn/Article/details/gt2pfrorzgz.html

[B13] 判断是否为数字
来源：http://dali.jianghu66.top/Article/details/gt2pincoqkb.html

Py:   isinstance(x, (int, float))
来源：http://dali.ybcxt.top/Article/details/gt2suljctwr.html

PHP:  is_numeric($x)
来源：http://dali.ivvv.top/Article/details/gt2yryfrjeg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2htajrtoh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2ebvdrjks.html

Java: x instanceof Number
来源：http://dali.sxryk.cn/Article/details/gt2rugzsers.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.smart0.xyz/Article/details/gt2teeluchj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gt2aulbadyw.html

C#:   x is int or double or decimal
来源：http://dali.xinyue.icu/Article/details/gt2qbyhbqso.html

[B14] 判断值是否在集合内
来源：http://dali.ehwqpu.com/Article/details/gt2vrxawgri.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ppjwa.cn/Article/details/gt2auyknptd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gt2xmnnatou.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2dvayyubj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2rkmrgafs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldlabmqp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ppjwa.cn/Article/details/gt2acavuymq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.c1oappe.top/Article/details/gt2aeajrvay.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2qusmdzer.html

[B15] 布尔运算与取反
来源：http://dali.guowangkeji.top/Article/details/gt2peqdmvgb.html

Py:   a and b or not c
来源：http://dali.0kj1m.cn/Article/details/gt2gqunowhl.html

PHP:  $a && $b || !$c
来源：http://dali.cdnleiting.top/Article/details/gt2cyxugzwd.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2psdtgomr.html

TS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2lykcdqfc.html

Java: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2wquxdqof.html

Go:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2xgpqtjba.html

Ruby: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2jimbnghz.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2qgdjwxee.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gzhubu.top/Article/details/gt2clssnist.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gt2ruijhrrv.html

PHP:  if (!$data) { return; }
来源：http://dali.aibaodan.cn/Article/details/gt2hbwdlumm.html

JS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gt2qcdeugob.html

TS:   if (!data) return;
来源：http://dali.jinqigufen.top/Article/details/gt2rvpbvfwe.html

Java: if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gt2ifcphmvl.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gt2sdivebgn.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gt2gnkcwzgv.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gt2dnwqloab.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2uymxbdon.html

C. 函数与作用域
来源：http://dali.fengsongda.top/Article/details/gt2ohgmpfpn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ufbarmsv.html

[C01] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqababeq.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2dbgyubfi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2mauxqygu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2rifgsgjl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2bhfuebww.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2uwipktsh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jyoumei.cn/Article/details/gt2dgmlxhzc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yongpay.top/Article/details/gt2skmsktew.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2zdebkxuj.html

[C02] 默认参数
来源：http://dali.sweek.top/Article/details/gt2lfzkused.html

Py:   def greet(name="World"): return name
来源：http://dali.zhiwuduotai.top/Article/details/gt2ilvjabah.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2uziexgcq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttvbycsw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2iehnueef.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ivvv.top/Article/details/gt2mesehrza.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gt2sqpcpraa.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gt2cmupqpys.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.haohaochexian.top/Article/details/gt2znbtrkej.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gt2fbevwfjg.html

Py:   def total(*args): return sum(args)
来源：http://dali.daria6918.cn/Article/details/gt2lovlfbrw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258.top/Article/details/gt2aalykubv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gt2uofuavpt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gt2trjvggju.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbzmecxs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gt2ikmhfpif.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gt2bajypjnn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dianchejie.cn/Article/details/gt2zhnspqkf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gt2lhweuqxj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gt2rmkunbsv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xinyue.icu/Article/details/gt2cwzzivda.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jdhjoiky.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigufen.top/Article/details/gt2tfqrigee.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuanzhike.top/Article/details/gt2bbqixoko.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangdashe.top/Article/details/gt2erydcolg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gt2kgitjopx.html

C#:   f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2luufhkjj.html

[C05] 返回多个值
来源：http://dali.birdmap.top/Article/details/gt2xqkbaaxt.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkgzzils.html

PHP:  return [$a, $b];
来源：http://dali.hysaishi.cn/Article/details/gt2jqbzkdww.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tanke756.top/Article/details/gt2qdgnuhao.html

TS:   return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gt2ztwtzvsd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sysykeji.top/Article/details/gt2zfymccbv.html

Go:   return a, b
来源：http://dali.tanke756.top/Article/details/gt2qrcqziuf.html

Ruby: return a, b
来源：http://dali.shzxlz.cn/Article/details/gt2ndnirhoa.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nwbrower.top/Article/details/gt2tzlvjfgj.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxuanxn.top/Article/details/gt2nxkinotd.html

Py:   square = lambda x: x * x
来源：http://dali.ydzc1.top/Article/details/gt2dycyrkws.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gogol.net.cn/Article/details/gt2ppjzxjfq.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqacqjg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sweek.top/Article/details/gt2zkjogatj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2zisfhcat.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2piprkvbe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ooohrztp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gt2cgvgudjl.html

[C07] 把函数作为参数传入
来源：http://dali.jqgufenzy.top/Article/details/gt2yapgouqn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ehwqpu.com/Article/details/gt2cxzbrfpj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xylfe.cn/Article/details/gt2hulcmmcm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yvedp.cn/Article/details/gt2vqzhacjw.html

TS:   arr.map(String)
来源：http://dali.hywenlv.cn/Article/details/gt2jpyarsuf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2pwoxdpio.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gt2ixzvbdir.html

Ruby: arr.map(&:upcase)
来源：http://dali.hfpthk.cn/Article/details/gt2wgdhbwrs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhhysjlo.html

[C08] 闭包
来源：http://dali.chenjidiqi.icu/Article/details/gt2kaleppqj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gt2pnuasnaf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lizmmjha.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlsmyfcl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2sedwgcri.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jianghu66.top/Article/details/gt2miggwgwr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhrfzion.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenzaomai.com/Article/details/gt2qselmxmg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2xgiiubbw.html

[C09] 递归
来源：http://dali.tanke756.top/Article/details/gt2svxrpbuk.html


<!-- 参考信息 -->