代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ehwqpu.com/Article/details/gtwykxdgds.html

JS:   `Hello, ${name}!`
来源：http://dali.ivvv.top/Article/details/gtkwgkzvlc.html

TS:   `Hello, ${name}!`
来源：http://dali.cheryme.top/Article/details/gttfaqiyyp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hfpthk.cn/Article/details/gtfoksqunb.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.316326.xyz/Article/details/gtarqbxblk.html

Ruby: "Hello, #{name}!"
来源：http://dali.yuxming.cn/Article/details/gtfnalnuzp.html

C#:   $"Hello, {name}!"
来源：http://dali.xziqi.cn/Article/details/gtlzfakmnj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yuanzhike.top/Article/details/gtadewskbn.html

Py:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtencfqycf.html

PHP:  "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gtgdfovtth.html

JS:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtibcjiwhj.html

TS:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtxhmkdysb.html

Java: "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gthuhoqkkt.html

Go:   "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtwqzwecoj.html

Ruby: "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtasqwtvcm.html

C#:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gttzcrtomy.html

[A14] 注释写法
来源：http://dali.snrcjt.cn/Article/details/gtslixxwuv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yj202588.top/Article/details/gtimwdiafu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkhdqzmc.html

JS:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gtdkeqamzj.html

TS:   // 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gthineedzz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hfpthk.cn/Article/details/gtilgsuoyw.html

Go:   // 单行；/* 多行 */
来源：http://dali.ehwqpu.com/Article/details/gtusmzuvzu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.birdmap.top/Article/details/gtlbdepire.html

C#:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gtzbttoxdq.html

[A15] 空值判断与默认值
来源：http://dali.tianlin.xyz/Article/details/gtrblhttmt.html

Py:   value = data or "默认值"
来源：http://dali.chenjidiqi.icu/Article/details/gtwvnyzjtk.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gtfsvumzlx.html

JS:   const value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gtflxoovsp.html

TS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtjogbboaw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.chenlongwang.top/Article/details/gtxlwndzgg.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.snrcjt.cn/Article/details/gtighckuoh.html

Ruby: value = data || "默认值"
来源：http://dali.zdqjudy.top/Article/details/gtsldgylsq.html

C#:   var value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gtswkdjowy.html

[A16] 真假值判断规则
来源：http://dali.iojbl.cn/Article/details/gtpvrobhqr.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.nanxuanxn.top/Article/details/gtzgscpggp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdbrmepe.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.andypj.xyz/Article/details/gtihcybijg.html

TS:   if (!x) {}
来源：http://dali.hywenlv.cn/Article/details/gtpnegoinq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhengqikj.top/Article/details/gtszqtslsd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.nanxuanxn.top/Article/details/gtptobmolt.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhiwuduotai.top/Article/details/gtxvqrlkbh.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zdqjudy.top/Article/details/gtvnmanlpx.html

[A17] 位运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyirrfjjk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtwrlvlnur.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yueranfly.top/Article/details/gtmjilblvj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gtuiajmwii.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gteivtctjw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gtfvcwydrd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtirimdqhj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtuwjnxdql.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtjbrkfnqa.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sysykeji.top/Article/details/gtlvdhzmlz.html

Py:   ord("A"); chr(65)
来源：http://dali.iojbl.cn/Article/details/gtmftlvoei.html

PHP:  ord("A"); chr(65)
来源：http://dali.ppjwa.cn/Article/details/gtfxwgswwu.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xuetiantiany.cn/Article/details/gtxrdrmyxn.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqzjectm.html

Java: (int) 'A'; (char) 65
来源：http://dali.cucudq.cn/Article/details/gtevuublvy.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hywenlv.cn/Article/details/gtpjiheruh.html

Ruby: "A".ord; 65.chr
来源：http://dali.shuidangran.top/Article/details/gtkeljbhlo.html

C#:   (int)'A'; (char)65
来源：http://dali.redwolf501.top/Article/details/gtkdtenqhc.html

[A19] 交换两个变量
来源：http://dali.sweek.top/Article/details/gtfynlurbs.html

Py:   a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gtjhltrhzn.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflkgitil.html

JS:   [a, b] = [b, a];
来源：http://dali.hysaishi.cn/Article/details/gtiirnsaoz.html

TS:   [a, b] = [b, a];
来源：http://dali.zycfv.cn/Article/details/gtqljttnzc.html

Java: int t = a; a = b; b = t;
来源：http://dali.cdnleiting.top/Article/details/gtoemznafa.html

Go:   a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gtzmwcxika.html

Ruby: a, b = b, a
来源：http://dali.zycfv.cn/Article/details/gtghcqczca.html

C#:   (a, b) = (b, a);
来源：http://dali.hnqzz.top/Article/details/gthgrhsotu.html

[A20] 读取标准输入
来源：http://dali.yvedp.cn/Article/details/gtevgcqxdf.html

Py:   name = input("请输入：")
来源：http://dali.yongpay.top/Article/details/gtngrtucmi.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhnewklh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhoulong.xyz/Article/details/gthfjwfjsz.html

TS:   // Node.js：readline 模块
来源：http://dali.nanxinkj.top/Article/details/gtajbmdext.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shuidangran.top/Article/details/gtnvbswenn.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tianlin.xyz/Article/details/gtqsuftqml.html

Ruby: gets.chomp
来源：http://dali.nanxinkj.top/Article/details/gtsylsrayd.html

C#:   Console.ReadLine();
来源：http://dali.zhiwuduotai.top/Article/details/gtmpbvitfg.html

[A21] 保留指定小数位输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouuzbxwg.html

Py:   f"{3.14159:.2f}"
来源：http://dali.chenzaomai.com/Article/details/gtnoxyxrdw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gtabzxmfjl.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtgnisrazp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtlmsdsbvr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gtoheukejv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.wangshuangyany.cn/Article/details/gtbanhvxwq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gtbztpughj.html

C#:   3.14159.ToString("F2")
来源：http://dali.zycfv.cn/Article/details/gthemyyrxk.html

[A22] 获取字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtltoojyca.html

Py:   len(s)
来源：http://dali.0kj1m.cn/Article/details/gtnimidvtq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tian-w.cn/Article/details/gtgtqfjazp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ivvv.top/Article/details/gtiafdrkce.html

TS:   s.length
来源：http://dali.zhengqikj.top/Article/details/gtogqpwlmr.html

Java: s.length()
来源：http://dali.jyoumei.cn/Article/details/gtepjldnrf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.birdmap.top/Article/details/gtavuwcrok.html

Ruby: s.length
来源：http://dali.iojbl.cn/Article/details/gtjpnzfbqq.html

C#:   s.Length
来源：http://dali.aibaodan.cn/Article/details/gtndxljceh.html

[A23] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtqtkjjfqt.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.c1oappe.top/Article/details/gteosiovvk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.havefunace.top/Article/details/gtqmjelbgk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gtpzshsxnr.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gtsjkasigz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gtnukekzjm.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.aizwys.cn/Article/details/gtsjmzythr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.iojbl.cn/Article/details/gtnvhdjvia.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.tianlin.xyz/Article/details/gtqioymvjo.html

[A24] 去除首尾空白
来源：http://dali.yj20258.top/Article/details/gtshbbqwxb.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jyoumei.cn/Article/details/gtqdnpsksg.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukczlyvq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.redwolf501.top/Article/details/gtcghhpqaz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258888.top/Article/details/gtlasmyuty.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenzaomai.com/Article/details/gtguyxdouf.html

Go:   strings.TrimSpace(s)
来源：http://dali.tianlin.xyz/Article/details/gtiurmxlzh.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.mhx1999.top/Article/details/gtbwdbmxfk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shzxlz.cn/Article/details/gtuxuoirug.html

[A25] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtytjczigk.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fzhhl.top/Article/details/gtxucdwnsw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmdoemxd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtealepdsn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gtlhayxnvr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangdashe.top/Article/details/gtqlitegto.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj20258.top/Article/details/gtzifqmyet.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.kuanghao11.cn/Article/details/gtrvmihlei.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gtcukfugar.html

[A26] 类型转换总览
来源：http://dali.redwolf501.top/Article/details/gtjorohxns.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sxryk.cn/Article/details/gtjesfuokd.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gotoacloud.top/Article/details/gtqlzgumaq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.daxiang520.top/Article/details/gtxqnnokwd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.meibo888.top/Article/details/gtsezblzja.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.iojbl.cn/Article/details/gtifbsmziy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.smart0.xyz/Article/details/gtxfmuvwxc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sufxvd.cn/Article/details/gtekqhbwjd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gtnyikqtwu.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgegqxpol.html

B. 流程控制
来源：http://dali.pycfn.com/Article/details/gteixquqrl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtpqcncqif.html

[B01] 条件判断 if / else
来源：http://dali.guannengcc.top/Article/details/gturnkhsrn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yueranfly.top/Article/details/gtlojixohm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hnqzz.top/Article/details/gtqewkjckj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gtuwlvokfz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gtfgxwwjju.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtizcpkibf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cheryme.top/Article/details/gtwukyeqtw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gaohongyu789.top/Article/details/gtbdxkdhan.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpecxbgjo.html

[B02] 多分支 else if / elif
来源：http://dali.zhongyouzk.top/Article/details/gtfcaeinjl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yuanzhike.top/Article/details/gtxxriirdp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cdnleiting.top/Article/details/gtucmrwagv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gttkpxveuv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gtvwgqdmab.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtbjdsdimt.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.quarkkingdee.top/Article/details/gtisyfstwo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xuetiantiany.cn/Article/details/gtkuywbqjq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtprysfbxw.html

[B03] switch / match / case
来源：http://dali.cdnleiting.top/Article/details/gtllkurzzt.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yanxiufei.cn/Article/details/gthtiwnzym.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gtbeibkzoc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtumrsqzqw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gtxlhgnnod.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtybyugzpk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xziqi.cn/Article/details/gttipoggnw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinqigufen.top/Article/details/gtlkbgklwu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.0kj1m.cn/Article/details/gtzwmiiydp.html

[B04] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtlftdtmad.html

Py:   for i in range(10): print(i)
来源：http://dali.yangfankeji.com/Article/details/gtncdcnoxn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yongpay.top/Article/details/gtwbnhvdbw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gtpfemyele.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xylfe.cn/Article/details/gtcvazozjj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nwbrower.top/Article/details/gtjlvibtdj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.smart0.xyz/Article/details/gtwtkmhuhm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hfpthk.cn/Article/details/gtsdmexypq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhixingplan.top/Article/details/gtyrhjelmp.html

[B05] 遍历数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtbgxrulyj.html

Py:   for item in arr: print(item)
来源：http://dali.hysaishi.cn/Article/details/gtvrarslja.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gogol.net.cn/Article/details/gtbpzcvqdd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gtelkayrqk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtmifndopi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xziqi.cn/Article/details/gthuawmnmx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgfzy.top/Article/details/gtunvdqmwh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.316326.xyz/Article/details/gthjuyzcgr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtkpmrkwbx.html

[B06] 遍历字典 / 对象
来源：http://dali.jqgufenzy.top/Article/details/gtghcjdoqg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xuetiantiany.cn/Article/details/gtbqvjznrp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shangyingyoupin.top/Article/details/gttposfcsk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtlgbzqzya.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenzaomai.com/Article/details/gtemdercop.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tanke756.top/Article/details/gtpipkmbxz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yvedp.cn/Article/details/gtygpxwvjc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspplugll.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gtymhhcxww.html

[B07] while 循环
来源：http://dali.yongpay.top/Article/details/gtuomdxhzl.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gtwzbqojno.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258.top/Article/details/gtmqvwbexu.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtfrcziujt.html

TS:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gthfjjvawo.html

Java: while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtebqvefee.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258.top/Article/details/gtrsmrmxov.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuanzhike.top/Article/details/gtfgeumlsu.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtnebqrdhs.html

[B08] do-while（至少执行一次）
来源：http://dali.mhx1999.top/Article/details/gtanleffnn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cucudq.cn/Article/details/gtsbxsggdj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtotmwjzbr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtwgdgintb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtfuzafmcs.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtuygptngk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yvedp.cn/Article/details/gteiejrool.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.feifeiyinyue.top/Article/details/gtqbrmwvjd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gthsijpdcy.html

[B09] break 与 continue
来源：http://dali.gogol.net.cn/Article/details/gthmpmtndr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gtuzyibkpd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtplldijjw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtzmlmnnzp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gttylulgiq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtlbgtrhrp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxsyasjm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.pycfn.com/Article/details/gtdvvddzgz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtmvrpjwir.html

[B10] 遍历同时拿索引
来源：http://dali.yangfankeji.com/Article/details/gtmztkmciz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tianlin.xyz/Article/details/gtnjvmbnld.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.meibo888.top/Article/details/gtlnkuroic.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.redwolf501.top/Article/details/gthyhukihp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtktpsniuu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.andypj.xyz/Article/details/gttvctepjg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.smart0.xyz/Article/details/gtgfncktok.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zdqjudy.top/Article/details/gtoecqfyro.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gteaouvbez.html

[B11] 生成数字序列 / 区间
来源：http://dali.yvedp.cn/Article/details/gtlkwrkpeg.html

Py:   list(range(0, 10, 2))
来源：http://dali.hysaishi.cn/Article/details/gtgqsrbcgy.html

PHP:  range(0, 10, 2);
来源：http://dali.9152youxi.cn/Article/details/gtcyeftzjf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtwsdemmcj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtesyatkgq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.andypj.xyz/Article/details/gtpqakwhfx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigufen.top/Article/details/gthekvuvrg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sxryk.cn/Article/details/gtthvzoics.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnxiangtu.top/Article/details/gtvatwwhkr.html

[B12] 跳出多层循环
来源：http://dali.aizwys.cn/Article/details/gtmifxmpiq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cashguo.top/Article/details/gtzahparyv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sxryk.cn/Article/details/gtnqfytkck.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtjdwknngp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtdbfgmtwi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtcgzrncin.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gtwbhifeop.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guowangkeji.top/Article/details/gtdsyuxrcy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cashguo.top/Article/details/gtforfnpsg.html

[B13] 判断是否为数字
来源：http://dali.chenzaomai.com/Article/details/gtizblzzqg.html

Py:   isinstance(x, (int, float))
来源：http://dali.pycfn.com/Article/details/gtxftitxqs.html

PHP:  is_numeric($x)
来源：http://dali.redwolf501.top/Article/details/gtvbylhwmh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtsgbdjkfl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gtlaxzpwbl.html

Java: x instanceof Number
来源：http://dali.jqgfzy.top/Article/details/gtyxbjbrlp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gtpjniggps.html

Ruby: x.is_a?(Numeric)
来源：http://dali.havefunace.top/Article/details/gtvuhrzcvv.html

C#:   x is int or double or decimal
来源：http://dali.quarkkingdee.top/Article/details/gtffzauwcn.html

[B14] 判断值是否在集合内
来源：http://dali.shzxlz.cn/Article/details/gtaccadyfa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ppjwa.cn/Article/details/gtpfckrwqv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gaohongyu789.top/Article/details/gtlcbhtbju.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtxhthfhir.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtrgsbwzxj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtjkcmkdum.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtiolgxtlu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtmdpiawcs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtogrgbfzx.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gtwcoiykea.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gtekdzcjtx.html

PHP:  $a && $b || !$c
来源：http://dali.iojbl.cn/Article/details/gtbzddieva.html

JS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtqjstyimk.html

TS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtwuqftkcb.html

Java: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtspwuhnxq.html

Go:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtljffabyu.html

Ruby: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtjxjequrt.html

C#:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtwgqgeeaz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxinkj.top/Article/details/gtdwuvohiq.html

Py:   if not data: return
来源：http://dali.andypj.xyz/Article/details/gtgsrdojae.html

PHP:  if (!$data) { return; }
来源：http://dali.jlsjyb.cn/Article/details/gtkcappdqu.html

JS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtpmmwuafn.html

TS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtmfqmpikd.html

Java: if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gtgirczyoo.html

Go:   if data == nil { return }
来源：http://dali.daria6918.cn/Article/details/gtppsyovev.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gtljfejwxq.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gttyyeqmkz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtimunzwzb.html

C. 函数与作用域
来源：http://dali.0kj1m.cn/Article/details/gtkkhkfroo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiqzaiah.html

[C01] 定义函数
来源：http://dali.birdmap.top/Article/details/gtewwbjiet.html

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gtnvdmaqhb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtzxoauqau.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtvpggexpu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrqmnjgyp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtbadnaijx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigufen.top/Article/details/gtykoqrute.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gotoacloud.top/Article/details/gtatwclszk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtunpwdhhg.html

[C02] 默认参数
来源：http://dali.aizwys.cn/Article/details/gtxunuansa.html

Py:   def greet(name="World"): return name
来源：http://dali.yueranfly.top/Article/details/gtggankjru.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yueranfly.top/Article/details/gtrsirzklz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtqufctoyz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtrthvnlwe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gtfmfbaljg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigfzy.top/Article/details/gtyqmdrvzo.html

Ruby: def greet(name = "World") = name
来源：http://dali.jianghu66.top/Article/details/gtfnbdhokq.html


<!-- 参考信息 -->