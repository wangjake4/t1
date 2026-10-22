代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gthoyslrbk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.vqdsnc.cn/Article/details/gtxbriprnx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gtpkgpwmqc.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gtvxvoldhf.html

C#:   list.Distinct().ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnlkgobh.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gtcqitinfb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gttynntgru.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtcqagrhur.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtptkrauph.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtupybjeyg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gttoazwnja.html

Go:   // 手写循环累加
来源：http://dali.feifeiyinyue.top/Article/details/gtzagczfqw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yvedp.cn/Article/details/gtrtpdhfjh.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gtcffyhdrj.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gtbcxfhbdy.html

Py:   max(arr);  min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtgyrkuduv.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gtbevjsprh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtxrjajqea.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gtgmmdllws.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ivvv.top/Article/details/gtdihvjdhn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtqslalloe.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gtjrfhewtl.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtjvvuvkbs.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gtsfvadlkx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuxming.cn/Article/details/gtisdhqmje.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gthjxfnged.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gthefblond.html

TS:   nested.flat();
来源：http://dali.tian-w.cn/Article/details/gtszhkngbx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gtyuwcufcs.html

Go:   // 手写双层循环
来源：http://dali.zhoulong.xyz/Article/details/gtdzjxzbbo.html

Ruby: nested.flatten
来源：http://dali.hysaishi.cn/Article/details/gtvzdaiabx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aizwys.cn/Article/details/gtequuricj.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzugwzsi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cashguo.top/Article/details/gtdawgxphr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gtptnqqmtj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gtzmjemikd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtunojyuij.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gtkrcvespr.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gtaftrrurn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gtvrhncpmm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gtcoucunqo.html

[D20] 统计每个元素出现次数
来源：http://dali.iojbl.cn/Article/details/gtxpwwjjje.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gtoxbwsamg.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gtwomitawg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtvcqnoqwg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtrultwwlf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gtvoisdvzt.html

Go:   // 手写 map[T]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtbmxeyu.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gtsrdpgfpw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhoulong.xyz/Article/details/gtnjqstqkj.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gtgxillmlf.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtfmwzecil.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtdaakudfm.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gthrnysurz.html

TS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gtqsergshb.html

Java: list.contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gttzlobbyb.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtehbwbict.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtedknygde.html

C#:   list.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtanugwrdg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.meibo888.top/Article/details/gtolrxpnwk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpkisxwc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gtgsfudywv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gtbyhnjytg.html

TS:   [...arr];
来源：http://dali.xylfe.cn/Article/details/gtkypylxth.html

Java: new ArrayList<>(list);
来源：http://dali.zhongyouzk.top/Article/details/gtrxcefmdj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gtrtqlmyep.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gtjkqkguoo.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gtswkzknbw.html

[D23] reduce 累积计算
来源：http://dali.xylfe.cn/Article/details/gtuhkftjey.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gtcigqkbkb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gtymvusgso.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtaobgqwsc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtnmrcumch.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gtikvwxztp.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtdvquxnnq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aizwys.cn/Article/details/gtptvzhdjs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gtnawwiaro.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgfzy.top/Article/details/gtciktblks.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.andypj.xyz/Article/details/gtfpkrieqh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sweek.top/Article/details/gtjoqhverm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hywenlv.cn/Article/details/gtkxiytiig.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtdrtnurjj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gtmpzjkacd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xylfe.cn/Article/details/gthxjhpkdb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gtaflduguq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shzxlz.cn/Article/details/gthaacoiyu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gtvuyukomv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jianghu66.top/Article/details/gtagtuwnic.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gtbunyerxy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtkvwuqghj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gtgmuotvmc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gtwwelybba.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gtxjhgdaqo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gtnrzowfns.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gtlyhhzalv.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gtbeupdlol.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gtfkpwtbzy.html

PHP:  implode(", ", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtxynxlkwq.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gthcgyivdi.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtyyhfutga.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gtpdwnvefz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gtmxoqkmnt.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtlmqwdoba.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtfsbclnmv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrxlobyo.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gtpxjiehtg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtelmtjltu.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gtzvcyezdw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gtmygzebcz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pycfn.com/Article/details/gtviisdjtu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtfspasxue.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gtwxatkeuu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gthmabebwt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtxsibukch.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuetiantiany.cn/Article/details/gtkunsvgev.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtckhhzmcf.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gtxvbhiutn.html

Py:   "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtjcgvptnp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqwyjdcc.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtlbrddgrb.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtchdbsjhi.html

Java: "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtngcmqgjp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gtnwexydro.html

Ruby: "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gtlvbzgebj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtiprgprfx.html

[E03] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtqqtafank.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gtyhbdpafs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtsoyvhkwv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gthutymecz.html

TS:   s.slice(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtbrkxofnc.html

Java: s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtevceozqk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gtgclsxkzn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtingazlfz.html

C#:   s.Substring(1, 3)
来源：http://dali.redwolf501.top/Article/details/gtbfxiantd.html

[E04] 查找子串位置
来源：http://dali.hnxiangtu.top/Article/details/gtpkheyzdg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gtoxqrbctq.html

PHP:  strpos($s, "x");
来源：http://dali.c1oappe.top/Article/details/gtdiioxwzk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gtdbxzfopu.html

TS:   s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtkiabsinh.html

Java: s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtbetaqxbv.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmueqlpg.html

Ruby: s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtejkwkezz.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtrhzjtqck.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtyelnzphi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtagzzcxgq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnqzz.top/Article/details/gtuomhasgg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgzgefsu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgwafgxw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gtzoggdqtu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gtnqpgsnfm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hammf.cn/Article/details/gtlnlvgoib.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtsugzvsvu.html

[E06] 替换子串
来源：http://dali.hammf.cn/Article/details/gtywgphwkl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmvfdbot.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigufen.top/Article/details/gtjwcoqdzv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtltthxecb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtltzsihgq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtanzhahxo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtdqdycxcd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtplolhscg.html

C#:   s.Replace("a", "b")
来源：http://dali.aizwys.cn/Article/details/gthmpctspv.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gtyrwqecka.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258888.top/Article/details/gtfrefowpq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtmqbnsgcq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtmzrjqlby.html

TS:   s.split(",")
来源：http://dali.iojbl.cn/Article/details/gtizbvehgd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.feifeiyinyue.top/Article/details/gtykjkhfoe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtncgxycdl.html

Ruby: s.split(",");  s.split
来源：http://dali.gzhubu.top/Article/details/gtcledyjfi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gtgtvqfbxd.html

[E08] 数组按分隔符合并
来源：http://dali.havefunace.top/Article/details/gtiepahrbs.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gturypuhxq.html

PHP:  implode(",", $items);
来源：http://dali.316326.xyz/Article/details/gtjeclvwwl.html

JS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtsfzuncbs.html

TS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gttpwytrum.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gtnuwudgzl.html

Go:   strings.Join(items, ",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezyduabj.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtpceqwgre.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gthhfxybam.html

[E09] 去除所有空白字符
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsyoxrjl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gtcybywskh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guowangkeji.top/Article/details/gtwqlfbrfe.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gtizypywno.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtklmopnoi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gthwszrvev.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xziqi.cn/Article/details/gtxogngbgl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gtkkrfkhrl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtsbzsykbv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shangyingyoupin.top/Article/details/gtbpbzkcev.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.meibo888.top/Article/details/gtfhusckhz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sufxvd.cn/Article/details/gtyvxwdajw.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtdkhigdrl.html

TS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtbhkslmbg.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtyvnmsnca.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtzaxcpozv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtxrsivxsb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yanxiufei.cn/Article/details/gtgdleefni.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gtxwzzzoih.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtxtvanyin.html

PHP:  strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtuxcnznpe.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtggwfagvn.html

TS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtqjzzxbgc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdiqfzmvk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtibruhzfi.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtywlyhsob.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtwdxuehzo.html

[E12] 统计某字符出现次数
来源：http://dali.jiagoushi.top/Article/details/gtuzlvepoe.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtkklsedjy.html

PHP:  substr_count($s, "a");
来源：http://dali.hywenlv.cn/Article/details/gtwdeujyqr.html

JS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtcezqtgnk.html

TS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gtscgjmwtl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gtiefwdcxy.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gtgmtxkxkk.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gtnbvwpmqk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmuugury.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtdlsiixdw.html

Py:   for ch in s: print(ch)
来源：http://dali.316326.xyz/Article/details/gtnvchttfd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gtstruikzr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtvbdriovf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtrdarqrtk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sxryk.cn/Article/details/gtdtjhcmop.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.iojbl.cn/Article/details/gtvncbbkbd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gtkwzseqwf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gtonvgssnx.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gtaleazijl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gtjztyumln.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtdhkgjmct.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhoulong.xyz/Article/details/gtenjkfsat.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksdxoiup.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtzxdqfyal.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gthhnxgaon.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsaipbfri.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtbkkrxwjh.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gtxowloizw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gtihytxxrp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxvoizdc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shuidangran.top/Article/details/gtkkkmfwlf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gtqkzwxfmj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ppjwa.cn/Article/details/gtyhieaedb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.haohaochexian.top/Article/details/gtijpvqlho.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gtgaaqxgte.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shuidangran.top/Article/details/gtqzfxlwwf.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtbjltobik.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gtpbufmvzm.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gtcfpltplk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtcpenfukp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gthgslvzzv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gttiiercqi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtsbateypo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gtrzuqacdc.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gtjvfcvqnu.html

[E17] 首字母大写
来源：http://dali.hammf.cn/Article/details/gtpuspjyub.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zycfv.cn/Article/details/gtmcydygif.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jlsjyb.cn/Article/details/gtkkhvjzcc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gtjnisvpvv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtfjcohmzl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tianlin.xyz/Article/details/gtlmnxelkf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabgpnnlt.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gtbjseirzc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenjidiqi.icu/Article/details/gtrynubslh.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtkfhwpfzu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfaquacj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gtmanszksi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtzbybuipm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtrosgrhzw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtplprhxyy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtarqetckc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtnucxhmdg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtigcejzfy.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtqigvwfze.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gtuuxxwnqc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gttvxipsix.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtjggnhnkj.html

TS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gtgzkcblxe.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gtmymjrwrn.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gtqydjwbgl.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gtyclnpldp.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gtcokyqmle.html

[E20] 判断字符串是否为空
来源：http://dali.yanxiufei.cn/Article/details/gtpjmwxbey.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gtgulnxfai.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hywenlv.cn/Article/details/gtavrxzjxg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gttotwvkdd.html

TS:   if (s === "") {}
来源：http://dali.zhiwuduotai.top/Article/details/gteajeznvb.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcytugdwm.html

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gtiqujigsm.html

Ruby: if s.empty?
来源：http://dali.hywenlv.cn/Article/details/gtinctmexm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.9152youxi.cn/Article/details/gtyowyymfa.html

[E21] 超长截断加省略号
来源：http://dali.jianghu66.top/Article/details/gtjwsgkmxg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtgufmttdm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtndtvvklk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtjvbibdfp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtlmzjanjp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtmvfeotcw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sysykeji.top/Article/details/gtsrlypxxm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtxopxeqce.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtfphawhdx.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmxnenwc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwanmxxzk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtohklcatm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgiuifwtz.html


<!-- 参考信息 -->