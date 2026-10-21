代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cashguo.top/Article/details/gtfsggfpop.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gtlzhcefwk.html

C#:   list.Max();  list.Min()
来源：http://dali.aizwys.cn/Article/details/gtwfuqhmmp.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gtxytmysbx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnqzz.top/Article/details/gtkardnykd.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gtsrbjfjbb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gtsbtawgcz.html

TS:   nested.flat();
来源：http://dali.daxiang520.top/Article/details/gthalaqmuo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yongpay.top/Article/details/gtbhvysidc.html

Go:   // 手写双层循环
来源：http://dali.yj202588.top/Article/details/gtklfeekfq.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gtvyngkvna.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkactzif.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gtfwnzkmwo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ybcxt.top/Article/details/gtflnswubq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cucudq.cn/Article/details/gtqqjnzqlt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shzxlz.cn/Article/details/gtjxrnbqzl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gtnqlfqhbl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tian-w.cn/Article/details/gtjxresuwk.html

Go:   // 手写 map[string][]T
来源：http://dali.andypj.xyz/Article/details/gtqksunxmy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gtjhewezmm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gtnyvrnzvh.html

[D20] 统计每个元素出现次数
来源：http://dali.jianghu66.top/Article/details/gtjzkiviqb.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gtyhydfrzg.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gtylrabwur.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnrlpfpj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gtqvpbmfis.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guannengcc.top/Article/details/gtdbqntxxg.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gtqwjwftym.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyizagtb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gtaafqwpew.html

[D21] 判断是否包含某元素
来源：http://dali.cashguo.top/Article/details/gtvabejwzz.html

Py:   x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtgsdlxmqw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gtsuldamdx.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtzulhcqok.html

TS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gthfsvbpru.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpgasdau.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtnmyqjulb.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gtovlvbqwo.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gthkgnfjpo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gtwbcaxloh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtvbrggsrr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gtgtzaaijj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shzxlz.cn/Article/details/gthrcbcghf.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gtnsjadush.html

Java: new ArrayList<>(list);
来源：http://dali.guowangkeji.top/Article/details/gtbltombxh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yvedp.cn/Article/details/gtuuxzuaop.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xinyue.icu/Article/details/gtasjevwmk.html

C#:   new List<int>(list);
来源：http://dali.jqgfzy.top/Article/details/gtlbijnkmx.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gtszcknpfs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cucudq.cn/Article/details/gtohailylv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gtbghexovs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtkfkxrmgr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gttiibzygb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.redwolf501.top/Article/details/gttnvsyhfv.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtguysnjpy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkkmjukx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sweek.top/Article/details/gtqynblhco.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gtoafzhqaf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtzokrjxfx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtwucmrevn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gtichoogoo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtcbfatint.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gtwtrxtzwn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gtuewlmnwf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.0kj1m.cn/Article/details/gtdbhpiagg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlezfjvsa.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtncjgsjcj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtowjvndno.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gtpzevuvnd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gtnsmnowog.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gtxmsqwgry.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtjwnbykuj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gtzpswlcra.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hywenlv.cn/Article/details/gtdogdsiqk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gtisigqccb.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gtdfgrwhgb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hywenlv.cn/Article/details/gtwguuwsft.html

PHP:  implode(", ", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtlkwxthvk.html

JS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtumfxvqme.html

TS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtnnbxcosw.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtqmiekyfq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tianlin.xyz/Article/details/gtjlmbcajd.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gthofkoudj.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtupybbmcv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkmgbnqyf.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gtttqcsrxt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtobodvblf.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtnvjjntyj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgfzy.top/Article/details/gtmwuvpwhk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gtzjxvltyk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtejrwztst.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtfutxxydm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shuidangran.top/Article/details/gtkrxucleh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yongpay.top/Article/details/gtqzydynlt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gtoqqsbcsc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvsqdfnw.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gtluzerqnw.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtibkrznyw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pengpengdd.cyou/Article/details/gteqguayfx.html

JS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtruntbtpd.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtjvdqtqrf.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtnheviwkx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yangfankeji.com/Article/details/gtinruwolq.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gthkiajnmf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmghnknzi.html

[E03] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtjatfmdbi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sxryk.cn/Article/details/gtevomionq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtuftpvjft.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtuvlbowwt.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtvcaftyre.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfittfjje.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gtgofftrxd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tian-w.cn/Article/details/gtabqojzgp.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258.top/Article/details/gtsazhzpnx.html

[E04] 查找子串位置
来源：http://dali.0kj1m.cn/Article/details/gtuygqdajy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtvyyiszww.html

PHP:  strpos($s, "x");
来源：http://dali.fengsongda.top/Article/details/gtoppoyjpw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgufenzy.top/Article/details/gtjsucxjvs.html

TS:   s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtqenuevjr.html

Java: s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtpqaqsows.html

Go:   strings.Index(s, "x")
来源：http://dali.yuxming.cn/Article/details/gtapvtlrdm.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtswsxinnb.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtjvabbvja.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gttvzsjdvm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtaibmslsn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuanzhike.top/Article/details/gtztxuxzqp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtvkigquhu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gtdqpmlpsy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtbytpxlam.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigfzy.top/Article/details/gtnfkithqf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nwbrower.top/Article/details/gtuwcakpsc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtbsixqgdz.html

[E06] 替换子串
来源：http://dali.meibo888.top/Article/details/gtimcgfcow.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtummurxkv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gtmopftdvc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtiptxvnzr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtezgoqygb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtqzorypci.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtsrgscydx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtvojyulsq.html

C#:   s.Replace("a", "b")
来源：http://dali.yonumen.top/Article/details/gtfvzdcxer.html

[E07] 按分隔符拆分
来源：http://dali.vqdsnc.cn/Article/details/gtpnyhtpcq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ppjwa.cn/Article/details/gtasjrsjpv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtkstowrbt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gtrxveckqu.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gtowiselgu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aizwys.cn/Article/details/gtvlhsvday.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gtomwhztqs.html

Ruby: s.split(",");  s.split
来源：http://dali.zhixingplan.top/Article/details/gtxrkthixr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gtzzmxlqth.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gtydgnpuiv.html

Py:   ",".join(items)
来源：http://dali.shuidangran.top/Article/details/gtnkzpqitq.html

PHP:  implode(",", $items);
来源：http://dali.nanxinkj.top/Article/details/gtbvpyspot.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtkoonyxlo.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtybnrmsit.html

Java: String.join(",", items)
来源：http://dali.yj202588.top/Article/details/gtjczzhvxj.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtdrgcfkaq.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gttgawlwth.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gtacpavzhr.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gtqladiawo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gtrapdhvwm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzehtnevt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gticwbkzwy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtfhapycrx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtetpexnof.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.mhx1999.top/Article/details/gtoyyyeesm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zycfv.cn/Article/details/gthjbslaav.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tian-w.cn/Article/details/gtzppazyaj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gtfiikjulr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtizjphjov.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yonumen.top/Article/details/gtnisicqfm.html

JS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtbqebrnvt.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtdssdsnkr.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtogpvlpmk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gthjdnxjaz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtnmknftvn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtylsupjkj.html

[E11] 反转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtzucfcyxw.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtslazmhbg.html

PHP:  strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gtucabspkq.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtccrtmldc.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtrjhyazed.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gtvexvpcco.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtyiqagheg.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtdhjexadx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtbimgvkza.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gtfdyyoype.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gthpkoubrt.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gtqmjehied.html

JS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtwlsamjgl.html

TS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtxazclqdo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinjpsjxx.html

Go:   strings.Count(s, "a")
来源：http://dali.yueranfly.top/Article/details/gtpomueoxh.html

Ruby: s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtamiqvxzu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gtyjmidkdh.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gtycttvzxr.html

Py:   for ch in s: print(ch)
来源：http://dali.zhoulong.xyz/Article/details/gtoqlqabzp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gterjphbgy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtgcywstnr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtowrbaftn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gtphcgmcfm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewrqiknp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.c1oappe.top/Article/details/gtksiaephu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sysykeji.top/Article/details/gtlojsheri.html

[E14] URL 编码与 Base64
来源：http://dali.sxryk.cn/Article/details/gtcaftgjtf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.redwolf501.top/Article/details/gtvcuknbta.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gticxoqqeh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dashuyun.cn/Article/details/gtmbsdpabu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gtrnwjxutb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtieiicpik.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbogzpef.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gtpcjaskhg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xinyue.icu/Article/details/gtgqpgxeux.html

[E15] HTML 转义 / 反转义
来源：http://dali.guowangkeji.top/Article/details/gtfdptcuya.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gtwppqgkec.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gttvwjvszn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cashguo.top/Article/details/gttfmmptwk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhixingplan.top/Article/details/gtnzozbvsf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuetiantiany.cn/Article/details/gtijpmclvl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sysykeji.top/Article/details/gtabcrlmog.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangdashe.top/Article/details/gtwfssooml.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gtrmqgaxct.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtfddwgusu.html

Py:   f"{1234567:,}"
来源：http://dali.snrcjt.cn/Article/details/gtnwcxeudy.html

PHP:  number_format(1234567);
来源：http://dali.yonumen.top/Article/details/gtpifdyxjn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtrodovlvz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gthzzjgvkz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtluefmmqn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuanzhike.top/Article/details/gtpmupzecj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gtkkgjzyfy.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gtnahyexpa.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gtdnrzwcbr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sxryk.cn/Article/details/gttzgmlqqa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gtxkyrepsr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtnzrfhcew.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtcfbqinnz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gtmgrehvrv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtyihbaruu.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gtmijwglsa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gtlvlyppxa.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gtnsvttods.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gtimscllnz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gtwoksbmfs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtjldoglok.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtgyghpobk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtemxvcrme.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtjtwmuvit.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvndfjbij.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gtofmteuta.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtvzkgavfe.html

Py:   s.splitlines()
来源：http://dali.tanke756.top/Article/details/gtpeoyifau.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtgdvvavcb.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtsknacvsl.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gttgpijple.html

Java: s.lines().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtffmxhrzv.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtcytxdtld.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gtgnuezrdv.html

C#:   s.Split('\n')
来源：http://dali.zhiwuduotai.top/Article/details/gtyjvtflum.html

[E20] 判断字符串是否为空
来源：http://dali.daxiang520.top/Article/details/gtnapcfumz.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gtwwzptbhq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gtccwxrddl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gtavcdfysh.html

TS:   if (s === "") {}
来源：http://dali.xylfe.cn/Article/details/gtpmegnglq.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gteqrgesky.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gtfzguicbi.html

Ruby: if s.empty?
来源：http://dali.sxryk.cn/Article/details/gtxlvpkxuh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gtgbrrbtgg.html

[E21] 超长截断加省略号
来源：http://dali.yvedp.cn/Article/details/gtlijpuxnf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.birdmap.top/Article/details/gtcflfcwvp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtousayurx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gthcenowrf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtsfeoscol.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gturlzwjgs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gtwpfounvn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtmlwzutro.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gthmyslzjp.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gtnvgfxvxn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ivvv.top/Article/details/gtbcjhclgk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtjdisimtv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtbijtcspn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gthhutugko.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gtdjpnksyg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gtgsofjieb.html

Ruby: s.bytesize;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtveybqsgk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gtdbffptba.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtwqhxxbto.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gtgddnxzuh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtcejsqvao.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaftyqolp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dianchejie.cn/Article/details/gtduhxgrgx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtahzfnjbp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gtpnjqhceh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtnkhgbfjf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtjdhybcqy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinghuilouyu.cn/Article/details/gtptnverdf.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtjabdzvhg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gttbjaciwq.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gtfngnzeus.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hywenlv.cn/Article/details/gtdlwijqtg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtgonhtoxz.html


<!-- 参考信息 -->