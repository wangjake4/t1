代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gzhubu.top/Article/details/gtpfaoqfht.html

Ruby: "Hello, #{name}!"
来源：http://dali.yj20258888.top/Article/details/gtkpugwydh.html

C#:   $"Hello, {name}!"
来源：http://dali.wangdashe.top/Article/details/gtdcgyvhyb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cashguo.top/Article/details/gtthtezzjw.html

Py:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtiqlmbrrd.html

PHP:  "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtadejkjmp.html

JS:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtwdoqhzye.html

TS:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtlnrpruac.html

Java: "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtufanzizj.html

Go:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtqlnwshey.html

Ruby: "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gtrjbmxklz.html

C#:   "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gtjpvfqyvq.html

[A14] 注释写法
来源：http://dali.xuetiantiany.cn/Article/details/gtshlhuoko.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hnxiangtu.top/Article/details/gtkgxxdutj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtqoxdygoc.html

JS:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gtrdkvyzrg.html

TS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtqeeasprz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.dianchejie.cn/Article/details/gtlksddhmx.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gtoruyvzmq.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shuidangran.top/Article/details/gtldojkrre.html

C#:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvthabnd.html

[A15] 空值判断与默认值
来源：http://dali.quarkkingdee.top/Article/details/gtmisxyads.html

Py:   value = data or "默认值"
来源：http://dali.cheryme.top/Article/details/gtygnsvfwd.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gtgkomjeuv.html

JS:   const value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtpalckyma.html

TS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gttgskiund.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ppjwa.cn/Article/details/gtjossrywa.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jqgufenzy.top/Article/details/gtgvohhgbq.html

Ruby: value = data || "默认值"
来源：http://dali.svipenyu.cn/Article/details/gtrhukkkku.html

C#:   var value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gttfnqageb.html

[A16] 真假值判断规则
来源：http://dali.kuanghao11.cn/Article/details/gtqewfuagj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvlexsti.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.pengpengdd.cyou/Article/details/gtafqaymbv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaimpbbb.html

TS:   if (!x) {}
来源：http://dali.dashuyun.cn/Article/details/gttblnudcq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvbyhgyb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.meibo888.top/Article/details/gtdmhidglb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.birdmap.top/Article/details/gtypjmxill.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtdxdxgqny.html

[A17] 位运算
来源：http://dali.xuetiantiany.cn/Article/details/gtrazfevdk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtbgcdnykc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ivvv.top/Article/details/gtnwsvgeuz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtbtnmacqk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtqafbhbwv.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtqzmjehit.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtiuuwuecm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gtzlgpvwcw.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtusssytwf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhengqikj.top/Article/details/gtkpngphzi.html

Py:   ord("A"); chr(65)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwzpqcvc.html

PHP:  ord("A"); chr(65)
来源：http://dali.nanxuanxn.top/Article/details/gtgwkatrgr.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.316326.xyz/Article/details/gtyewvjgwu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvkmrabt.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gtdywektmf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nwbrower.top/Article/details/gtmqtwqcot.html

Ruby: "A".ord; 65.chr
来源：http://dali.birdmap.top/Article/details/gtzgcgzhjy.html

C#:   (int)'A'; (char)65
来源：http://dali.wangshuangyany.cn/Article/details/gtetdvvmkp.html

[A19] 交换两个变量
来源：http://dali.hammf.cn/Article/details/gtnuewqdxd.html

Py:   a, b = b, a
来源：http://dali.cheryme.top/Article/details/gttxcwvvdi.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hammf.cn/Article/details/gtycdgujqn.html

JS:   [a, b] = [b, a];
来源：http://dali.ehwqpu.com/Article/details/gtounceehu.html

TS:   [a, b] = [b, a];
来源：http://dali.chenjidiqi.icu/Article/details/gtmgulcliq.html

Java: int t = a; a = b; b = t;
来源：http://dali.feifeiyinyue.top/Article/details/gtcpculowc.html

Go:   a, b = b, a
来源：http://dali.sweek.top/Article/details/gtmbvgkwqj.html

Ruby: a, b = b, a
来源：http://dali.cashguo.top/Article/details/gtqnznnebb.html

C#:   (a, b) = (b, a);
来源：http://dali.pycfn.com/Article/details/gtsebucfff.html

[A20] 读取标准输入
来源：http://dali.wangshuangyany.cn/Article/details/gtkbguspvt.html

Py:   name = input("请输入：")
来源：http://dali.ppjwa.cn/Article/details/gtikpkvirv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gzhubu.top/Article/details/gtgzqoyefj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cashguo.top/Article/details/gtcvctmkic.html

TS:   // Node.js：readline 模块
来源：http://dali.9152youxi.cn/Article/details/gtyqspnneh.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yonumen.top/Article/details/gttunmdxie.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jiagoushi.top/Article/details/gtlzjyapnc.html

Ruby: gets.chomp
来源：http://dali.nanxuanxn.top/Article/details/gtetmvfjof.html

C#:   Console.ReadLine();
来源：http://dali.zhongyouzk.top/Article/details/gtmzvnzved.html

[A21] 保留指定小数位输出
来源：http://dali.jyoumei.cn/Article/details/gtmczrmohr.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cqqwz.cn/Article/details/gtivpylbwj.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yj20258888.top/Article/details/gttpndrkau.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgutfdgch.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtpupbkoeb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtncqyzkbv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hfpthk.cn/Article/details/gtxkdikpfy.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtgyuvokas.html

C#:   3.14159.ToString("F2")
来源：http://dali.havefunace.top/Article/details/gtbdgqodfe.html

[A22] 获取字符串长度
来源：http://dali.birdmap.top/Article/details/gtnoyvqjqu.html

Py:   len(s)
来源：http://dali.0kj1m.cn/Article/details/gtxprmolkc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jiagoushi.top/Article/details/gtrvmlcbhv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hysaishi.cn/Article/details/gthtbthjzl.html

TS:   s.length
来源：http://dali.yanxiufei.cn/Article/details/gtwnlnijne.html

Java: s.length()
来源：http://dali.yongpay.top/Article/details/gtloyflgoi.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shzxlz.cn/Article/details/gtbljuxxdm.html

Ruby: s.length
来源：http://dali.xuetiantiany.cn/Article/details/gttxkyqfls.html

C#:   s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtxfdbltru.html

[A23] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtlmwkjhoi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zycfv.cn/Article/details/gtjdbxnukb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.316326.xyz/Article/details/gtbloidafs.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxuanxn.top/Article/details/gtwowtbqpo.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllzeerqs.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gtpvpeziny.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cucudq.cn/Article/details/gtxhlpsssw.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.birdmap.top/Article/details/gtqgbgamor.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.tanke756.top/Article/details/gtcuajcnso.html

[A24] 去除首尾空白
来源：http://dali.dashuyun.cn/Article/details/gtmjahbeja.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yueranfly.top/Article/details/gtcwiezowz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hongshengwenyu.top/Article/details/gtlilrpjth.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.aibaodan.cn/Article/details/gtyakxrluk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gzhubu.top/Article/details/gtnpvrnreo.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkujosrf.html

Go:   strings.TrimSpace(s)
来源：http://dali.dashuyun.cn/Article/details/gtzieeskxc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yongpay.top/Article/details/gtmxvbnmif.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.smart0.xyz/Article/details/gtqmxxqgdz.html

[A25] 字符串比较
来源：http://dali.xuanzx.com/Article/details/gtlgffpltv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.0kj1m.cn/Article/details/gtewxnysdt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.c1oappe.top/Article/details/gtwztmhljh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tianlin.xyz/Article/details/gtlhakfbbi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuanzx.com/Article/details/gtrmpbbuib.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shuidangran.top/Article/details/gtyvmxvetu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zdqjudy.top/Article/details/gtqjzbchsp.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tianlin.xyz/Article/details/gtlluugfbj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.bjfxy.top/Article/details/gtmzgcmrvu.html

[A26] 类型转换总览
来源：http://dali.zhengqikj.top/Article/details/gtyymjpygu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.316326.xyz/Article/details/gtreawsbca.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jqgufenzy.top/Article/details/gtadmxooel.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xuetiantiany.cn/Article/details/gtvdakogue.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sufxvd.cn/Article/details/gtxwkdpmib.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sweek.top/Article/details/gtgrsidraw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzooyslx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.redwolf501.top/Article/details/gtizewyhel.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinqigufen.top/Article/details/gttppdnojw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsbcemqdv.html

B. 流程控制
来源：http://dali.hammf.cn/Article/details/gtcxchvshz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkcvotvnt.html

[B01] 条件判断 if / else
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwqzknoi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nanxuanxn.top/Article/details/gtifbqjioz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nwbrower.top/Article/details/gtdheulyfl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtlstryces.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gtfaxqpfdo.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtxoylvltl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj202588.top/Article/details/gtzzdgfahi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zdqjudy.top/Article/details/gtpjtavhwp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gtkonrydkk.html

[B02] 多分支 else if / elif
来源：http://dali.chenjidiqi.icu/Article/details/gtoozfzxpl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fzhhl.top/Article/details/gtyzlmdmmu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shuidangran.top/Article/details/gtvriudqda.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gtoaajruqu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gtjkjvjpah.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gtzhjrbbpr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.c1oappe.top/Article/details/gtyeiiioae.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxuanxn.top/Article/details/gtfmsmpwzs.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtqtajzucb.html

[B03] switch / match / case
来源：http://dali.shuidangran.top/Article/details/gtzuiocsvr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hfpthk.cn/Article/details/gtmktfpxvs.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtxczwtsye.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtoavrinux.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtkjnoubwu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhengqikj.top/Article/details/gttlzusdrr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yongpay.top/Article/details/gtcfoqzuri.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.haohaochexian.top/Article/details/gtkbtzzvmp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiteljnxz.html

[B04] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtyepnomwr.html

Py:   for i in range(10): print(i)
来源：http://dali.yonumen.top/Article/details/gtlpbinfst.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ivvv.top/Article/details/gtbdjnohwj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.meibo888.top/Article/details/gtldygjejk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jiagoushi.top/Article/details/gtbttibrmz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuanzhike.top/Article/details/gtqllpichh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sufxvd.cn/Article/details/gttfpvfgsx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.andypj.xyz/Article/details/gthcqsoycs.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteavyfvkr.html

[B05] 遍历数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gtalkxtegn.html

Py:   for item in arr: print(item)
来源：http://dali.yj20258.top/Article/details/gtfsvxnsfs.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cucudq.cn/Article/details/gtqmcxpfje.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gtihzxlred.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtndckhgsz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlcvlmhu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.pycfn.com/Article/details/gtwpeelxnv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ehwqpu.com/Article/details/gtbvvnsqja.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cashguo.top/Article/details/gtqdxpboxe.html

[B06] 遍历字典 / 对象
来源：http://dali.redwolf501.top/Article/details/gtduwungjk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sweek.top/Article/details/gtnntefdio.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.smart0.xyz/Article/details/gtdstvcyhi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthuuaxgyd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gtkgidgxzx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gaohongyu789.top/Article/details/gtupanwrdu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zycfv.cn/Article/details/gtmnvmwkqe.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ybcxt.top/Article/details/gtqjezjhbq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guannengcc.top/Article/details/gtxbdaijkv.html

[B07] while 循环
来源：http://dali.yanxiufei.cn/Article/details/gtrcrotwpe.html

Py:   while i < 10: i += 1
来源：http://dali.aibaodan.cn/Article/details/gtuxhgxtyn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenzaomai.com/Article/details/gtwvoxeuds.html

JS:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtpvkkupaq.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtvkbtjnre.html

Java: while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gteljlkqwy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tianlin.xyz/Article/details/gtkvpftuxw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.daria6918.cn/Article/details/gtqoyhytzw.html

C#:   while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtcyxkmyvk.html

[B08] do-while（至少执行一次）
来源：http://dali.jinqigfzy.top/Article/details/gtsdftkjrk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ydzc1.top/Article/details/gtiktfmjwr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tanke756.top/Article/details/gtlzipyzxq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtgrgwrzgw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtakcmhlki.html

Java: do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtrylwizab.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gtsdhlnler.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhixingplan.top/Article/details/gtcmcornho.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzplroakh.html

[B09] break 与 continue
来源：http://dali.hfpthk.cn/Article/details/gthjccweoc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj202588.top/Article/details/gtjykxbovg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtppyjmynd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtfzemyygt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtjbdoshto.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gteykfnloc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gttvijadee.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gotoacloud.top/Article/details/gthfpltpsd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtsxmwxele.html

[B10] 遍历同时拿索引
来源：http://dali.daxiang520.top/Article/details/gtttjsyfhh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sweek.top/Article/details/gtlcqruidl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.svipenyu.cn/Article/details/gtsorezgkb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gteygzynjn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gtxpszigzn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guannengcc.top/Article/details/gtanpqkytu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shzxlz.cn/Article/details/gtzpbxyfxm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.birdmap.top/Article/details/gtnswfjrrq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.mhx1999.top/Article/details/gtvdllylxx.html

[B11] 生成数字序列 / 区间
来源：http://dali.hysaishi.cn/Article/details/gtyhltqbtq.html

Py:   list(range(0, 10, 2))
来源：http://dali.pycfn.com/Article/details/gtbtfyawyr.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gtkeouaiut.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ehwqpu.com/Article/details/gtzbtpcuog.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gtvhecdijg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zycfv.cn/Article/details/gtywapewmn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shzxlz.cn/Article/details/gtycldlwzi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gtiranjqzu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cashguo.top/Article/details/gtfplyktdz.html

[B12] 跳出多层循环
来源：http://dali.xuanzx.com/Article/details/gtpxzpuxeb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.0kj1m.cn/Article/details/gtorjkxnlg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgfzy.top/Article/details/gtxfbpqglq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtrrybaxxg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtgyqgbjux.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltbxjrpt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cashguo.top/Article/details/gtvvyzwikg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.redwolf501.top/Article/details/gtpogggnjj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenzaomai.com/Article/details/gtjpubuasx.html

[B13] 判断是否为数字
来源：http://dali.chenlongwang.top/Article/details/gtxxhhbrjk.html

Py:   isinstance(x, (int, float))
来源：http://dali.hywenlv.cn/Article/details/gtcqghsigc.html

PHP:  is_numeric($x)
来源：http://dali.shuidangran.top/Article/details/gtdozadind.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gtdxnjpckt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gtgdkemlrg.html

Java: x instanceof Number
来源：http://dali.nanxinkj.top/Article/details/gtrrneuesz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.quarkkingdee.top/Article/details/gtjnmioobp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.c1oappe.top/Article/details/gtsyynupfc.html

C#:   x is int or double or decimal
来源：http://dali.fengsongda.top/Article/details/gtelgrmifd.html

[B14] 判断值是否在集合内
来源：http://dali.meibo888.top/Article/details/gtkpykzwbd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guowangkeji.top/Article/details/gtpvzfoxwn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gttjchgnom.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtpruwqvuv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtaedioivr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xinyue.icu/Article/details/gthfttryvn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gtpaacuxpw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangdashe.top/Article/details/gtxmgzozxf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtjwddizbx.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gtlpcmxmbu.html

Py:   a and b or not c
来源：http://dali.haohaochexian.top/Article/details/gthvdqkbuf.html

PHP:  $a && $b || !$c
来源：http://dali.aizwys.cn/Article/details/gtqhzizchy.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtzfmcqxpw.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtuiyczdsy.html

Java: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtrabsdjrp.html

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtrrroytpv.html

Ruby: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtntpxynbr.html

C#:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcaqmtihs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj202588.top/Article/details/gtkzdzxfeu.html

Py:   if not data: return
来源：http://dali.guannengcc.top/Article/details/gtrkeiyqze.html

PHP:  if (!$data) { return; }
来源：http://dali.redwolf501.top/Article/details/gtdwlaxhqh.html

JS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gteozbwhkl.html

TS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gthedkclen.html

Java: if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtzgpimxao.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gtzpqnoaez.html

Ruby: return if data.nil?
来源：http://dali.hywenlv.cn/Article/details/gtxcrdqhar.html

C#:   if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gtrcgdjmtr.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtbwbbwjiy.html

C. 函数与作用域
来源：http://dali.dianchejie.cn/Article/details/gtzeenugtf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmparyqsz.html

[C01] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtmirxjlle.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtbmpefbkd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtsrpvdbwk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtaukqqwdu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtqyymbvkn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtasxgstag.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gtkqvbytkf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shangyingyoupin.top/Article/details/gtwgajxjxs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtfourvthn.html

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gtzwmgbyol.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigfzy.top/Article/details/gtzjifyozd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.dianchejie.cn/Article/details/gtknwokjcw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtbbsrafgm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtpqbqhyck.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigufen.top/Article/details/gtgcpbkukg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pengpengdd.cyou/Article/details/gthtesvwqj.html

Ruby: def greet(name = "World") = name
来源：http://dali.jiagoushi.top/Article/details/gtplnsygqs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gtrlivaxla.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gtmehxxtwq.html

Py:   def total(*args): return sum(args)
来源：http://dali.guannengcc.top/Article/details/gtujtojhmi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.c1oappe.top/Article/details/gtmgihaaei.html


<!-- 参考信息 -->