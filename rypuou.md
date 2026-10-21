代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtycaygxch.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtymtwxyqk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenjidiqi.icu/Article/details/gtslkbojee.html

Go:   slices.Index(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtauzyelbs.html

Ruby: arr.index(x)
来源：http://dali.yj20258888.top/Article/details/gtplnvcuus.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gtoaggvlvk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gtzaffwibr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtswqwwtrd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.havefunace.top/Article/details/gtfskcaulw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtjrkjvhbc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gtloxqrszo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yvedp.cn/Article/details/gttlrcdicq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gtkvqmdsfw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtyuhabjzb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gtfzupweqs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxinkj.top/Article/details/gtixywikjb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.316326.xyz/Article/details/gtmmninmwk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtehtjnnze.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtqwpeysap.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtarsnvexl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtngmpmacj.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtonefczmk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gthlayscpk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtsdsvfdws.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gtqaiibjkm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gtvuzytrnt.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gtcwwrjpub.html

JS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtepmwzzag.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtxknvwyud.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gtpkvsxpzo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangdashe.top/Article/details/gtaiokdgpe.html

Ruby: arr.uniq
来源：http://dali.yueranfly.top/Article/details/gtuancippi.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gtftcojyyi.html

[D16] 求和与平均值
来源：http://dali.jinghuilouyu.cn/Article/details/gtovzggxiu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aizwys.cn/Article/details/gtovmppbwh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sufxvd.cn/Article/details/gtxctofshs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtgdacmvao.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gttuvtxwvf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gtjiqiolsr.html

Go:   // 手写循环累加
来源：http://dali.feifeiyinyue.top/Article/details/gtiquugfkb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jiagoushi.top/Article/details/gtlsafbxga.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gtuhdujnwv.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gtdflvzryr.html

Py:   max(arr);  min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnoumgws.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gthgquxqru.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtsveljlxr.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gtcxswlzpj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gtbjuqnoae.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daxiang520.top/Article/details/gthfzxhcxr.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnaljrdwe.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gtowwctzjh.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gtffdxnmmy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gtnqgorxql.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gtvhlailot.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gtkefnyolc.html

TS:   nested.flat();
来源：http://dali.nanxuanxn.top/Article/details/gtfxhmvgfv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtygsjilrc.html

Go:   // 手写双层循环
来源：http://dali.tian-w.cn/Article/details/gtpejtilkg.html

Ruby: nested.flatten
来源：http://dali.jinghuilouyu.cn/Article/details/gtorwefjjp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtlnvruljo.html

[D19] 按字段分组
来源：http://dali.hnqzz.top/Article/details/gtgxuqpriq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gtlzgnktxr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gtomykmffy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfibsgpa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gtstvwjkpl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gtidkmxhlr.html

Go:   // 手写 map[string][]T
来源：http://dali.yanxiufei.cn/Article/details/gtjqrhwnwx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gtrtudtlbt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gtjicbhopg.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gtlalulwjc.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gtpyfpqmzj.html

PHP:  array_count_values($arr);
来源：http://dali.bjfxy.top/Article/details/gtibhwvfhw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtvulihsyl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtmcuezkdk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xylfe.cn/Article/details/gtjcorzvxt.html

Go:   // 手写 map[T]int
来源：http://dali.nwbrower.top/Article/details/gtiwenpjzy.html

Ruby: arr.tally
来源：http://dali.yongpay.top/Article/details/gtxnvimvbp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gtagzevqyz.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gtkrvjlrtk.html

Py:   x in arr
来源：http://dali.yangfankeji.com/Article/details/gthvlbozby.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gtbpcnwtzo.html

JS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gttoemsjlh.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtxskuyhph.html

Java: list.contains(x)
来源：http://dali.yonumen.top/Article/details/gtvgfoofvt.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtwsncojdh.html

Ruby: arr.include?(x)
来源：http://dali.yvedp.cn/Article/details/gtldacdpop.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtgzbayxyv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258.top/Article/details/gthwbycjgz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangdashe.top/Article/details/gtdvaxmnwe.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.meibo888.top/Article/details/gtrudqxgvd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtnupjfddi.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gtnpynptmf.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gtkzjrusba.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gtlttsutap.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gtfakthnmc.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gthkebiznv.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gtxdybrngl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gtrbyflhlj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gtktrnpbic.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtzfnhytkw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtzpdkmwih.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxuanxn.top/Article/details/gtmghnggbt.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtzymawzvz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258.top/Article/details/gtpadvwkvz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxinkj.top/Article/details/gtkabvldgk.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gtdrxbsoae.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hammf.cn/Article/details/gtyjdhsfay.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gtzsgsnonj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cucudq.cn/Article/details/gtxjiwsmvb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtmvdpnmbq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflosokbu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gttbnnazfh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nwbrower.top/Article/details/gtlwpaiwbd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.meibo888.top/Article/details/gtbdgzuktf.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gtqvwdbrdd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jyoumei.cn/Article/details/gtnbtjynol.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gtcwbnlptr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtekqzyipo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gtrejmeqmz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gtdrwjazdz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.birdmap.top/Article/details/gttchshhyz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gtnctpmbhu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gtqndhsftv.html

[D26] 数组转字符串
来源：http://dali.havefunace.top/Article/details/gtawdvtbbn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gtithzuwbm.html

PHP:  implode(", ", $arr);
来源：http://dali.yvedp.cn/Article/details/gtquwfroqz.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtuipbnqas.html

TS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtigwvwfix.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtnenvgvzh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvmtshsm.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtgzvizntt.html

C#:   string.Join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtjmldcvnc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtdmjucvsm.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gteuqsvayt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfhipsijg.html

[E01] 拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtwajfueph.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gtdprhughd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gtnneadcbs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtnwdqinnc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtpxlomydi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.bjfxy.top/Article/details/gttpyhrjwn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gtqwtxiksp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gtutipngtg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtfzogrmze.html

[E02] 重复字符串
来源：http://dali.yj20258888.top/Article/details/gttunatvkb.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtaknewqel.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gtbqcurhwf.html

JS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtyvnsvrhp.html

TS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtqucibomf.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtdncofnds.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gtwxdgcuou.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtenefukku.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gtqgjncqdn.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtqebejisr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nwbrower.top/Article/details/gtahdpbgdo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtkocyeayy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtlkkbhxhq.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtwggwmfbf.html

Java: s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtywmncxmf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtjkwqlkdo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jianghu66.top/Article/details/gtnwwaxtxf.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujbwebki.html

[E04] 查找子串位置
来源：http://dali.jinqigufen.top/Article/details/gtnvfwnmdp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtqzmyodhg.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gtvurmahzx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gtbxepfacc.html

TS:   s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtybmbyoee.html

Java: s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtofkycwyy.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gtktqklrwy.html

Ruby: s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gtpzahzglu.html

C#:   s.IndexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtamuqsxnh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gtoqxzwdcn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.c1oappe.top/Article/details/gtdwbzwwmt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gtdtaecjtm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtkmjwaijp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gtyrukbwoi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtajkgvbjb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gtoecvfkak.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xylfe.cn/Article/details/gtaluouijz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtiqdnywbp.html

[E06] 替换子串
来源：http://dali.yuxming.cn/Article/details/gtflngvpbh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtetxkoqrr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.0kj1m.cn/Article/details/gtkbuatzzj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtudenijxq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtewdgmkii.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtpfcoutqo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtcptucdwe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtlrfkfojc.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtzgsajzqo.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gtdsxvkenq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhiwuduotai.top/Article/details/gtjpzbovcy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtplrxiujk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqotqzwcw.html

TS:   s.split(",")
来源：http://dali.havefunace.top/Article/details/gtwezpvpak.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvrewmki.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xinyue.icu/Article/details/gtrqarbebp.html

Ruby: s.split(",");  s.split
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltndlajx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuetiantiany.cn/Article/details/gtswxkwewj.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gtequnfgsg.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gtqrxicgwm.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gtzmykdevu.html

JS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtqimvegkn.html

TS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gtijwtngjb.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtjdzxqsws.html

Go:   strings.Join(items, ",")
来源：http://dali.nwbrower.top/Article/details/gtpbyeabsa.html

Ruby: items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtfkszahqd.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gtclxifgcq.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gtjzuwubxd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgruuserk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gtkckloand.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtlidjwwfi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtqmdrhavq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.redwolf501.top/Article/details/gtdnfasvjw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtyfwafhmg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gtuiirvrgd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jianghu66.top/Article/details/gtbhleslld.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gtzuxipbys.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtmrgbtvqa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuanzx.com/Article/details/gtjbfotkdd.html

JS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtmfuinceb.html

TS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvvlpszp.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfxfsctx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gttwygnawq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtncfysdqz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtnuqrjton.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtxwaqbesz.html

Py:   s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gtqbdaccfg.html

PHP:  strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gtarxrhzbq.html

JS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtwgjdevzz.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtpmowifyw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.0kj1m.cn/Article/details/gtlofnvxmh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jiagoushi.top/Article/details/gttiwplvlq.html

Ruby: s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtgwjcefis.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtalxtwcxe.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gtrczctiux.html

Py:   s.count("a")
来源：http://dali.zycfv.cn/Article/details/gtrztgznpb.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefqvdaac.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtzgcvnxry.html

TS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtiylmuaej.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhoulong.xyz/Article/details/gtoixtdtkr.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gtknucsokg.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtrajlfshc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gtdutwjdgf.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gtorparazm.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gtmyvzbowy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtjbzrpubd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtzgromxbv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gthxawoxwo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtrznqytke.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sxryk.cn/Article/details/gtmumvaqoj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gtxlvoveqm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258888.top/Article/details/gtbhgywncp.html

[E14] URL 编码与 Base64
来源：http://dali.yvedp.cn/Article/details/gtljzufcmn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gtoeiexhtm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtszjtvcyd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gtdaxymtau.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gtdejygtlo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtefsfwyth.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gtfxmdnkpl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gtaknnzequ.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtiujlyeok.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrikfhicp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gtstixuwjv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuanzhike.top/Article/details/gtiusszhjy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258888.top/Article/details/gtfxleyagv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hfpthk.cn/Article/details/gtliqwvvwr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gtzoclgnaw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gtaclrxihz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gtdkjeedtg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gtivkfrtis.html

[E16] 数字千分位
来源：http://dali.yj20258888.top/Article/details/gtlidwbuop.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gtbfgghpmj.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gtdqhsxbrh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtkkuotsre.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtycxsljbr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtiyrgneaq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.0kj1m.cn/Article/details/gtqbvwyrtz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gtysnxbtos.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtwyrcrkoc.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gtfqskctea.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtxwqipmqj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ehwqpu.com/Article/details/gtfmjabbdj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtgemnluir.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtzlddkzjp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ppjwa.cn/Article/details/gtoyecffji.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.bjfxy.top/Article/details/gtohhraanr.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gtoferpznc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gtuanyfrct.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gtwdaxuuxz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gtvhzjqzam.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.kuanghao11.cn/Article/details/gtkjwfaamz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtfcdoxzci.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtiyvvpjvz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtdgdidwkp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxhnaoad.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gthansohqr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gtyegjdrkr.html

[E19] 多行文本按行拆分
来源：http://dali.fengsongda.top/Article/details/gtfmwxigfb.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gtptgbicbz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258888.top/Article/details/gtlxqvmxei.html


<!-- 参考信息 -->