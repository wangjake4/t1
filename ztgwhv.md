代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.aibaodan.cn/Article/details/gtvfizjdsa.html

Py:   ord("A"); chr(65)
来源：http://dali.chenlongwang.top/Article/details/gtxicyfzuw.html

PHP:  ord("A"); chr(65)
来源：http://dali.yongpay.top/Article/details/gtyqapxdxc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yongpay.top/Article/details/gtjaemmrcv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xziqi.cn/Article/details/gttreqqntf.html

Java: (int) 'A'; (char) 65
来源：http://dali.nanxuanxn.top/Article/details/gtrzxdjcwi.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yuanzhike.top/Article/details/gtklwkvxrj.html

Ruby: "A".ord; 65.chr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvpykpud.html

C#:   (int)'A'; (char)65
来源：http://dali.bjfxy.top/Article/details/gtciqukehs.html

[A19] 交换两个变量
来源：http://dali.zhoulong.xyz/Article/details/gtdbfnmwiq.html

Py:   a, b = b, a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwzorstw.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gotoacloud.top/Article/details/gtitsqqnsp.html

JS:   [a, b] = [b, a];
来源：http://dali.mhx1999.top/Article/details/gtkdzupecg.html

TS:   [a, b] = [b, a];
来源：http://dali.316326.xyz/Article/details/gtwtncbheh.html

Java: int t = a; a = b; b = t;
来源：http://dali.yangfankeji.com/Article/details/gthmzhruwq.html

Go:   a, b = b, a
来源：http://dali.haohaochexian.top/Article/details/gtpepppjfd.html

Ruby: a, b = b, a
来源：http://dali.gotoacloud.top/Article/details/gtkhcxxvfz.html

C#:   (a, b) = (b, a);
来源：http://dali.guannengcc.top/Article/details/gtyoacqoer.html

[A20] 读取标准输入
来源：http://dali.hammf.cn/Article/details/gtmjjkosij.html

Py:   name = input("请输入：")
来源：http://dali.daria6918.cn/Article/details/gtlisuqmpx.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.nanxuanxn.top/Article/details/gtgbgjlrtk.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xinyue.icu/Article/details/gtzvzgtoay.html

TS:   // Node.js：readline 模块
来源：http://dali.smart0.xyz/Article/details/gtjicsckiu.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhoulong.xyz/Article/details/gtzyeuobma.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xuanzx.com/Article/details/gtebvtaliv.html

Ruby: gets.chomp
来源：http://dali.havefunace.top/Article/details/gtmtlieboz.html

C#:   Console.ReadLine();
来源：http://dali.yj20258888.top/Article/details/gtqyfieobu.html

[A21] 保留指定小数位输出
来源：http://dali.yangfankeji.com/Article/details/gtryeezcfu.html

Py:   f"{3.14159:.2f}"
来源：http://dali.c1oappe.top/Article/details/gtgjmvacqm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gtjnkcsgvp.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosvhljfv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gtkfjmshol.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gtvhinmosf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gtxntclxtc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gtkqszeubc.html

C#:   3.14159.ToString("F2")
来源：http://dali.fengsongda.top/Article/details/gtkhetpund.html

[A22] 获取字符串长度
来源：http://dali.jinqigufen.top/Article/details/gtckzlnqnz.html

Py:   len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtljeixgnx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xziqi.cn/Article/details/gthgegcrts.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sxryk.cn/Article/details/gtfoqyenpk.html

TS:   s.length
来源：http://dali.zhengqikj.top/Article/details/gtopbvpbsi.html

Java: s.length()
来源：http://dali.hywenlv.cn/Article/details/gtxpuhgror.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtnygqktex.html

Ruby: s.length
来源：http://dali.yongpay.top/Article/details/gtatnxeukp.html

C#:   s.Length
来源：http://dali.xinyue.icu/Article/details/gtmbakaabw.html

[A23] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gtrvdsyeln.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.chenlongwang.top/Article/details/gtxxgcemhq.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hnqzz.top/Article/details/gtsmzoetwv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xylfe.cn/Article/details/gtbtjubmkt.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gogol.net.cn/Article/details/gtxdzzrsmq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gtjjpnjsyv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.aibaodan.cn/Article/details/gtxyzargvq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gtvqpeumvz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ehwqpu.com/Article/details/gtiockzjiy.html

[A24] 去除首尾空白
来源：http://dali.birdmap.top/Article/details/gtgyvsenpv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hysaishi.cn/Article/details/gtpuccdtly.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ppjwa.cn/Article/details/gtioflbknb.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.bjfxy.top/Article/details/gtohercgdz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtpcropwuh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tianlin.xyz/Article/details/gtkxveipex.html

Go:   strings.TrimSpace(s)
来源：http://dali.sxryk.cn/Article/details/gtetjqmdhp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj20258888.top/Article/details/gtewgqssvp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.nanxinkj.top/Article/details/gtctocofpe.html

[A25] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gtwoacmosh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cucudq.cn/Article/details/gturodbiey.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hywenlv.cn/Article/details/gtqowagand.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.316326.xyz/Article/details/gtfduwweuq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.svipenyu.cn/Article/details/gtwbibjjqx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jqgfzy.top/Article/details/gtgntvculb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gzhubu.top/Article/details/gtuovqwerb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.9152youxi.cn/Article/details/gtxlgvoehx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ybcxt.top/Article/details/gtatavghnk.html

[A26] 类型转换总览
来源：http://dali.pycfn.com/Article/details/gtcomhtzug.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.dianchejie.cn/Article/details/gtliyskeqj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gzhubu.top/Article/details/gtumvrascq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.bjfxy.top/Article/details/gtuvrhfpnf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.dianchejie.cn/Article/details/gtgxqedsyb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ppjwa.cn/Article/details/gtrhdymfds.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.chenzaomai.com/Article/details/gtjhwxbghx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ivvv.top/Article/details/gthevztqxx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gteisoqrbb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtlaqnartf.html

B. 流程控制
来源：http://dali.xuanzx.com/Article/details/gtdenfrjyo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnymzxeri.html

[B01] 条件判断 if / else
来源：http://dali.jqgfzy.top/Article/details/gtcmjgkvpb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.iojbl.cn/Article/details/gtlilbarxp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtyecwqtbd.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtxadoktpe.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtkndsmnqp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gtxxhgqbjj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenjidiqi.icu/Article/details/gtjyyhrhkt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ivvv.top/Article/details/gtmlgfoduy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtlbgiroxh.html

[B02] 多分支 else if / elif
来源：http://dali.guowangkeji.top/Article/details/gthimvarkh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinqigufen.top/Article/details/gtxmdxgcsy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj20258888.top/Article/details/gtbyhmyxss.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrpwjfvw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhlaymks.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtdqhgujzj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.quarkkingdee.top/Article/details/gtjxdlivhx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ivvv.top/Article/details/gtblqolarj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtivimumjs.html

[B03] switch / match / case
来源：http://dali.meibo888.top/Article/details/gtwkoakvre.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.snrcjt.cn/Article/details/gtlrhezoik.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhengqikj.top/Article/details/gtgbsxfkal.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtolypopka.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwvhhrim.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtxockqnvm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.birdmap.top/Article/details/gtyrnzeavd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.aibaodan.cn/Article/details/gtitlrpbec.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gtxmbydnbv.html

[B04] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gthwefhmlo.html

Py:   for i in range(10): print(i)
来源：http://dali.zhengqikj.top/Article/details/gtocndfygd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.aizwys.cn/Article/details/gtdjflbtol.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yangfankeji.com/Article/details/gtomldyweb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gtgybbdfxy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.dianchejie.cn/Article/details/gtrygpvfbj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tianlin.xyz/Article/details/gtxofxfwdc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.vqdsnc.cn/Article/details/gtumoxxfex.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yuanzhike.top/Article/details/gtcnffvwpj.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtmvrkhxtt.html

Py:   for item in arr: print(item)
来源：http://dali.ybcxt.top/Article/details/gtikwhmhzf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hywenlv.cn/Article/details/gtzxaypzav.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gtwlhlcpge.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gtixtnsyik.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.316326.xyz/Article/details/gtgxxtezvd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.9152youxi.cn/Article/details/gtuhyjxycs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cqqwz.cn/Article/details/gtszpitzil.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yvedp.cn/Article/details/gtxtrsfsqt.html

[B06] 遍历字典 / 对象
来源：http://dali.gogol.net.cn/Article/details/gtfnzbnmok.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yuxming.cn/Article/details/gtoabdxjjz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ybcxt.top/Article/details/gtfkcxwhkb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sufxvd.cn/Article/details/gtsxrpmclw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gtlihtrrnv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.andypj.xyz/Article/details/gtudpcmrtj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jlsjyb.cn/Article/details/gtzgscijaq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258888.top/Article/details/gteribrlph.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ppjwa.cn/Article/details/gtsevjnnrq.html

[B07] while 循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykpkgkat.html

Py:   while i < 10: i += 1
来源：http://dali.zhixingplan.top/Article/details/gtjnwrnqwk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakdtyfds.html

JS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtyystvgsb.html

TS:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtemlqqdjx.html

Java: while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtsuaqnmcx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gzhubu.top/Article/details/gtwggzzqzs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sysykeji.top/Article/details/gthepsudgy.html

C#:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtbmbqjgrd.html

[B08] do-while（至少执行一次）
来源：http://dali.0kj1m.cn/Article/details/gtzpoturkj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj202588.top/Article/details/gtemdunpxp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hammf.cn/Article/details/gtfzgtettr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtzjewgzsf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtihawyghs.html

Java: do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gttrdaastp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.fengsongda.top/Article/details/gtvarysrcn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangshuangyany.cn/Article/details/gtxoebvkqi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtrfsabtsw.html

[B09] break 与 continue
来源：http://dali.hywenlv.cn/Article/details/gtgfcphhhb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hfpthk.cn/Article/details/gtdvaxqbuy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtksbaksqq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrpwgspa.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtxwlifvqp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytkippea.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gtzfjrihmc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.quarkkingdee.top/Article/details/gtlsvfepjc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbgdehzvp.html

[B10] 遍历同时拿索引
来源：http://dali.hongshengwenyu.top/Article/details/gtwbugnjde.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhixingplan.top/Article/details/gtvcyihjdv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tian-w.cn/Article/details/gtoatvyuvw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtcfvnzmdp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gtahufejxm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aizwys.cn/Article/details/gtednmpijp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.haohaochexian.top/Article/details/gtbrdkazbe.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hfpthk.cn/Article/details/gtrryolxpi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqvsqvmm.html

[B11] 生成数字序列 / 区间
来源：http://dali.dashuyun.cn/Article/details/gtuekbocqx.html

Py:   list(range(0, 10, 2))
来源：http://dali.c1oappe.top/Article/details/gtxuuizgcu.html

PHP:  range(0, 10, 2);
来源：http://dali.cucudq.cn/Article/details/gtdtwrwisb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gtadcfpltd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvifybud.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtqkkopqrb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gtefkorzft.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zdqjudy.top/Article/details/gtqlcndxun.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yanxiufei.cn/Article/details/gtqcpqstyd.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gtqdpvxnke.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yonumen.top/Article/details/gtqvmfacsw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.vqdsnc.cn/Article/details/gtdiaoepbf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtnnntltwe.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtrqahxtmi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtotmcolyb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.havefunace.top/Article/details/gtvnmtzasi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxinkj.top/Article/details/gttvkgseji.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenzaomai.com/Article/details/gtumbyjncx.html

[B13] 判断是否为数字
来源：http://dali.tian-w.cn/Article/details/gtiyqqemfm.html

Py:   isinstance(x, (int, float))
来源：http://dali.svipenyu.cn/Article/details/gtdcvnrqaq.html

PHP:  is_numeric($x)
来源：http://dali.sxryk.cn/Article/details/gtrtnudxly.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gtkpbsnesp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gtfrxndnix.html

Java: x instanceof Number
来源：http://dali.cqqwz.cn/Article/details/gtjlrjgmdx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ivvv.top/Article/details/gthajcxpib.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuanzhike.top/Article/details/gtesysjzjp.html

C#:   x is int or double or decimal
来源：http://dali.xylfe.cn/Article/details/gtrkojjexz.html

[B14] 判断值是否在集合内
来源：http://dali.birdmap.top/Article/details/gtlmxjzocj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gtgjmysjwk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jianghu66.top/Article/details/gtgyblqjuz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtcybozmej.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtollpvyca.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtmliogghk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.c1oappe.top/Article/details/gtzveukxxk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtehmdqlad.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtglmpstqv.html

[B15] 布尔运算与取反
来源：http://dali.yvedp.cn/Article/details/gtdbhxjmwd.html

Py:   a and b or not c
来源：http://dali.zdqjudy.top/Article/details/gtgxerwrai.html

PHP:  $a && $b || !$c
来源：http://dali.aizwys.cn/Article/details/gtxjkvvmpj.html

JS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtpaletsoo.html

TS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtofpkwkma.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtxizhifac.html

Go:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtevjnfdto.html

Ruby: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtwwdqjebm.html

C#:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtzjeuwrqd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.9152youxi.cn/Article/details/gtuiyxqjtm.html

Py:   if not data: return
来源：http://dali.ydzc1.top/Article/details/gtjebexgpn.html

PHP:  if (!$data) { return; }
来源：http://dali.guowangkeji.top/Article/details/gtzycukrlz.html

JS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtsdlwsplz.html

TS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gtfhbhjtwl.html

Java: if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gtkjvoktov.html

Go:   if data == nil { return }
来源：http://dali.9152youxi.cn/Article/details/gtqpdugjws.html

Ruby: return if data.nil?
来源：http://dali.jqgufenzy.top/Article/details/gtxzgkweyj.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtafpfdw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtuhstdbkw.html

C. 函数与作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmteussf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gteurcxvqh.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtntinyblk.html

Py:   def add(a, b): return a + b
来源：http://dali.9152youxi.cn/Article/details/gtrberaueg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtouaaitig.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtqopxhylf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtfopaivmh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gthibzcehw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjfpwywg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guannengcc.top/Article/details/gtpppyxplv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtuefttrpk.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gtjqwiublz.html

Py:   def greet(name="World"): return name
来源：http://dali.zhiwuduotai.top/Article/details/gtxrsfuznd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxuanxn.top/Article/details/gtfaisysae.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gtqxfoxlci.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtvshalmuf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gtrrkatgxu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gtesaqvptu.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gtbosyxkyq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhoulong.xyz/Article/details/gtwhwniwuq.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gthbyyxuka.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gtqghaesuw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgufenzy.top/Article/details/gtabjzrffh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtyciizufu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dianchejie.cn/Article/details/gtfqafuyhv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtazofdlwa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hywenlv.cn/Article/details/gtpnjouoel.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gtmutvntoi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbvairsz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dashuyun.cn/Article/details/gtrpsdpzxf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuetiantiany.cn/Article/details/gtjlcpquhb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sxryk.cn/Article/details/gtyhozxmvg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtwpmsifjh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gtjrwudxee.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuetiantiany.cn/Article/details/gtbcgragim.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gtmcwgwtpz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxiajhrw.html

C#:   f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtpadmbalp.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gtaptchzal.html

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtpqiripso.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gthqswnyoh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtxagbbagu.html

TS:   return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gtponukigl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sufxvd.cn/Article/details/gtwizeilxq.html

Go:   return a, b
来源：http://dali.sysykeji.top/Article/details/gtiyxrgefi.html

Ruby: return a, b
来源：http://dali.shzxlz.cn/Article/details/gtlgksdhfn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.svipenyu.cn/Article/details/gtutxjooml.html

[C06] 匿名函数 / lambda
来源：http://dali.cucudq.cn/Article/details/gtmmzocsks.html

Py:   square = lambda x: x * x
来源：http://dali.ivvv.top/Article/details/gtuivrsnik.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenzaomai.com/Article/details/gtcvbleacz.html

JS:   const square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtcvbevwxx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gtbvukvxep.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gtwpszmztn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gtdkjsqskq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yvedp.cn/Article/details/gtwmafomfn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtqhfprrik.html

[C07] 把函数作为参数传入
来源：http://dali.kuanghao11.cn/Article/details/gtpkpotewn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sysykeji.top/Article/details/gtmuijdwry.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtigmvequl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xinyue.icu/Article/details/gtvtazpduw.html

TS:   arr.map(String)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhddsaty.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tianlin.xyz/Article/details/gtwrgjkktm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtwzjkoc.html

Ruby: arr.map(&:upcase)
来源：http://dali.haohaochexian.top/Article/details/gtsooeoccg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gtxghqbimh.html

[C08] 闭包
来源：http://dali.smart0.xyz/Article/details/gtbmqaknua.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtbshvndwm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258888.top/Article/details/gtnvuqtihf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtdqkljxxc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtlfvtykoh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gtseiiicjq.html


<!-- 参考信息 -->