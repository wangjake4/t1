代发 wailian999

Ruby: arr.tally
来源：http://dali.cashguo.top/Article/details/gtksnacwiu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuanzhike.top/Article/details/gtedxdragx.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gtcmqrgvmj.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gtmhcvwvly.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gtpyunpcoi.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtfvaqywjh.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtbkibxsno.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gthvgwhbwy.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gteubqozwv.html

Ruby: arr.include?(x)
来源：http://dali.aibaodan.cn/Article/details/gthpjrgrkb.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtoknelouo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenjidiqi.icu/Article/details/gtvgkeziwj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.snrcjt.cn/Article/details/gtzuvbrzor.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhengqikj.top/Article/details/gtodnqfakt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuxming.cn/Article/details/gtvulvhyty.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gtgdmvvfob.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gtyowkklfy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shzxlz.cn/Article/details/gtqloxrmry.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gtndnlqzpt.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gtiozcjgof.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gtprdczlnh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pycfn.com/Article/details/gtwyoqwmeu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fzhhl.top/Article/details/gtihkzodeo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtbmhyrnxa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtzwxkmujc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtujmzpiuy.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtonmxkkrl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtjvagxxnc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtxnynaggc.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gtuyqxbcod.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shuidangran.top/Article/details/gtbvktbhmv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtsgacrwex.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtmpjaowuw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhivoljl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gtbuyjyqbd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gtvnxruiun.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtqqctlaqr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtwlidvnji.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gtuggqlnez.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gtfwpwykok.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gtuvfhufbz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zycfv.cn/Article/details/gtxzbetqhk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shzxlz.cn/Article/details/gtajzrsfhr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fzhhl.top/Article/details/gtnramcaap.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gtkvuzxzvm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dianchejie.cn/Article/details/gthhiletrv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gzhubu.top/Article/details/gtlarxlxgg.html

[D26] 数组转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtktkfakdd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gtmlkyyuer.html

PHP:  implode(", ", $arr);
来源：http://dali.0kj1m.cn/Article/details/gtbmpqyocu.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtdlrzoreq.html

TS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtivqxmpwg.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gttqzvsxry.html

Go:   strings.Join(strs, ", ")
来源：http://dali.0kj1m.cn/Article/details/gtagdgpjcw.html

Ruby: arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gthjnamvyu.html

C#:   string.Join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gthwawlnws.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfdflobvj.html

E. 字符串处理
来源：http://dali.c1oappe.top/Article/details/gtmpduotoh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtkecmipay.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtyxlubssw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.bjfxy.top/Article/details/gtgjskdgow.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtjzzieyte.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtelcwkbwk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtkjpikfir.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuetiantiany.cn/Article/details/gtktgmbuhd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.316326.xyz/Article/details/gtjwgqzewj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gtxauffuyx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cashguo.top/Article/details/gtbsvmtouo.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gtbhaxwulw.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtqrvygbya.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aizwys.cn/Article/details/gtbezvjnpu.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtoctinxij.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtjiuaqgvq.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtwknmnasp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ivvv.top/Article/details/gtidfwipnr.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtncacnlia.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gtcilbxjcc.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtfuhfsukm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gtmntkaful.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtvrrzvxij.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtgwmkgujf.html

TS:   s.slice(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtdhtulood.html

Java: s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gthbszdtnl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gtodcjxoxe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gttutpvkit.html

C#:   s.Substring(1, 3)
来源：http://dali.cucudq.cn/Article/details/gtovjjhapx.html

[E04] 查找子串位置
来源：http://dali.xylfe.cn/Article/details/gthxmlacio.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gtkvdtnjmz.html

PHP:  strpos($s, "x");
来源：http://dali.zycfv.cn/Article/details/gtsaackoqo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj202588.top/Article/details/gtituheydb.html

TS:   s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gtmjhhhfbe.html

Java: s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtkccioets.html

Go:   strings.Index(s, "x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdsolyae.html

Ruby: s.index("x")
来源：http://dali.tian-w.cn/Article/details/gtqzgxscwq.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gthevfcxxo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hammf.cn/Article/details/gtdsnvfmgb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gotoacloud.top/Article/details/gtrcsdaacu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.feifeiyinyue.top/Article/details/gtguuzzvzc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtypqgyhfu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuxming.cn/Article/details/gtjencirxu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtdbnrevdw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shangyingyoupin.top/Article/details/gthkbxsgqh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtrwiaylnd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtmylocbvj.html

[E06] 替换子串
来源：http://dali.gotoacloud.top/Article/details/gtcphuebcy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtipyigduj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhongyouzk.top/Article/details/gtiqqkmxyd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmnineth.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gthqbruawa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtyhbapyil.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtqvsjbneu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtlixlnsxt.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtljjmnbbv.html

[E07] 按分隔符拆分
来源：http://dali.vqdsnc.cn/Article/details/gtrxwawyrx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gtzzqkbfkc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ydzc1.top/Article/details/gttgyiyhrj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuanzhike.top/Article/details/gtcndledde.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gtswgkdgky.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gtjamjbajg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.bjfxy.top/Article/details/gtdthzpcax.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzbxyhva.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhoulong.xyz/Article/details/gtwssmalac.html

[E08] 数组按分隔符合并
来源：http://dali.pycfn.com/Article/details/gtbnhhbqsz.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gtgbzedhlp.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gtqaqhlsth.html

JS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtptuopcap.html

TS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtrjbobnfa.html

Java: String.join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywykdmfy.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gtvuenotct.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtiicfvhsk.html

C#:   string.Join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtlkszfwvq.html

[E09] 去除所有空白字符
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzpjafjn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gtisouaiso.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtomneflml.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtcqvafbxg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtljzqnpkd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtmosnvjvr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnqzz.top/Article/details/gtnipymndp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gthnmpcfkl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtvepmiijo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.c1oappe.top/Article/details/gtsfimubhj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtefrkymyv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gtamayviwa.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtvctnrnzp.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtltdflchb.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtjnbyehpl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtowmoldma.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtrmizhbyi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gtxfsqxwop.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gtyuxuczwv.html

Py:   s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtqowntbas.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtnaqsvuda.html

JS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtloepujxl.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gthjuffndg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gttbeunlfl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtcslsuofw.html

Ruby: s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtospvzvtw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtygjxtxsg.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtdxndbcef.html

Py:   s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtegtxgfjv.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gtwzzvxjjh.html

JS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtmqchncci.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtjdnnqxit.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gthxrkibto.html

Go:   strings.Count(s, "a")
来源：http://dali.hywenlv.cn/Article/details/gtinbuvmzw.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtcnlwrjzb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gtrnisqvlo.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtbyrfvqej.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gtzeiuoxwz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tianlin.xyz/Article/details/gtpgteibiv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtvuuftwqd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtwxcnremw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fengsongda.top/Article/details/gthfzmckpp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtucqubfqa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yueranfly.top/Article/details/gtfsfezycu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtlhwpkaxt.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gtkzxvhbrt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gttwmpcbcc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gtbeaqeyng.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikierdck.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggowavqs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gthwzrupql.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gtmtrtelxx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ydzc1.top/Article/details/gtovwrqxbr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nwbrower.top/Article/details/gtutccyqyt.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gttfnaovay.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hysaishi.cn/Article/details/gtuolctmya.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnkbukuj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxuanxn.top/Article/details/gteublbvmg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cqqwz.cn/Article/details/gtrybmeydj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gtxuymyfyu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gtozmsthbx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtblykflpa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtwbijmc.html

[E16] 数字千分位
来源：http://dali.gzhubu.top/Article/details/gtgkzihbzl.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gtecijiigu.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gtvkqawxux.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtlnuirwkv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtottyrqjd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtsphxmryy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.0kj1m.cn/Article/details/gtpqyoukze.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gtqdmpzubp.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gthasgcolw.html

[E17] 首字母大写
来源：http://dali.yangfankeji.com/Article/details/gtxzeznois.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daxiang520.top/Article/details/gtkqzrwwxu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtkzubccxz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtwslnrdae.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtspdnwyts.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwfvdbxp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gtnrcucycn.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gtbabthtnf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.smart0.xyz/Article/details/gthjeqdqmu.html

[E18] 模板占位符替换
来源：http://dali.nanxinkj.top/Article/details/gtqmjioynk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gtixlldjmu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gtovktpzzv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtxndasugy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtjbrhrysn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtjlfdeszf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtmaijflml.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.havefunace.top/Article/details/gtbtgnzevp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gtqxxldndq.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gtqpzgcxzb.html

Py:   s.splitlines()
来源：http://dali.tianlin.xyz/Article/details/gtsvvvcmsa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtcbugmrhf.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtnyfsnfwa.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtqzknowrn.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gtqtfqawml.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtghhznlcs.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtiscprrpf.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gteezijohp.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycpaidmg.html

Py:   if not s:
来源：http://dali.zhoulong.xyz/Article/details/gtbfjwalnx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gtlnqzejaa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbkzmdih.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwerfcvpn.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtxgexlsfx.html

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gtnorexsnz.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gtcmhigdjl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gtgtsnnluo.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gtkjaqofzp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gtfctsdkgl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtzerqudfq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtonufmmur.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtjfrtlacs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtqukhsvqp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gtgorydqfq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtnrvvoxbr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtystrrxqz.html

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gteebqlohr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtkevxbqvx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtpvchsvfs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtmrhxebpu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtrrkslvnz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtlutdxenf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtdtesicym.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtyjjnrkqn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gtizuikkdi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtptuqpqpm.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gtwmrgwqti.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvtpvhiho.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gtbqudsjpo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkidjavbq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtvkjpwovw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gttkqtpwll.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtsmapkvef.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtnvedtdrk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gthslxrspb.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gtkzgfvqvu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtufhrdlsf.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtcsfiaxrp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gtrqgjgmrp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gtcdijwcam.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthoziplgu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gtyuflcyxv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtggcbzjko.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fzhhl.top/Article/details/gtwhgsqnnn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gtnaesnibs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gtnjoxdkrl.html

[F03] 写入文件（覆盖）
来源：http://dali.hnqzz.top/Article/details/gttiukqnoz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gtzncvygpp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupnvwfsw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtxoerhoow.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gtnzigjjpe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gtcbtiryqw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gtvtgpsict.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gtvzhcohnc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtasrwpzxs.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtdepxrwxs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gtdhwidpiq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzhyhcdk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtjnhdzxcf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtzzkaakvy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuanzx.com/Article/details/gtsirdxxnj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtwdkuxhxr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gtnzzduyuo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gaohongyu789.top/Article/details/gtryfxafxi.html

[F05] 判断文件或目录是否存在
来源：http://dali.aizwys.cn/Article/details/gttrvkrmjy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenjidiqi.icu/Article/details/gtcrbybsvo.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtzklefsnn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtlwfoyjni.html


<!-- 参考信息 -->