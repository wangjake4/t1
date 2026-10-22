代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhengqikj.top/Article/details/gt2ugjolbvl.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhengqikj.top/Article/details/gt2fuauhnqx.html

C#:   $"Hello, {name}!"
来源：http://dali.jlsjyb.cn/Article/details/gt2hhzrwhkt.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shzxlz.cn/Article/details/gt2lnwkswlv.html

Py:   "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gt2zbgqphph.html

PHP:  "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gt2vewcwlcn.html

JS:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gt2reoumwxg.html

TS:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gt2uxbyqswe.html

Java: "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gt2xfrfyzvv.html

Go:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gt2moyijhkt.html

Ruby: "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vngzilum.html

C#:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gt2onehmcgz.html

[A14] 注释写法
来源：http://dali.yonumen.top/Article/details/gt2ecgfyzjd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shzxlz.cn/Article/details/gt2zjhzbcyi.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gt2duyookwq.html

JS:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gt2cdislbfc.html

TS:   // 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gt2vycnkvxv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.smart0.xyz/Article/details/gt2gfhtutrs.html

Go:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gt2oqhivbye.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hfpthk.cn/Article/details/gt2enccogub.html

C#:   // 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gt2jpnrexnm.html

[A15] 空值判断与默认值
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwrmhzzr.html

Py:   value = data or "默认值"
来源：http://dali.gotoacloud.top/Article/details/gt2fhpuoixq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ydzc1.top/Article/details/gt2uegueutl.html

JS:   const value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gt2waprxmwf.html

TS:   const value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gt2clwjhmvb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shuidangran.top/Article/details/gt2zsxcrgfh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tianlin.xyz/Article/details/gt2aqcaoulj.html

Ruby: value = data || "默认值"
来源：http://dali.jiagoushi.top/Article/details/gt2vbzygegk.html

C#:   var value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gt2hrsttzkd.html

[A16] 真假值判断规则
来源：http://dali.yanxiufei.cn/Article/details/gt2ugsgnvec.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.wangshuangyany.cn/Article/details/gt2jtcsamty.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzavmemt.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.9152youxi.cn/Article/details/gt2zwjyaiaj.html

TS:   if (!x) {}
来源：http://dali.cashguo.top/Article/details/gt2oihsvsyh.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhengqikj.top/Article/details/gt2sojmzgzu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.aibaodan.cn/Article/details/gt2untiifvh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.kuanghao11.cn/Article/details/gt2xmvxxdum.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hammf.cn/Article/details/gt2ngcgpybi.html

[A17] 位运算
来源：http://dali.hnqzz.top/Article/details/gt2eqkerolp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gt2oqugefse.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yangfankeji.com/Article/details/gt2krjbgcab.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmfbtqci.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gt2pwxgfzmy.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gt2jbqgnfdy.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gt2hxwggzoj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gt2libalduh.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gt2kdvambdc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shuidangran.top/Article/details/gt2nskzpmnf.html

Py:   ord("A"); chr(65)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjovexic.html

PHP:  ord("A"); chr(65)
来源：http://dali.hfpthk.cn/Article/details/gt2sjyjqvmd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xylfe.cn/Article/details/gt2thtdhcea.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ydzc1.top/Article/details/gt2rhhgrrgs.html

Java: (int) 'A'; (char) 65
来源：http://dali.ivvv.top/Article/details/gt2omanjnik.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.meibo888.top/Article/details/gt2jymkgmyf.html

Ruby: "A".ord; 65.chr
来源：http://dali.hywenlv.cn/Article/details/gt2zqetvhun.html

C#:   (int)'A'; (char)65
来源：http://dali.yuxming.cn/Article/details/gt2alqcicok.html

[A19] 交换两个变量
来源：http://dali.bjfxy.top/Article/details/gt2bdcllutj.html

Py:   a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gt2uicigrdd.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jlsjyb.cn/Article/details/gt2ggsslvlo.html

JS:   [a, b] = [b, a];
来源：http://dali.sufxvd.cn/Article/details/gt2qwyobrar.html

TS:   [a, b] = [b, a];
来源：http://dali.jyoumei.cn/Article/details/gt2ogfiqrdo.html

Java: int t = a; a = b; b = t;
来源：http://dali.fengsongda.top/Article/details/gt2zalqfbjr.html

Go:   a, b = b, a
来源：http://dali.jinqigufen.top/Article/details/gt2ihakuslt.html

Ruby: a, b = b, a
来源：http://dali.ydzc1.top/Article/details/gt2ogtrrnvn.html

C#:   (a, b) = (b, a);
来源：http://dali.tanke756.top/Article/details/gt2bmqxfbks.html

[A20] 读取标准输入
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgoifkwe.html

Py:   name = input("请输入：")
来源：http://dali.hfpthk.cn/Article/details/gt2jjzzlxex.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jianghu66.top/Article/details/gt2hqbpcsex.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmtnspmk.html

TS:   // Node.js：readline 模块
来源：http://dali.yongpay.top/Article/details/gt2cviohatt.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jiagoushi.top/Article/details/gt2xpffxgqm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ehwqpu.com/Article/details/gt2vlbmwjsy.html

Ruby: gets.chomp
来源：http://dali.vqdsnc.cn/Article/details/gt2blfdgaxe.html

C#:   Console.ReadLine();
来源：http://dali.c1oappe.top/Article/details/gt2alxpjyim.html

[A21] 保留指定小数位输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptryoqgu.html

Py:   f"{3.14159:.2f}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzgtojrk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jiagoushi.top/Article/details/gt2bjftyogv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gt2wewmxxkx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gt2uvqvaliw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gt2qgeyogmb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gt2yjraqsln.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jiagoushi.top/Article/details/gt2muynonrr.html

C#:   3.14159.ToString("F2")
来源：http://dali.ehwqpu.com/Article/details/gt2lefpqodd.html

[A22] 获取字符串长度
来源：http://dali.316326.xyz/Article/details/gt2rgrupnbl.html

Py:   len(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2qrenzzse.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbiwssck.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.dashuyun.cn/Article/details/gt2ywuuptmn.html

TS:   s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2unbjjbfd.html

Java: s.length()
来源：http://dali.gotoacloud.top/Article/details/gt2tmtndmxn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2zgvemdzu.html

Ruby: s.length
来源：http://dali.gotoacloud.top/Article/details/gt2wmdaudyq.html

C#:   s.Length
来源：http://dali.yj20258888.top/Article/details/gt2mpglpyre.html

[A23] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gt2sobkdqoi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.redwolf501.top/Article/details/gt2ezbashai.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhixingplan.top/Article/details/gt2smdxjdyj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gt2xfipsqjt.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj202588.top/Article/details/gt2wezkgsfn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jyoumei.cn/Article/details/gt2txjpovgz.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuanzx.com/Article/details/gt2pyqpmajh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gt2iiapljla.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sweek.top/Article/details/gt2nottkihz.html

[A24] 去除首尾空白
来源：http://dali.tian-w.cn/Article/details/gt2akyzjrhf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.chenlongwang.top/Article/details/gt2jtrtgwkh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqvncnab.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shuidangran.top/Article/details/gt2ayzvqynr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigufen.top/Article/details/gt2obrzgbzq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrufaem.html

Go:   strings.TrimSpace(s)
来源：http://dali.haohaochexian.top/Article/details/gt2jyknwwdk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.bjfxy.top/Article/details/gt2ikpexeqx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yuxming.cn/Article/details/gt2dxkxpuca.html

[A25] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgguahub.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugvtoyjo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.9152youxi.cn/Article/details/gt2centjghz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yangfankeji.com/Article/details/gt2pjotszkx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ortgnjhy.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yanxiufei.cn/Article/details/gt2fqmeszma.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hysaishi.cn/Article/details/gt2dzlplytl.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.andypj.xyz/Article/details/gt2ryxelffx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gt2zontwyiy.html

[A26] 类型转换总览
来源：http://dali.zhixingplan.top/Article/details/gt2xgjsadxg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.redwolf501.top/Article/details/gt2ogflsgzp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zdqjudy.top/Article/details/gt2zzmismux.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ydzc1.top/Article/details/gt2mqlvgcdm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sxryk.cn/Article/details/gt2mafjimtl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tianlin.xyz/Article/details/gt2arkauepx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.daxiang520.top/Article/details/gt2jmwsatne.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.316326.xyz/Article/details/gt2xguilixr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.daxiang520.top/Article/details/gt2ybzqccvi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2uhasnpxi.html

B. 流程控制
来源：http://dali.jqgufenzy.top/Article/details/gt2vqzscmpt.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2awgitauk.html

[B01] 条件判断 if / else
来源：http://dali.cheryme.top/Article/details/gt2sofdzkaz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yongpay.top/Article/details/gt2lpiezsdh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cucudq.cn/Article/details/gt2xhrokkpp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gt2ztrrvprd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gt2gcmbymzq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gt2ijixiiok.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruevtgag.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xuanzx.com/Article/details/gt2vyhkvgbe.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gt2awxyvtmk.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigufen.top/Article/details/gt2ghnpnshv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.pycfn.com/Article/details/gt2tgurlqci.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ppjwa.cn/Article/details/gt2mnhdatwf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gt2cuhvameb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gt2ediqjrhe.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcqgjsos.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hammf.cn/Article/details/gt2piwctukj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.pycfn.com/Article/details/gt2ealgoavd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gt2qixbmcib.html

[B03] switch / match / case
来源：http://dali.316326.xyz/Article/details/gt2emtdqvrg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xylfe.cn/Article/details/gt2uasqotnz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gt2mbylgnyh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gt2qugoczey.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gt2wvfmfolp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gt2avtcslro.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jqgfzy.top/Article/details/gt2nkcthlqp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.dianchejie.cn/Article/details/gt2jcwwhbxm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yueranfly.top/Article/details/gt2figrxciv.html

[B04] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gt2jchxviyb.html

Py:   for i in range(10): print(i)
来源：http://dali.yangfankeji.com/Article/details/gt2eomlpdre.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2morakuuf.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gt2osgtgour.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aizwys.cn/Article/details/gt2thjhsaxm.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gaohongyu789.top/Article/details/gt2awuntamc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnxiangtu.top/Article/details/gt2yeyaoczz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gaohongyu789.top/Article/details/gt2dayzpjnt.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yj202588.top/Article/details/gt2naxotusm.html

[B05] 遍历数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gt2yssuwkuw.html

Py:   for item in arr: print(item)
来源：http://dali.xuanzx.com/Article/details/gt2cgmraide.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jyoumei.cn/Article/details/gt2scfdaguv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cashguo.top/Article/details/gt2cuqlvxhn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gt2bpboaykt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqtxcqgd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yueranfly.top/Article/details/gt2uutabkjy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gogol.net.cn/Article/details/gt2zdbjcuoz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cdnleiting.top/Article/details/gt2wavviisj.html

[B06] 遍历字典 / 对象
来源：http://dali.yangfankeji.com/Article/details/gt2lfoemsyq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cdnleiting.top/Article/details/gt2qhvlhtmb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2eplejsnv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ekikyjba.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gt2sramcxem.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhoulong.xyz/Article/details/gt2rbipmbuo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cvxjqnzu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hammf.cn/Article/details/gt2ukmydbov.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gt2xerzvkbi.html

[B07] while 循环
来源：http://dali.hnxiangtu.top/Article/details/gt2nyzvnwwk.html

Py:   while i < 10: i += 1
来源：http://dali.jqgfzy.top/Article/details/gt2rquatfos.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.0kj1m.cn/Article/details/gt2ewpvibrm.html

JS:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gt2rmtdvcgi.html

TS:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gt2cclprcpq.html

Java: while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbcswxnm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tianlin.xyz/Article/details/gt2obyjanjt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gogol.net.cn/Article/details/gt2xxhikqcb.html

C#:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gt2fcwgqpfe.html

[B08] do-while（至少执行一次）
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwlfzatk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuxming.cn/Article/details/gt2xaplypsj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zycfv.cn/Article/details/gt2mhxjlten.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gt2qzojeflw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gt2khwrhgqp.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gt2eijdtknu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenzaomai.com/Article/details/gt2dbbtuxou.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yvedp.cn/Article/details/gt2suyjbymm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2ssehxjwr.html

[B09] break 与 continue
来源：http://dali.cdnleiting.top/Article/details/gt2mdwdxzbt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigfzy.top/Article/details/gt2tlyffdzc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2pmwlizmd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gt2mdxxilkz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gt2cslmpavh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2nyngrvsu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jyoumei.cn/Article/details/gt2swdfjkge.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.daria6918.cn/Article/details/gt2brfgztei.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gt2zfbpluhq.html

[B10] 遍历同时拿索引
来源：http://dali.xylfe.cn/Article/details/gt2ibezabsy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhoulong.xyz/Article/details/gt2ppljolys.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.pycfn.com/Article/details/gt2wmsajcgb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gt2tskunarq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gt2qxkbnlxy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jyoumei.cn/Article/details/gt2admurlba.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pfjvsdbl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nwbrower.top/Article/details/gt2imtjapat.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gt2izpywfcn.html

[B11] 生成数字序列 / 区间
来源：http://dali.hfpthk.cn/Article/details/gt2cctrlgja.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gt2behcudjr.html

PHP:  range(0, 10, 2);
来源：http://dali.jiagoushi.top/Article/details/gt2gyvtthtd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gt2zwajttja.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gt2lwqrsdme.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xinyue.icu/Article/details/gt2gdbbjezb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.9152youxi.cn/Article/details/gt2uzuwbtma.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnqzz.top/Article/details/gt2instxlte.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.meibo888.top/Article/details/gt2thhbkhhv.html

[B12] 跳出多层循环
来源：http://dali.zhixingplan.top/Article/details/gt2jwobxqsd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnqzz.top/Article/details/gt2qdrkommy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aibaodan.cn/Article/details/gt2zcbzdcwh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gt2saqcvkug.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwlgpbdb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pujymghp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cheryme.top/Article/details/gt2yhisunig.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zdqjudy.top/Article/details/gt2ywxtcvwh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj202588.top/Article/details/gt2oybinuup.html

[B13] 判断是否为数字
来源：http://dali.jqgfzy.top/Article/details/gt2gmvtklic.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gt2kuavkkze.html

PHP:  is_numeric($x)
来源：http://dali.fzhhl.top/Article/details/gt2dptuzihx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gt2qbkzbvhp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gt2sluwvcdx.html

Java: x instanceof Number
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxyncgoh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.vqdsnc.cn/Article/details/gt2mytvuwux.html

Ruby: x.is_a?(Numeric)
来源：http://dali.316326.xyz/Article/details/gt2nhbioihf.html

C#:   x is int or double or decimal
来源：http://dali.vqdsnc.cn/Article/details/gt2ccfgrzqa.html

[B14] 判断值是否在集合内
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpdmaaxs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gt2bhzxbxyb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lojxlgek.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2tgsjcjyx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gt2fbginjda.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2vguqxchy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.dianchejie.cn/Article/details/gt2aihevwki.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2uxeykxle.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.birdmap.top/Article/details/gt2lcdkctfy.html

[B15] 布尔运算与取反
来源：http://dali.0kj1m.cn/Article/details/gt2igbshslq.html

Py:   a and b or not c
来源：http://dali.ivvv.top/Article/details/gt2oiwoftge.html

PHP:  $a && $b || !$c
来源：http://dali.redwolf501.top/Article/details/gt2zghmmczn.html

JS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2yprmhkjf.html

TS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2xpdkwxuz.html

Java: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2dgukyevt.html

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2ghiqaoru.html

Ruby: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2loctcmep.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2fpogqzyg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yonumen.top/Article/details/gt2uwmstjce.html

Py:   if not data: return
来源：http://dali.kuanghao11.cn/Article/details/gt2dxehzzrv.html

PHP:  if (!$data) { return; }
来源：http://dali.hfpthk.cn/Article/details/gt2vyxydklg.html

JS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gt2ncsewjzl.html

TS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gt2qrmugdfz.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gt2jvdttrzc.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gt2lzjpxlax.html

Ruby: return if data.nil?
来源：http://dali.hnxiangtu.top/Article/details/gt2weibxkrv.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gt2ddlzhqou.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2docgahsx.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gt2xkfpiwwd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2iiclezxy.html

[C01] 定义函数
来源：http://dali.yongpay.top/Article/details/gt2mspgrsvi.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258888.top/Article/details/gt2oeufvxid.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2yyynemsd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2jzywhimn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2broqfcyg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2xagwqtln.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yangfankeji.com/Article/details/gt2mhdkaldy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvcfnfqj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2btqmwqis.html

[C02] 默认参数
来源：http://dali.9152youxi.cn/Article/details/gt2ylkappqj.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gt2jqblpavs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.316326.xyz/Article/details/gt2fenlvtcn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2bpifvxwe.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2ykgbnweh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.0kj1m.cn/Article/details/gt2gvnhizcc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.redwolf501.top/Article/details/gt2qhsjpwpo.html

Ruby: def greet(name = "World") = name
来源：http://dali.shuidangran.top/Article/details/gt2crizdjpc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jiagoushi.top/Article/details/gt2wmhvvktf.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjihhil.html

Py:   def total(*args): return sum(args)
来源：http://dali.guannengcc.top/Article/details/gt2vmdncqst.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gt2gmieldwy.html


<!-- 参考信息 -->