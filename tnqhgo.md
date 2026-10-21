代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.fengsongda.top/Article/details/gtxgdohbfg.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtkvviyyxa.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtctxrzhjn.html

Java: list.contains(x)
来源：http://dali.sweek.top/Article/details/gtrulsmzgb.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcilqrjew.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gtpzztgttf.html

C#:   list.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtuaagxiub.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sxryk.cn/Article/details/gtbxqpdefv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ehwqpu.com/Article/details/gtczmgjpov.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gtjzzsbesw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gtywavxnlc.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxeexxexw.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtihwxtkwg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gtqnollqjc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gtxvpiqydr.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcvysrnl.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gtkdcuuyfh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gttznjtdyi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ydzc1.top/Article/details/gtgekxngnr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtrkxdtadu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmbtjkqo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aibaodan.cn/Article/details/gtbykzcbyo.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtsiafvbey.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hammf.cn/Article/details/gtslypmbpd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jiagoushi.top/Article/details/gtwmhlvibh.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gtyjhewghu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gtoofzzcjp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gtmgekbqgx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbrftrxi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtnpvhkaxq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gttsjrihxk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ivvv.top/Article/details/gtdrphaqjx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gtadzcvleo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shuidangran.top/Article/details/gtlhrxfosy.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gtmuuijrtv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hywenlv.cn/Article/details/gtnatrwdow.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtgzehrfah.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dianchejie.cn/Article/details/gtjzbtylbm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gtpyfgyuag.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gtoptxjlfb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhixingplan.top/Article/details/gtituojitb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.smart0.xyz/Article/details/gtjemchfmd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.andypj.xyz/Article/details/gtkkhhytqg.html

[D26] 数组转字符串
来源：http://dali.c1oappe.top/Article/details/gtqvfqbiwy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fengsongda.top/Article/details/gtavqrvtpc.html

PHP:  implode(", ", $arr);
来源：http://dali.gogol.net.cn/Article/details/gtzngqjygl.html

JS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtsjlcsddp.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtqxqessvd.html

Java: String.join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtnpjmrwat.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhoulong.xyz/Article/details/gthgumyome.html

Ruby: arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtsticnvas.html

C#:   string.Join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gtspqhncoy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtykkfhpbu.html

E. 字符串处理
来源：http://dali.aizwys.cn/Article/details/gtiutowvus.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtpteedpen.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gtqmdhvljf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fengsongda.top/Article/details/gtvdyvthrt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuanzhike.top/Article/details/gttkaxsviy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtzeivzsrv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtxfaiwsan.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gtmtrklgdl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tian-w.cn/Article/details/gtrqqehped.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.quarkkingdee.top/Article/details/gtyctjibay.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtucufnvzt.html

[E02] 重复字符串
来源：http://dali.yangfankeji.com/Article/details/gtrshxoqic.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtemusqbjl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj202588.top/Article/details/gtbwmdejku.html

JS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtfqcncaef.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtxtcimexc.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtepnulfkk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gtbmtwrbru.html

Ruby: "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtztjelbyo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gtwdwtumku.html

[E03] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtedpirwje.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gtwcbbwaaw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtxyqhqddg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtwxdeznwc.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtpgrwnjdl.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtennaopix.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtertbizgv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gtfdguaehp.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gtizpvzzzr.html

[E04] 查找子串位置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtmtrklx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlnuhlvf.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigufen.top/Article/details/gtifqnmcwv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhengqikj.top/Article/details/gtiqwkaomi.html

TS:   s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtmacbifqo.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtbmxitmxl.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgfzy.top/Article/details/gtarkgtfol.html

Ruby: s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtckvyakpw.html

C#:   s.IndexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtlrgisfar.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuetiantiany.cn/Article/details/gtueuevuzv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtofysrrha.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aizwys.cn/Article/details/gtrhwywdjb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtcepescxf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtimixkcax.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtnywogsej.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangshuangyany.cn/Article/details/gtaewfbnoy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtexkhegho.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtlqrmeswb.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gtoulpkteb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtqkrisefx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxueovfwa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtmfcaagzn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtewjmlmnk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylmwnhtv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtipfvdblj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgnfzbvc.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtbbxkqofv.html

[E07] 按分隔符拆分
来源：http://dali.guannengcc.top/Article/details/gtvkmpmajs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gtopuvpfmp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtutvphjzz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgfzy.top/Article/details/gtwphfaqak.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gtnowomcaf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gtjwhdhotx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtxkaxgasy.html

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gtkrsmavzy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gtkhbsowla.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gttleuvnwc.html

Py:   ",".join(items)
来源：http://dali.svipenyu.cn/Article/details/gtqmsohwsb.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpohrztbz.html

JS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtgkeneggb.html

TS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtroglmzua.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gthjxkmalc.html

Go:   strings.Join(items, ",")
来源：http://dali.zycfv.cn/Article/details/gtqszrfduf.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtmizktfdp.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gttepizfyx.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrlnllaf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cqqwz.cn/Article/details/gtumaualnh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sysykeji.top/Article/details/gtfykkpeje.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtnixbrkov.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtjhdfwwnl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtvwtjmwkn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gttyhmfoua.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtltfrbqrk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtiswmaqhq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtfoilrpak.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtzwjtsbyu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtivdtsqgw.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtexzmyhtd.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtnnnsmtpv.html

Java: String.format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtlmqpjlze.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtazshhrqz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtrwjdygyd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gtnqvastek.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gtzzzophch.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gthkbmebqp.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gttwslmonm.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtpbbnvfzk.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtysjxqbjz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.haohaochexian.top/Article/details/gtpcytlcot.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dashuyun.cn/Article/details/gtkrkwlxtc.html

Ruby: s.reverse
来源：http://dali.shuidangran.top/Article/details/gtzsycrgbg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtwypguokv.html

[E12] 统计某字符出现次数
来源：http://dali.dashuyun.cn/Article/details/gtigrexpmv.html

Py:   s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtmzqmoxly.html

PHP:  substr_count($s, "a");
来源：http://dali.haohaochexian.top/Article/details/gtqpydfgae.html

JS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtokwmjeww.html

TS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtnvwvdpxi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aizwys.cn/Article/details/gtwlrzcjwk.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gtaqpixfxd.html

Ruby: s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtthkmiouk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cashguo.top/Article/details/gtpsjrewgw.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrpogogt.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsungein.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gtnvbknflf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtoljoeidx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtnuzvsawi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtnvmdhqoq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.iojbl.cn/Article/details/gtjmjgonde.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aibaodan.cn/Article/details/gthrrmwyjc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpesjyenz.html

[E14] URL 编码与 Base64
来源：http://dali.vqdsnc.cn/Article/details/gtwowqeopm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gtdwigyfhq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtmhzqdjer.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gthwvgnmsr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gtjorpquvd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtcfngqezr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gterybpxfz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ppjwa.cn/Article/details/gtxbkzijav.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cucudq.cn/Article/details/gtnntjvqds.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gtitmycxhs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tian-w.cn/Article/details/gtlnuojlst.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupsttltt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuxming.cn/Article/details/gtilssbdmq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fengsongda.top/Article/details/gtddkphylp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gtuneprwsa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ehwqpu.com/Article/details/gtgvxfsqrl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gtqxoewdil.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.0kj1m.cn/Article/details/gtjsrwajaa.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtbcpoaxsj.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gtxmwlmlji.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gttilsrrky.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtkfahphjb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtuskvykcy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gtsnatadgj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gtgbdyagie.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtvawfgkhc.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gtpzxtqweg.html

[E17] 首字母大写
来源：http://dali.yangfankeji.com/Article/details/gtxqylsikv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aibaodan.cn/Article/details/gtysctotau.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gtmyeatiqj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gtwcdkyydt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjjiuhms.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gtjkplghdo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gtwaezepwm.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gtlafiwqkg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gtcldwbfqw.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gtcmskqvfe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gthkzqpzdt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gtyoiovmru.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtmwzabvxi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtmjhzrsup.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcztxbjmh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtrqnqjbcj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gtpxzhjwki.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhengqikj.top/Article/details/gtmjatovdf.html

[E19] 多行文本按行拆分
来源：http://dali.nwbrower.top/Article/details/gtdfvoruax.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gtegitlkxh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gtfhlarsxe.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gtpytwhhbx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtkrebctre.html

Java: s.lines().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtstkmrlpn.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gtzzdegoaj.html

Ruby: s.lines
来源：http://dali.dashuyun.cn/Article/details/gtqcibiyqd.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gtadcpmcxq.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gtwrthxafo.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gttaxtyhrq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gtayygboys.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtvjcwsxnf.html

TS:   if (s === "") {}
来源：http://dali.ybcxt.top/Article/details/gttcqewqfy.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtlukitkxl.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbmywhatb.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gtapgkwltw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gtipeugtgq.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gtukwpvvmb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gtqdiutwxq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gthflpbybl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtomwqhpas.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtvvbtejgq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtztxcnsth.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gtsgxelxvf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtvzuxnrtl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfyhamci.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gtyvtfbyhw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gtypxdpdag.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtpydhckuw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtsjjghjua.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtjkyzybft.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gtieoaagfp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gticzkdcsj.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gtvxuqrlxt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtvjfmruqq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqiylowym.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gtgemgukqb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzqsotkwi.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gtewbdyhlg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gtwpkfsuym.html

PHP:  file_get_contents("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtevxcyugf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gtdexfwaeh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gtsihiiruf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyczhejrc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cheryme.top/Article/details/gtulmvgugz.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvvzgmxa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gtuhftdojk.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gtkjwxcpsf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gtvliwvdih.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnxiangtu.top/Article/details/gtfxllhbmf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtxjumcqwv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtznovocvz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtxcmuddlc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gtuntthohe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gtehqypxrn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangdashe.top/Article/details/gtlqdcokvs.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwustpcu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gtxhwteifu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtfrjilbbo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtvfcshkhj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtjfsimpxx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtdxdmxego.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gtqagbomxh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtuzkbelna.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtxmdtgcyc.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gtviottyzn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtkuquqxyv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcsaqzvy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gthsseiopz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtljyyeqxh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gtmxrjatio.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gttgfkgvpf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gtvfjrdudv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gtyylasyiu.html

[F05] 判断文件或目录是否存在
来源：http://dali.mhx1999.top/Article/details/gtxnrxljph.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtnkxshgwf.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtsbqoplej.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtesiykyyo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmklvocrj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtehybdipu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gtiriimhlf.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gthvplpiea.html


<!-- 参考信息 -->