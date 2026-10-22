代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtwlmobcmz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnacocbm.html

Go:   // 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gthalvyqdf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xuetiantiany.cn/Article/details/gtegvpcjfp.html

C#:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtfbeoipyt.html

[A15] 空值判断与默认值
来源：http://dali.zhoulong.xyz/Article/details/gtrbvbvwpz.html

Py:   value = data or "默认值"
来源：http://dali.shanyushiyangtech.top/Article/details/gtrghjwkpf.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gtunwcspkq.html

JS:   const value = data ?? "默认值";
来源：http://dali.yj202588.top/Article/details/gtvzsjpqtj.html

TS:   const value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gtztzrdjgu.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.daxiang520.top/Article/details/gtjakovmmm.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yj20258.top/Article/details/gthmgqyvcv.html

Ruby: value = data || "默认值"
来源：http://dali.sysykeji.top/Article/details/gtfilyzmfx.html

C#:   var value = data ?? "默认值";
来源：http://dali.zdqjudy.top/Article/details/gtlpkhqixc.html

[A16] 真假值判断规则
来源：http://dali.yj20258888.top/Article/details/gtjxlcuubw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hywenlv.cn/Article/details/gtdcmfuiig.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.nwbrower.top/Article/details/gtfvmkzpem.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.nanxinkj.top/Article/details/gtfpbpvuyh.html

TS:   if (!x) {}
来源：http://dali.nanxinkj.top/Article/details/gtgidpgdar.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cheryme.top/Article/details/gtxqnbfuft.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gogol.net.cn/Article/details/gtphajkvuc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jianghu66.top/Article/details/gtisqgsvuj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtcespeccn.html

[A17] 位运算
来源：http://dali.jianghu66.top/Article/details/gtqgjhavzf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gtwqctfcuw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nwbrower.top/Article/details/gtalhddqrm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtjbaasqko.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gthsfuyqyp.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtvckandcf.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtmwuwhups.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gthxcfuors.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtuzykacsx.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cashguo.top/Article/details/gtudjujvso.html

Py:   ord("A"); chr(65)
来源：http://dali.quarkkingdee.top/Article/details/gtizstfyds.html

PHP:  ord("A"); chr(65)
来源：http://dali.jqgfzy.top/Article/details/gtgpylypet.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fzhhl.top/Article/details/gtzobenxub.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ppjwa.cn/Article/details/gtjiohuirf.html

Java: (int) 'A'; (char) 65
来源：http://dali.nwbrower.top/Article/details/gtikhkcirz.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.redwolf501.top/Article/details/gtcasucxhk.html

Ruby: "A".ord; 65.chr
来源：http://dali.ehwqpu.com/Article/details/gtuhttmldi.html

C#:   (int)'A'; (char)65
来源：http://dali.aizwys.cn/Article/details/gtznpquosr.html

[A19] 交换两个变量
来源：http://dali.pycfn.com/Article/details/gtitxzqxpi.html

Py:   a, b = b, a
来源：http://dali.yuanzhike.top/Article/details/gtriobpvqw.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ydzc1.top/Article/details/gtnxosjmtm.html

JS:   [a, b] = [b, a];
来源：http://dali.smart0.xyz/Article/details/gtjhjwnrmj.html

TS:   [a, b] = [b, a];
来源：http://dali.jiagoushi.top/Article/details/gttpavrdus.html

Java: int t = a; a = b; b = t;
来源：http://dali.chenlongwang.top/Article/details/gtisjjtyvh.html

Go:   a, b = b, a
来源：http://dali.shangyingyoupin.top/Article/details/gtoganjfkh.html

Ruby: a, b = b, a
来源：http://dali.svipenyu.cn/Article/details/gtbefelfil.html

C#:   (a, b) = (b, a);
来源：http://dali.pycfn.com/Article/details/gtaoiesglr.html

[A20] 读取标准输入
来源：http://dali.pycfn.com/Article/details/gtjahlkrju.html

Py:   name = input("请输入：")
来源：http://dali.ybcxt.top/Article/details/gtabpvdxli.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.tianlin.xyz/Article/details/gteulldfqg.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ybcxt.top/Article/details/gtjuyinwdj.html

TS:   // Node.js：readline 模块
来源：http://dali.hnxiangtu.top/Article/details/gtuaipbmkp.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.aizwys.cn/Article/details/gtagafyrpg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.guannengcc.top/Article/details/gthioldtjf.html

Ruby: gets.chomp
来源：http://dali.jiagoushi.top/Article/details/gthdgdsydj.html

C#:   Console.ReadLine();
来源：http://dali.yj202588.top/Article/details/gtcgqavdyi.html

[A21] 保留指定小数位输出
来源：http://dali.havefunace.top/Article/details/gtdowlfzsb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shangyingyoupin.top/Article/details/gtbruorxnj.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtympyqjfo.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gtixrvixms.html

TS:   (3.14159).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtlfuqkgso.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jlsjyb.cn/Article/details/gtplluvytq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gtzvumuyue.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gtyuansyfy.html

C#:   3.14159.ToString("F2")
来源：http://dali.yj20258888.top/Article/details/gtdqjaxxyw.html

[A22] 获取字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtviklsknr.html

Py:   len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulhddhzx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibbucrdt.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.bjfxy.top/Article/details/gttctmmsxj.html

TS:   s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwoxaani.html

Java: s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtrmakfsnj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nanxinkj.top/Article/details/gtwhskngwg.html

Ruby: s.length
来源：http://dali.yangfankeji.com/Article/details/gtjscqaalq.html

C#:   s.Length
来源：http://dali.andypj.xyz/Article/details/gtxgepasdf.html

[A23] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtapvigkzp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhoulong.xyz/Article/details/gthbjxkbfd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.smart0.xyz/Article/details/gtrndsbzlk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cqqwz.cn/Article/details/gtgreoqujj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gtwzuvzcca.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gaohongyu789.top/Article/details/gtmwlbmybb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhengqikj.top/Article/details/gtexrmubea.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gtzghkxnff.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.9152youxi.cn/Article/details/gtfosilugj.html

[A24] 去除首尾空白
来源：http://dali.hammf.cn/Article/details/gtxqlsqzkx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.haohaochexian.top/Article/details/gtdyamlrcc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.9152youxi.cn/Article/details/gtsjkduslw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtaskzttnd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gogol.net.cn/Article/details/gtzzytappo.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhwzfpkm.html

Go:   strings.TrimSpace(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtbmzhjzeq.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jiagoushi.top/Article/details/gtfsxnhihs.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.nanxuanxn.top/Article/details/gtlqtdgagv.html

[A25] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtditcuogp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xylfe.cn/Article/details/gtrjuluptr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gotoacloud.top/Article/details/gtxniyabrr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuanzhike.top/Article/details/gtjktwnbmg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.feifeiyinyue.top/Article/details/gtcpgzqqcm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.havefunace.top/Article/details/gtkrovrczp.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.dianchejie.cn/Article/details/gtnvbbchjd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dashuyun.cn/Article/details/gtycevcuyz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gtkolpltfn.html

[A26] 类型转换总览
来源：http://dali.cashguo.top/Article/details/gtlmsabsat.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.feifeiyinyue.top/Article/details/gtafykubvs.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfygrpse.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjkpllus.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nwbrower.top/Article/details/gtwrxtmhiq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gtrchdozmh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.feifeiyinyue.top/Article/details/gtlrtgdfdy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ehwqpu.com/Article/details/gtuudjhcoa.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sysykeji.top/Article/details/gtyhvswzfc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqbysmntu.html

B. 流程控制
来源：http://dali.gaohongyu789.top/Article/details/gtdjwpvfkf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtpbkkmjdp.html

[B01] 条件判断 if / else
来源：http://dali.guowangkeji.top/Article/details/gtambwbaqd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hysaishi.cn/Article/details/gtmalgkqgc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sufxvd.cn/Article/details/gtctaapggp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gtzvunflhm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtoaxdwypk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gtlgvwjtai.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.snrcjt.cn/Article/details/gtsqbmmpxw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hammf.cn/Article/details/gtxlkzmfib.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtjymvmuvw.html

[B02] 多分支 else if / elif
来源：http://dali.ppjwa.cn/Article/details/gtsqjgrhgg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cqqwz.cn/Article/details/gtwgiktodk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.redwolf501.top/Article/details/gtvcodkgek.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gtwrmlwaif.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gtoujdajzk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtlknilxdy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.feifeiyinyue.top/Article/details/gtkxxmykjl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gotoacloud.top/Article/details/gtkrgtxkns.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtrrbenkzn.html

[B03] switch / match / case
来源：http://dali.zdqjudy.top/Article/details/gtouxclfht.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinqigufen.top/Article/details/gtjdtvkmdz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gtfnqzblsg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gtenxbxarc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtfjgqbmmj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtqitgqeic.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cucudq.cn/Article/details/gtwhpmwhom.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.aizwys.cn/Article/details/gttyxxfkjc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gotoacloud.top/Article/details/gtamxqsnse.html

[B04] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtwgxyedpu.html

Py:   for i in range(10): print(i)
来源：http://dali.xuanzx.com/Article/details/gtigknkamb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhijiandao.cn/Article/details/gtwrfmuvzq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtgrgntwws.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioertfry.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.guannengcc.top/Article/details/gtqjlprvkh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhongyouzk.top/Article/details/gtifkllynr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenjidiqi.icu/Article/details/gtislratwh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jyoumei.cn/Article/details/gtyfynkezs.html

[B05] 遍历数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtecugeqeb.html

Py:   for item in arr: print(item)
来源：http://dali.yj202588.top/Article/details/gtkmeqwzpw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sxryk.cn/Article/details/gtwapwtvcr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gtkfedmjrg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtftrljmiy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sysykeji.top/Article/details/gtcgigqlgp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cdnleiting.top/Article/details/gtyyrkdvfy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gtsxesucbh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtrzneadlk.html

[B06] 遍历字典 / 对象
来源：http://dali.bjfxy.top/Article/details/gtckwbkssk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenzaomai.com/Article/details/gtqdtwvvdx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvkpblbwj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hongshengwenyu.top/Article/details/gtewftthiv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daria6918.cn/Article/details/gturkmxung.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yonumen.top/Article/details/gtnyrybmyk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zycfv.cn/Article/details/gtphheolyh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yvedp.cn/Article/details/gtmdsautdd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhengqikj.top/Article/details/gtalmtrssx.html

[B07] while 循环
来源：http://dali.cheryme.top/Article/details/gteqrqdhes.html

Py:   while i < 10: i += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegyehwdw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gthxqfjjer.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtchlvfxay.html

TS:   while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gtdpcytuhj.html

Java: while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtnsdfizui.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zycfv.cn/Article/details/gtsclzkpee.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258.top/Article/details/gtnzoanobj.html

C#:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtkgaybgpd.html

[B08] do-while（至少执行一次）
来源：http://dali.dianchejie.cn/Article/details/gtgkqhfgoq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhoulong.xyz/Article/details/gtefzqkppv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tian-w.cn/Article/details/gtspctdbpl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtvvvctrle.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtqqkedbaj.html

Java: do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtviicrurk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.bjfxy.top/Article/details/gtghefrwem.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.316326.xyz/Article/details/gtxpqjceyr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtkkaojoye.html

[B09] break 与 continue
来源：http://dali.ybcxt.top/Article/details/gtnythfkgo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigufen.top/Article/details/gtozuctyaw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gthsiuoqjq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtawcknoop.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtzbjvwere.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gttkwowgdb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhengqikj.top/Article/details/gtxkgvrbhu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.svipenyu.cn/Article/details/gtvauhembv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtlqnvao.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gtecjaaijd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xziqi.cn/Article/details/gtiexmotmv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cucudq.cn/Article/details/gtipfbqjlv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xziqi.cn/Article/details/gtwqgfwcal.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gthqmqptsy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ehwqpu.com/Article/details/gttvjxhhul.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jlsjyb.cn/Article/details/gtwhgmtnsm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.316326.xyz/Article/details/gtokamypxh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gttbszthrf.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenzaomai.com/Article/details/gttdwewcqc.html

Py:   list(range(0, 10, 2))
来源：http://dali.yvedp.cn/Article/details/gtobfwrisr.html

PHP:  range(0, 10, 2);
来源：http://dali.0kj1m.cn/Article/details/gtzchwnkxk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtpwmgshof.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gtuegrzvom.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenlongwang.top/Article/details/gtfpkokgrs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ybcxt.top/Article/details/gtwgeimdtg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.smart0.xyz/Article/details/gtxpdpthkn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gtaellemkm.html

[B12] 跳出多层循环
来源：http://dali.tianlin.xyz/Article/details/gtlukwavfs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nwbrower.top/Article/details/gtohkppfap.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhengqikj.top/Article/details/gtdefbluwx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtrbvpitxk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtysxwvknt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtajwwirsc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovcimchy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.redwolf501.top/Article/details/gtkcdbhwlu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shuidangran.top/Article/details/gthidmmoql.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyptzunr.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuxming.cn/Article/details/gtmjoqnzhf.html

PHP:  is_numeric($x)
来源：http://dali.tian-w.cn/Article/details/gtfeolqvca.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbknqaag.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gttqhhuuin.html

Java: x instanceof Number
来源：http://dali.smart0.xyz/Article/details/gtbxhffwit.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gaohongyu789.top/Article/details/gtvubajsbv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnqzz.top/Article/details/gtmasdzdqe.html

C#:   x is int or double or decimal
来源：http://dali.hammf.cn/Article/details/gtdfjjrtds.html

[B14] 判断值是否在集合内
来源：http://dali.svipenyu.cn/Article/details/gtiykxrajc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmykkgqs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ivvv.top/Article/details/gtujhyrgdt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtclbpxpyw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtnmfmoxfx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtjxpikdgv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.snrcjt.cn/Article/details/gtkfmeoswc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtfbvhatue.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyorzikwz.html

[B15] 布尔运算与取反
来源：http://dali.yongpay.top/Article/details/gtarneqlis.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtrakcrzfv.html

PHP:  $a && $b || !$c
来源：http://dali.ydzc1.top/Article/details/gttinptbhl.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtvpcbpkpm.html

TS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtnjhxrpmp.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtaysmhdhb.html

Go:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gteoxcawrx.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtxhexkvxk.html

C#:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtugfrubko.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cucudq.cn/Article/details/gthqffhpci.html

Py:   if not data: return
来源：http://dali.nanxinkj.top/Article/details/gtddzavsrd.html

PHP:  if (!$data) { return; }
来源：http://dali.yuanzhike.top/Article/details/gttjlfyana.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltkwkcbf.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtaqcqqsjn.html

Java: if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gttudbwowf.html

Go:   if data == nil { return }
来源：http://dali.316326.xyz/Article/details/gtjflxbmhw.html

Ruby: return if data.nil?
来源：http://dali.cashguo.top/Article/details/gtumfhkmbc.html

C#:   if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gtjnxwisdk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxseqxxoe.html

C. 函数与作用域
来源：http://dali.sufxvd.cn/Article/details/gtgbcgqsye.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwfhrumev.html

[C01] 定义函数
来源：http://dali.pycfn.com/Article/details/gthsgablgl.html

Py:   def add(a, b): return a + b
来源：http://dali.9152youxi.cn/Article/details/gtvdvvkkxo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpasrcpn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtvwxlymmh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtrrdklmao.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtjpnektgb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.316326.xyz/Article/details/gtqlhyqoln.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhixingplan.top/Article/details/gtavmhgoeq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtfsmzyrxa.html

[C02] 默认参数
来源：http://dali.smart0.xyz/Article/details/gtdwtagkwn.html

Py:   def greet(name="World"): return name
来源：http://dali.hammf.cn/Article/details/gtvhfmhbcd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guowangkeji.top/Article/details/gtpghzjxjn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtnskunnhb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtpscvyqht.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhongyouzk.top/Article/details/gtokqrxciz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.feifeiyinyue.top/Article/details/gtwzhmeicp.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gtbbpvqswf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hfpthk.cn/Article/details/gtituzudwt.html

[C03] 可变参数
来源：http://dali.daria6918.cn/Article/details/gthbsxeuzo.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnqzz.top/Article/details/gttdnzxjpo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gtfsdbgccj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtijdnjrsh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gtktiktxtc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aibaodan.cn/Article/details/gtazalrqry.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyyhoxgh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hfpthk.cn/Article/details/gtmyhhvuvz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.redwolf501.top/Article/details/gtprrcqgrt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gtzsnklust.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gtfblrdrzg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.c1oappe.top/Article/details/gtmghnkaak.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gtxlmdtsjf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gteposfqvq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuanzhike.top/Article/details/gtnmeuohna.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkcvxmgq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtbmeqslbg.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtqilvvxqa.html

[C05] 返回多个值
来源：http://dali.yongpay.top/Article/details/gtlyaqduds.html


<!-- 参考信息 -->