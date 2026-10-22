代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2frsejdds.html

TS:   const value = data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gt2yyzcupsh.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zdqjudy.top/Article/details/gt2pouhjlvh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yvedp.cn/Article/details/gt2bqaaubbd.html

Ruby: value = data || "默认值"
来源：http://dali.guannengcc.top/Article/details/gt2ajusulws.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gt2ztwasyst.html

[A16] 真假值判断规则
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqldetpf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.wangshuangyany.cn/Article/details/gt2vyxyllmu.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.chenjidiqi.icu/Article/details/gt2sycsunst.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gogol.net.cn/Article/details/gt2kguggkcj.html

TS:   if (!x) {}
来源：http://dali.zycfv.cn/Article/details/gt2cpthmzyo.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.nwbrower.top/Article/details/gt2llwsxglz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.bjfxy.top/Article/details/gt2jcooirpi.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.guowangkeji.top/Article/details/gt2emraiolk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hywenlv.cn/Article/details/gt2yjarfxgm.html

[A17] 位运算
来源：http://dali.haohaochexian.top/Article/details/gt2nilfewls.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2rueswbja.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zdqjudy.top/Article/details/gt2hjimtocy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2goihobjr.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gt2tkbqfbjc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gt2hjvsutlz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gt2uvcrnoxy.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gt2peyzzosb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gt2tgexuuit.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yueranfly.top/Article/details/gt2xwkarjiy.html

Py:   ord("A"); chr(65)
来源：http://dali.yj20258.top/Article/details/gt2tkcvbejh.html

PHP:  ord("A"); chr(65)
来源：http://dali.ydzc1.top/Article/details/gt2vvcstpig.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlctnlbz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njlgxrfw.html

Java: (int) 'A'; (char) 65
来源：http://dali.gaohongyu789.top/Article/details/gt2ifholvbn.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.tianlin.xyz/Article/details/gt2cymeymgw.html

Ruby: "A".ord; 65.chr
来源：http://dali.svipenyu.cn/Article/details/gt2jowwwpvt.html

C#:   (int)'A'; (char)65
来源：http://dali.hfpthk.cn/Article/details/gt2lsbwrjxj.html

[A19] 交换两个变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vsddbxgx.html

Py:   a, b = b, a
来源：http://dali.zycfv.cn/Article/details/gt2jsrcfque.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.vqdsnc.cn/Article/details/gt2cfoftcsa.html

JS:   [a, b] = [b, a];
来源：http://dali.yj20258888.top/Article/details/gt2pkypjyda.html

TS:   [a, b] = [b, a];
来源：http://dali.9152youxi.cn/Article/details/gt2qszqfwaz.html

Java: int t = a; a = b; b = t;
来源：http://dali.nanxuanxn.top/Article/details/gt2saqvnovs.html

Go:   a, b = b, a
来源：http://dali.dashuyun.cn/Article/details/gt2qzljpawh.html

Ruby: a, b = b, a
来源：http://dali.zhongyouzk.top/Article/details/gt2ppksvbhv.html

C#:   (a, b) = (b, a);
来源：http://dali.jiagoushi.top/Article/details/gt2tqxqzxvp.html

[A20] 读取标准输入
来源：http://dali.shzxlz.cn/Article/details/gt2bzznxcjx.html

Py:   name = input("请输入：")
来源：http://dali.pycfn.com/Article/details/gt2vujgwrtt.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.pycfn.com/Article/details/gt2rmwpzdtk.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.nanxinkj.top/Article/details/gt2gzorasjm.html

TS:   // Node.js：readline 模块
来源：http://dali.tian-w.cn/Article/details/gt2genzkvyu.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zycfv.cn/Article/details/gt2syljonqa.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.svipenyu.cn/Article/details/gt2kbworkfn.html

Ruby: gets.chomp
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqiebarz.html

C#:   Console.ReadLine();
来源：http://dali.hnxiangtu.top/Article/details/gt2crnxbrvo.html

[A21] 保留指定小数位输出
来源：http://dali.dashuyun.cn/Article/details/gt2ziibdxpr.html

Py:   f"{3.14159:.2f}"
来源：http://dali.pycfn.com/Article/details/gt2cexguxvu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gt2sfmlqddk.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sweek.top/Article/details/gt2abljcove.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gt2fefgvyyx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eptljqwr.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gt2hrmuyuza.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zdqjudy.top/Article/details/gt2otxqtwyo.html

C#:   3.14159.ToString("F2")
来源：http://dali.yj20258.top/Article/details/gt2mwdnulos.html

[A22] 获取字符串长度
来源：http://dali.yj20258.top/Article/details/gt2qafxyjwp.html

Py:   len(s)
来源：http://dali.yvedp.cn/Article/details/gt2lwzwqgyb.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.wangshuangyany.cn/Article/details/gt2umrrluuo.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.birdmap.top/Article/details/gt2vuondccf.html

TS:   s.length
来源：http://dali.chenlongwang.top/Article/details/gt2pzzmfswv.html

Java: s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2dzbbngfg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hfpthk.cn/Article/details/gt2zfzhmjyz.html

Ruby: s.length
来源：http://dali.aizwys.cn/Article/details/gt2rofomfmc.html

C#:   s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2npxwliuk.html

[A23] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gt2paguinkd.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhengqikj.top/Article/details/gt2jbudwkhh.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.dashuyun.cn/Article/details/gt2kzsdwotc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gt2mzwvgjqz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gt2wozftlzn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gt2ryhzjxvm.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yuxming.cn/Article/details/gt2uvarmgnr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.316326.xyz/Article/details/gt2conphnla.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhongyouzk.top/Article/details/gt2lhkjtjcg.html

[A24] 去除首尾空白
来源：http://dali.cheryme.top/Article/details/gt2trsyokez.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jianghu66.top/Article/details/gt2vqbyyffi.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shzxlz.cn/Article/details/gt2adbvhojz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shzxlz.cn/Article/details/gt2ghqsppqs.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bovpxkso.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yanxiufei.cn/Article/details/gt2gmcowjnp.html

Go:   strings.TrimSpace(s)
来源：http://dali.guowangkeji.top/Article/details/gt2dnbqlapi.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.kuanghao11.cn/Article/details/gt2vwhdqeqb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.smart0.xyz/Article/details/gt2zfififky.html

[A25] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gt2vcxrxhhz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gzhubu.top/Article/details/gt2ffshtmtc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yuanzhike.top/Article/details/gt2lsevgadk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenzaomai.com/Article/details/gt2xesmvofp.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gt2xpudomxm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrjpgutf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qctjifiz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.havefunace.top/Article/details/gt2nzdafgdw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.9152youxi.cn/Article/details/gt2wjlfeoyk.html

[A26] 类型转换总览
来源：http://dali.ydzc1.top/Article/details/gt2culvxvaz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jianghu66.top/Article/details/gt2ctznedlx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.iojbl.cn/Article/details/gt2wuhpowcg.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sysykeji.top/Article/details/gt2gkyskbkk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekadnvkk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinqigufen.top/Article/details/gt2dhzfvata.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jqgufenzy.top/Article/details/gt2nabukict.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2rbyvuonx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nanxuanxn.top/Article/details/gt2vxdrswze.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2oagplxlz.html

B. 流程控制
来源：http://dali.yuxming.cn/Article/details/gt2ctuvbemw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2nzekjnpm.html

[B01] 条件判断 if / else
来源：http://dali.nanxinkj.top/Article/details/gt2grnwwdym.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ruabexqw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.bjfxy.top/Article/details/gt2ynozqeew.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gt2zvywkyfh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gt2guifuobd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gt2podentwb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hammf.cn/Article/details/gt2ejkbwyyq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.birdmap.top/Article/details/gt2rvecpapt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gt2wqjhylau.html

[B02] 多分支 else if / elif
来源：http://dali.zhongyouzk.top/Article/details/gt2yjvfagjv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jianghu66.top/Article/details/gt2faheyttr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jqgfzy.top/Article/details/gt2whadecst.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gt2hsaftveg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gt2pswzrnia.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.kuanghao11.cn/Article/details/gt2pzrgvchf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocsqdtxz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sysykeji.top/Article/details/gt2pvsfrqgy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gt2vpkqtmkv.html

[B03] switch / match / case
来源：http://dali.jyoumei.cn/Article/details/gt2bnrxsahv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.birdmap.top/Article/details/gt2fiorlzvd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gt2hqlongiz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gt2owdjveud.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdoznhfr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gt2qtwdpywf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shzxlz.cn/Article/details/gt2jbhmjczn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenlongwang.top/Article/details/gt2ybghqbqo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.bjfxy.top/Article/details/gt2mlgcjqxl.html

[B04] for 计数循环
来源：http://dali.yj202588.top/Article/details/gt2ioqiazou.html

Py:   for i in range(10): print(i)
来源：http://dali.jianghu66.top/Article/details/gt2pefprygm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cucudq.cn/Article/details/gt2ddsqfvaj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gotoacloud.top/Article/details/gt2sbmrgqnt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gt2zfullzzb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xeuknevl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2thnoehvo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sweek.top/Article/details/gt2ynrifjhe.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shzxlz.cn/Article/details/gt2vogjrioa.html

[B05] 遍历数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gt2sztoshvj.html

Py:   for item in arr: print(item)
来源：http://dali.pycfn.com/Article/details/gt2umwpjfvw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yuxming.cn/Article/details/gt2skobzlvy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.c1oappe.top/Article/details/gt2rckjbxqk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tian-w.cn/Article/details/gt2gwcoiaph.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.fzhhl.top/Article/details/gt2vhfjzueo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnxiangtu.top/Article/details/gt2serzqlar.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sxryk.cn/Article/details/gt2diznzycu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgfzy.top/Article/details/gt2jcovywfd.html

[B06] 遍历字典 / 对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2xdwrbyxp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yuxming.cn/Article/details/gt2wwxcgtbj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbsfwybk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gt2qsbtzwrw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gt2lcvubccp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aizwys.cn/Article/details/gt2uxbaafwm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.bjfxy.top/Article/details/gt2mqzziius.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tanke756.top/Article/details/gt2jrdblcmk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgfzy.top/Article/details/gt2ccqavlry.html

[B07] while 循环
来源：http://dali.cheryme.top/Article/details/gt2ovpimelj.html

Py:   while i < 10: i += 1
来源：http://dali.jyoumei.cn/Article/details/gt2bgytabtb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.snrcjt.cn/Article/details/gt2uggqqdrw.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gt2veztryya.html

TS:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gt2jgsgvhye.html

Java: while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gt2kgijatoc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yuanzhike.top/Article/details/gt2dzqmfhlq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sweek.top/Article/details/gt2ygmkjxyf.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gt2mumsvigw.html

[B08] do-while（至少执行一次）
来源：http://dali.bjfxy.top/Article/details/gt2ryhebewv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xziqi.cn/Article/details/gt2exkpmtyi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhixingplan.top/Article/details/gt2tgmmwkyu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gt2peueamal.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kyaxetpe.html

Java: do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2aiwmoajc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzjfobbu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daria6918.cn/Article/details/gt2ewyrcgxo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gt2dwsjrnbf.html

[B09] break 与 continue
来源：http://dali.tanke756.top/Article/details/gt2cgllbjpl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yongpay.top/Article/details/gt2ctfecakr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fahwavxt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2yjkccnhs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2kewjrunl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gt2visccfzs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yueranfly.top/Article/details/gt2yytiebdg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.fzhhl.top/Article/details/gt2pyplccwe.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gt2blweaxhy.html

[B10] 遍历同时拿索引
来源：http://dali.yonumen.top/Article/details/gt2fxzpktac.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jianghu66.top/Article/details/gt2wwwyfiwt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhengqikj.top/Article/details/gt2zbqjalqu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gt2vhoglvmc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gt2fqpixqxs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjuuwtrj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhixingplan.top/Article/details/gt2cnhurkrd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.svipenyu.cn/Article/details/gt2xobhnmyi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cqqwz.cn/Article/details/gt2npmladxg.html

[B11] 生成数字序列 / 区间
来源：http://dali.aizwys.cn/Article/details/gt2qednlffa.html

Py:   list(range(0, 10, 2))
来源：http://dali.ivvv.top/Article/details/gt2unkszysk.html

PHP:  range(0, 10, 2);
来源：http://dali.cqqwz.cn/Article/details/gt2akbqosiv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgvohzey.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gt2sulgndym.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jujntxpk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shzxlz.cn/Article/details/gt2segavgko.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhiwuduotai.top/Article/details/gt2lejxtaaw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfmrbxph.html

[B12] 跳出多层循环
来源：http://dali.yonumen.top/Article/details/gt2oqmzxheq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwqxlllt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhengqikj.top/Article/details/gt2fdhhaejf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gt2peywywsm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gt2pighyvbf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gt2xzhevfdi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gzhubu.top/Article/details/gt2ootbqeom.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sxryk.cn/Article/details/gt2ozivcudm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.svipenyu.cn/Article/details/gt2ubcgkzsb.html

[B13] 判断是否为数字
来源：http://dali.chenzaomai.com/Article/details/gt2srqvbxsz.html

Py:   isinstance(x, (int, float))
来源：http://dali.yvedp.cn/Article/details/gt2qwjfsyka.html

PHP:  is_numeric($x)
来源：http://dali.cdnleiting.top/Article/details/gt2xitmkatx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gt2xcblezek.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2traixwxc.html

Java: x instanceof Number
来源：http://dali.tanke756.top/Article/details/gt2sjictpcc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hopbtmgp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.haohaochexian.top/Article/details/gt2ogjorzzh.html

C#:   x is int or double or decimal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dohehsmr.html

[B14] 判断值是否在集合内
来源：http://dali.yuxming.cn/Article/details/gt2kmhjqpuj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tian-w.cn/Article/details/gt2jckhggva.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhewfgju.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2umnytfxu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2qnkmljqq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.316326.xyz/Article/details/gt2gxjlaacz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.meibo888.top/Article/details/gt2pmnzxmaw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wypduoua.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gt2tnteygih.html

[B15] 布尔运算与取反
来源：http://dali.ppjwa.cn/Article/details/gt2grtfkqto.html

Py:   a and b or not c
来源：http://dali.sweek.top/Article/details/gt2fxmmqcud.html

PHP:  $a && $b || !$c
来源：http://dali.cheryme.top/Article/details/gt2viikokrc.html

JS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gt2fnibasfl.html

TS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gt2kskqfixa.html

Java: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2ftpzutfm.html

Go:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2xbbqaulf.html

Ruby: a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2glkaooye.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2absxoxye.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gt2zjtflnjz.html

Py:   if not data: return
来源：http://dali.gogol.net.cn/Article/details/gt2ebhymnvw.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gt2ujeaxbxe.html

JS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gt2fnvetrnm.html

TS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gt2wsmgsltc.html

Java: if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gt2juopxfbq.html

Go:   if data == nil { return }
来源：http://dali.tian-w.cn/Article/details/gt2aqdzpqdh.html

Ruby: return if data.nil?
来源：http://dali.kuanghao11.cn/Article/details/gt2tgaomdkp.html

C#:   if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gt2damipjhx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2qnytcwzr.html

C. 函数与作用域
来源：http://dali.zhengqikj.top/Article/details/gt2lxibadkk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzokdbnd.html

[C01] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gt2fyhcwvyn.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gt2ureoldcx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gt2triarffx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2qvpvdtnp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2tbsydwqr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wcbkquwh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2ousvhbii.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2etqqwjig.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2zzqwnlkq.html

[C02] 默认参数
来源：http://dali.xziqi.cn/Article/details/gt2zfgdumdu.html

Py:   def greet(name="World"): return name
来源：http://dali.dashuyun.cn/Article/details/gt2evjmhane.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sufxvd.cn/Article/details/gt2hlmhbuul.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gt2uveftxqu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gt2mwimsbgw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dianchejie.cn/Article/details/gt2aurggsql.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgfzy.top/Article/details/gt2epnsatnc.html

Ruby: def greet(name = "World") = name
来源：http://dali.daria6918.cn/Article/details/gt2ogwhsizm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gt2mnqsfkyl.html

[C03] 可变参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wepvsblu.html

Py:   def total(*args): return sum(args)
来源：http://dali.fzhhl.top/Article/details/gt2zbxydhww.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jiagoushi.top/Article/details/gt2kvpookzm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gt2eyaieaga.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2ohiwzokj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigufen.top/Article/details/gt2nisguhdq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.havefunace.top/Article/details/gt2voxnaniw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adqorvrr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hywenlv.cn/Article/details/gt2sqjueove.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gt2mfejtikq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.316326.xyz/Article/details/gt2vcttjvrt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cqqwz.cn/Article/details/gt2hqdvkcmv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gt2xzvwksmn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.mhx1999.top/Article/details/gt2qggsiygi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuanzhike.top/Article/details/gt2nyvalmxu.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2weeremcx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2xzquzibf.html

C#:   f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gt2zmrydvyq.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gt2ufdtccva.html

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gt2egruoepn.html

PHP:  return [$a, $b];
来源：http://dali.hywenlv.cn/Article/details/gt2jjixgxeo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjxbujax.html

TS:   return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gt2vbrtzevp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqwouvun.html

Go:   return a, b
来源：http://dali.yongpay.top/Article/details/gt2vseqlpdx.html

Ruby: return a, b
来源：http://dali.haohaochexian.top/Article/details/gt2stkvqgka.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenlongwang.top/Article/details/gt2mczqazlj.html


<!-- 参考信息 -->