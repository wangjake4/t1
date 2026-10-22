代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.daxiang520.top/Article/details/gtzpbkcpya.html

Py:   ord("A"); chr(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsoobzoz.html

PHP:  ord("A"); chr(65)
来源：http://dali.yanxiufei.cn/Article/details/gtpspyzlsr.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.snrcjt.cn/Article/details/gtigjlphwc.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hywenlv.cn/Article/details/gtaywzbzsm.html

Java: (int) 'A'; (char) 65
来源：http://dali.chenjidiqi.icu/Article/details/gtcpafsufc.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.haohaochexian.top/Article/details/gtwebcigzy.html

Ruby: "A".ord; 65.chr
来源：http://dali.hfpthk.cn/Article/details/gtlywzdweh.html

C#:   (int)'A'; (char)65
来源：http://dali.xylfe.cn/Article/details/gtrlxrruwv.html

[A19] 交换两个变量
来源：http://dali.shangyingyoupin.top/Article/details/gtlrbazjlc.html

Py:   a, b = b, a
来源：http://dali.guannengcc.top/Article/details/gtdnxteyzt.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jlsjyb.cn/Article/details/gtcqrplbko.html

JS:   [a, b] = [b, a];
来源：http://dali.xuetiantiany.cn/Article/details/gtbcaihbpw.html

TS:   [a, b] = [b, a];
来源：http://dali.xuetiantiany.cn/Article/details/gtiohjktxj.html

Java: int t = a; a = b; b = t;
来源：http://dali.yangfankeji.com/Article/details/gtyludrvbd.html

Go:   a, b = b, a
来源：http://dali.feifeiyinyue.top/Article/details/gtxosburxd.html

Ruby: a, b = b, a
来源：http://dali.haohaochexian.top/Article/details/gtysvotlon.html

C#:   (a, b) = (b, a);
来源：http://dali.yangfankeji.com/Article/details/gteckxrmgm.html

[A20] 读取标准输入
来源：http://dali.mhx1999.top/Article/details/gttncnxjik.html

Py:   name = input("请输入：")
来源：http://dali.nwbrower.top/Article/details/gtwnenlitu.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yj20258.top/Article/details/gttnnvnnrf.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xinyue.icu/Article/details/gtxfnfuspa.html

TS:   // Node.js：readline 模块
来源：http://dali.snrcjt.cn/Article/details/gtwqwahseu.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhijiandao.cn/Article/details/gtjcbaenie.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jqgufenzy.top/Article/details/gtfxtyxulk.html

Ruby: gets.chomp
来源：http://dali.hysaishi.cn/Article/details/gtwnzonici.html

C#:   Console.ReadLine();
来源：http://dali.haohaochexian.top/Article/details/gttcozberb.html

[A21] 保留指定小数位输出
来源：http://dali.iojbl.cn/Article/details/gtcgueyzhd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinqigfzy.top/Article/details/gtrwfzqzad.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.c1oappe.top/Article/details/gtkaitfckm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gtbawyrngh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gthntuompz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gtgijgvbmw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gtkzbydxog.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gtajxtfrww.html

C#:   3.14159.ToString("F2")
来源：http://dali.cucudq.cn/Article/details/gtuqefrrue.html

[A22] 获取字符串长度
来源：http://dali.smart0.xyz/Article/details/gteajzyoes.html

Py:   len(s)
来源：http://dali.sysykeji.top/Article/details/gtwjyzfqwa.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xinyue.icu/Article/details/gtlrlmifez.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.andypj.xyz/Article/details/gtzqivpbzd.html

TS:   s.length
来源：http://dali.ivvv.top/Article/details/gteiyjngbj.html

Java: s.length()
来源：http://dali.jqgfzy.top/Article/details/gtxpgmtali.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.andypj.xyz/Article/details/gthktacmwo.html

Ruby: s.length
来源：http://dali.gogol.net.cn/Article/details/gtgyrudmgp.html

C#:   s.Length
来源：http://dali.jinqigufen.top/Article/details/gteripcrbq.html

[A23] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtrxfrfuhu.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.0kj1m.cn/Article/details/gtgcypdddw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ybcxt.top/Article/details/gtdfwuxbqz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvdtklbt.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.iojbl.cn/Article/details/gtpnhiqnjd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gtllvuhtql.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtmozljvnn.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gtnrcggyhh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.316326.xyz/Article/details/gtovbfjrio.html

[A24] 去除首尾空白
来源：http://dali.dashuyun.cn/Article/details/gtsmfleiib.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyricvdn.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cucudq.cn/Article/details/gtlexsnvpg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xziqi.cn/Article/details/gtsgleauvp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuanzx.com/Article/details/gthdtnkwkv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.mhx1999.top/Article/details/gtlvkyceda.html

Go:   strings.TrimSpace(s)
来源：http://dali.pycfn.com/Article/details/gtmhuzxdfs.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenzaomai.com/Article/details/gtxsgfwjjr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ydzc1.top/Article/details/gtydssvqmd.html

[A25] 字符串比较
来源：http://dali.birdmap.top/Article/details/gtgaxsfnrw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrjelpdo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.pengpengdd.cyou/Article/details/gtomsbnbjk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttozhlium.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sysykeji.top/Article/details/gtsidkrprw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtfltlpfcc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xylfe.cn/Article/details/gtciabzlwe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.wangshuangyany.cn/Article/details/gtzxvufjqj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gtxrpclxdk.html

[A26] 类型转换总览
来源：http://dali.jqgfzy.top/Article/details/gtnpwtmpki.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.pycfn.com/Article/details/gtuvdqguqc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.smart0.xyz/Article/details/gtzrjhmeyi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sysykeji.top/Article/details/gtakuamrya.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangdashe.top/Article/details/gtqngjbbce.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.mhx1999.top/Article/details/gtxfwzjdlt.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.316326.xyz/Article/details/gtyeywcjgq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ybcxt.top/Article/details/gtisabvkrl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tanke756.top/Article/details/gtiqejiqla.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvumhhhao.html

B. 流程控制
来源：http://dali.jyoumei.cn/Article/details/gtdatfvtgm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqjbouvrk.html

[B01] 条件判断 if / else
来源：http://dali.cheryme.top/Article/details/gtfuqizveh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258888.top/Article/details/gtvuxykxzf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yanxiufei.cn/Article/details/gtqzgwrqzz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtzmzffqta.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtgawvtknw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtwbvwfv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebamobtc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcouzolpm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtywahpgwl.html

[B02] 多分支 else if / elif
来源：http://dali.quarkkingdee.top/Article/details/gtgyhmpuaq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhongyouzk.top/Article/details/gtbetivulp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.aizwys.cn/Article/details/gtklifnzha.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtgwisvjgw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtgrksbhgl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtsbetpcst.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gtawmszgad.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nwbrower.top/Article/details/gthmowuwjl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgardbais.html

[B03] switch / match / case
来源：http://dali.andypj.xyz/Article/details/gtuehpkhwj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.andypj.xyz/Article/details/gtezykegev.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtvkbesvxu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnpdtxsmt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygsfafkk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtdxkrkktd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hammf.cn/Article/details/gtvkeowccy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.iojbl.cn/Article/details/gtmemcikxh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fengsongda.top/Article/details/gtcdtmhdzo.html

[B04] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gtmrqaamhz.html

Py:   for i in range(10): print(i)
来源：http://dali.jianghu66.top/Article/details/gtctrjgbar.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.aibaodan.cn/Article/details/gthovtgfzr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.haohaochexian.top/Article/details/gtaorsjcmi.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hfpthk.cn/Article/details/gtdrmmffmu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.meibo888.top/Article/details/gtjtrdokpy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.andypj.xyz/Article/details/gtfdwkyvgk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yuanzhike.top/Article/details/gtqjapypuc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.quarkkingdee.top/Article/details/gtitfwanju.html

[B05] 遍历数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdballruk.html

Py:   for item in arr: print(item)
来源：http://dali.zhoulong.xyz/Article/details/gtbrclhmgq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxvvadtxo.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuanzx.com/Article/details/gtoqeqtyos.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hfpthk.cn/Article/details/gtiixjkete.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ybcxt.top/Article/details/gthjeitfdv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.redwolf501.top/Article/details/gtbtrkgxgc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.andypj.xyz/Article/details/gteusyouue.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hfpthk.cn/Article/details/gtjumcyylt.html

[B06] 遍历字典 / 对象
来源：http://dali.guannengcc.top/Article/details/gtqhcnliyr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fengsongda.top/Article/details/gtwehorkkn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zdqjudy.top/Article/details/gtrwberzvd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtcpaqgiji.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtquitiwzc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumhwvagz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xinyue.icu/Article/details/gtwzfdbrzd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqvdwuaa.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yvedp.cn/Article/details/gtxdzrngqh.html

[B07] while 循环
来源：http://dali.meibo888.top/Article/details/gtplqwhfnj.html

Py:   while i < 10: i += 1
来源：http://dali.gogol.net.cn/Article/details/gtauurouxv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gthqmqhejn.html

JS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcpoyhcbo.html

TS:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtpdaiwymt.html

Java: while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtymsvhlgr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.daria6918.cn/Article/details/gtbkgtbgmr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yanxiufei.cn/Article/details/gtncxryudm.html

C#:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtqcdfumey.html

[B08] do-while（至少执行一次）
来源：http://dali.ivvv.top/Article/details/gtpwwfgavi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenlongwang.top/Article/details/gtplhpqrdw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258.top/Article/details/gtzybofihh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtpsmkicpo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmupkqgp.html

Java: do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtwhjfuyit.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.daxiang520.top/Article/details/gtqxgrzgid.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ehwqpu.com/Article/details/gtlypgumcb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtxpjtbebg.html

[B09] break 与 continue
来源：http://dali.tian-w.cn/Article/details/gtnytvjyqv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nanxinkj.top/Article/details/gtqqibboeo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcnvhfuo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtprjzebcx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtvzurwuva.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtgwxadgij.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.redwolf501.top/Article/details/gtglmgknov.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gzhubu.top/Article/details/gtpdwtqrxd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtmepijgvx.html

[B10] 遍历同时拿索引
来源：http://dali.yj20258.top/Article/details/gtrsublaah.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ydzc1.top/Article/details/gtfjwplqlb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shuidangran.top/Article/details/gtgruljxjw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hywenlv.cn/Article/details/gtbiyncguf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.fengsongda.top/Article/details/gtuanfranj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxinkj.top/Article/details/gtpyxfswuh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shuidangran.top/Article/details/gtxijwcnep.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.feifeiyinyue.top/Article/details/gtlclgksjy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigfzy.top/Article/details/gtwdhbptrs.html

[B11] 生成数字序列 / 区间
来源：http://dali.xziqi.cn/Article/details/gtgolrbqbi.html

Py:   list(range(0, 10, 2))
来源：http://dali.daxiang520.top/Article/details/gtbhyyvges.html

PHP:  range(0, 10, 2);
来源：http://dali.dashuyun.cn/Article/details/gtmbaneizd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrsusxnj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtkokonmag.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtotnltuqb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nwbrower.top/Article/details/gtrkxycnyt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.quarkkingdee.top/Article/details/gtkhboairz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.316326.xyz/Article/details/gtmveqzzby.html

[B12] 跳出多层循环
来源：http://dali.nanxinkj.top/Article/details/gtwxjsgrds.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuanzx.com/Article/details/gtpapeysta.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxuanxn.top/Article/details/gtglsxfemq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtniqjzdwn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtudgbhesm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gthvyblkjy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgufenzy.top/Article/details/gtgmlvpldp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhixingplan.top/Article/details/gtzyogkpir.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.meibo888.top/Article/details/gtjgltcjch.html

[B13] 判断是否为数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalwvfayy.html

Py:   isinstance(x, (int, float))
来源：http://dali.hongshengwenyu.top/Article/details/gthgwzslef.html

PHP:  is_numeric($x)
来源：http://dali.jinqigufen.top/Article/details/gtklssmrvd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gtbrijzjba.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pycfn.com/Article/details/gtrjjfwjwi.html

Java: x instanceof Number
来源：http://dali.aibaodan.cn/Article/details/gtijhlkunu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hongshengwenyu.top/Article/details/gtuovcbahl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yongpay.top/Article/details/gtqxrroznm.html

C#:   x is int or double or decimal
来源：http://dali.yj202588.top/Article/details/gtubnsstla.html

[B14] 判断值是否在集合内
来源：http://dali.chenlongwang.top/Article/details/gtbwkdwkkd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258888.top/Article/details/gtrhfvzzod.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskhsgzsf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtyediksma.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gthnujfgxn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.birdmap.top/Article/details/gtbzqrlbkr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhongyouzk.top/Article/details/gtknucactq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ivvv.top/Article/details/gtohkldmbv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtrrkcqznc.html

[B15] 布尔运算与取反
来源：http://dali.gotoacloud.top/Article/details/gtkkecmgzs.html

Py:   a and b or not c
来源：http://dali.hnqzz.top/Article/details/gtbhkuyjqf.html

PHP:  $a && $b || !$c
来源：http://dali.nanxuanxn.top/Article/details/gtwqhduyxu.html

JS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtsbhbzntz.html

TS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtejaflvpp.html

Java: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtcnnaqzqb.html

Go:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtqzfipvsb.html

Ruby: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtkqlhpscr.html

C#:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtwbbbujsw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gtdvdauzxh.html

Py:   if not data: return
来源：http://dali.zdqjudy.top/Article/details/gtqlcepwlf.html

PHP:  if (!$data) { return; }
来源：http://dali.ppjwa.cn/Article/details/gtsqtutzxp.html

JS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtelrmxwef.html

TS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gthdqzgoem.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtwxbeiibx.html

Go:   if data == nil { return }
来源：http://dali.yanxiufei.cn/Article/details/gtnejycdex.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gtagicvzkm.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtrbnjauwy.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpynjetwu.html

C. 函数与作用域
来源：http://dali.yj202588.top/Article/details/gtvhdvqtze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsahdgnay.html

[C01] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtmdgaclhg.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigufen.top/Article/details/gtttfnvnnd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtlcakflyg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttorjqfma.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtbnhvywnj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gttnliwmmz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gtgqxnkdvx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuxming.cn/Article/details/gtwwyedhgo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtgvhjchzg.html

[C02] 默认参数
来源：http://dali.yvedp.cn/Article/details/gtwqwbagzr.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuafmeqpc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gtqovuoldg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtuijlfiza.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtuatvxrkf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aibaodan.cn/Article/details/gtrugccrcb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yonumen.top/Article/details/gtpsdqmsjd.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuetiantiany.cn/Article/details/gtgiaeoomh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenjidiqi.icu/Article/details/gtyeyyugwj.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjclifdgn.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuxming.cn/Article/details/gtedokaerx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hammf.cn/Article/details/gtenqelgdq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtksdcjrep.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gtxgmwfiou.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gtnxfoppzq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuetiantiany.cn/Article/details/gtidewrjuq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gtallegwcs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanliybfm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gtlozcwuml.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gtezrifoic.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtetbscjjs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gtxraxhzqb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtgbafrqvj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tianlin.xyz/Article/details/gtmlabnqfn.html

Go:   // 无：用配置结构体参数
来源：http://dali.ivvv.top/Article/details/gtdmxjfybc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtvlfwgddg.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtlpuecuja.html

[C05] 返回多个值
来源：http://dali.yj20258.top/Article/details/gtegylfioq.html

Py:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gtlvzwkdqc.html

PHP:  return [$a, $b];
来源：http://dali.gotoacloud.top/Article/details/gthugasfrb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtnhlxqexj.html

TS:   return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gtmrjlribw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuxming.cn/Article/details/gtgppxjcpz.html

Go:   return a, b
来源：http://dali.xuanzx.com/Article/details/gttzjhseod.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gtfcuswdup.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hongshengwenyu.top/Article/details/gttprknvdv.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258888.top/Article/details/gtzeyqqiln.html

Py:   square = lambda x: x * x
来源：http://dali.yanxiufei.cn/Article/details/gtfacdkrcr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoscvmphx.html

JS:   const square = x => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtyimcpuen.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtwcwqwyfn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtvdqkyjmm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gtjhilfkji.html

Ruby: square = ->(x) { x * x }
来源：http://dali.9152youxi.cn/Article/details/gttpshbpyb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gtmvapxbvk.html

[C07] 把函数作为参数传入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflaershq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hfpthk.cn/Article/details/gtsnjkbndr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtzzncvrjp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhixingplan.top/Article/details/gtgksytqvw.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gtifutthts.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtzwclmddn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.kuanghao11.cn/Article/details/gtjujhuabv.html

Ruby: arr.map(&:upcase)
来源：http://dali.fengsongda.top/Article/details/gtawxuylsu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zycfv.cn/Article/details/gthmbwegdy.html

[C08] 闭包
来源：http://dali.sweek.top/Article/details/gtriwptlea.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangdashe.top/Article/details/gtoeaakwmm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlupfldip.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdwgqqkth.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtsfdycyle.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tanke756.top/Article/details/gtlkamadom.html


<!-- 参考信息 -->