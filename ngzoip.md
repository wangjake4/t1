代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gogol.net.cn/Article/details/gtyonsoqdv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ehwqpu.com/Article/details/gtjmdiqrko.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtycherfpa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtrgeydxcv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gtukethhzs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gtmsvzjsli.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.0kj1m.cn/Article/details/gtmaupawsw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ydzc1.top/Article/details/gtxwtjjmlc.html

[D11] 反转数组
来源：http://dali.cdnleiting.top/Article/details/gtsapscsph.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnxiangtu.top/Article/details/gtcrazujev.html

PHP:  array_reverse($arr);
来源：http://dali.gzhubu.top/Article/details/gtklgeibhh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gtukknebzd.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gtdfbncftl.html

Java: Collections.reverse(list);
来源：http://dali.jqgfzy.top/Article/details/gttkdujbrr.html

Go:   slices.Reverse(arr)
来源：http://dali.shuidangran.top/Article/details/gtxranlkcl.html

Ruby: arr.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtydgglcys.html

C#:   list.Reverse();
来源：http://dali.xuanzx.com/Article/details/gtlqerdsbn.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gtonwbwfvx.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gtovagtdlt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.snrcjt.cn/Article/details/gthnyurjcp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gtsxssoznv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtyuoibcji.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.svipenyu.cn/Article/details/gtcmqayqkk.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gttrlooeva.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtfnbjwrna.html

C#:   list.IndexOf(x);
来源：http://dali.jqgufenzy.top/Article/details/gtbyycpnzz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmkpumxl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtxzmlobnc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sweek.top/Article/details/gtofwioiin.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gtdmdjkwvs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtivahekmr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gtdkubcsvu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.snrcjt.cn/Article/details/gtbqcjieqy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guowangkeji.top/Article/details/gtbprljvow.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gtswgozenv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gtrulncvod.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gtmrkyhewx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtiyxyeufx.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtyuzfltlk.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtlyosuzgr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gtbklafcdq.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gttlmpuagk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtgygmjige.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtbpnwnbis.html

[D15] 去重
来源：http://dali.jinqigfzy.top/Article/details/gtlivwhnvg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtfctvhprs.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtjglodskg.html

JS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtuhkrymco.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtfckfbzho.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yanxiufei.cn/Article/details/gthmnbjlte.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.andypj.xyz/Article/details/gtcxswzgnw.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtajrjacfe.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gtfpoeqbsk.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gtuzaajtyk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gttpmefwqr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gtyrnnjrds.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtcyrynpzp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gttwiucrti.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfjuhbvj.html

Go:   // 手写循环累加
来源：http://dali.0kj1m.cn/Article/details/gtsvnjumia.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtrhdhiryx.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhengqikj.top/Article/details/gtmnoaiipg.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gtayzvlkqd.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gtopiopgdj.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtdioauaqh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guannengcc.top/Article/details/gtoorjhqdx.html

TS:   Math.max(...arr);
来源：http://dali.nwbrower.top/Article/details/gtbtxfdysc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxuanxn.top/Article/details/gtouxvsmug.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtjqzziilg.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gtkdasmstg.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gtysgzezvc.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gtummaswxg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yueranfly.top/Article/details/gtxljgkkbu.html

PHP:  array_merge(...$nested);
来源：http://dali.gogol.net.cn/Article/details/gtkchajfjt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gtmqjokbrv.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gtdmbbkeqv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gtjmlitupx.html

Go:   // 手写双层循环
来源：http://dali.yj202588.top/Article/details/gtujvwtqlt.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gtbikarylw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cashguo.top/Article/details/gtbtdjrgqy.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gtvnmceznv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtbenkndet.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gtwcgrhdmw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwditwbel.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtyvvpqjgr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yonumen.top/Article/details/gtrsjsnbfw.html

Go:   // 手写 map[string][]T
来源：http://dali.feifeiyinyue.top/Article/details/gtmfxhwehs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhengqikj.top/Article/details/gthgrbqpdh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gtiaeywbsm.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gtbsyjowue.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gtllqgmnbl.html

PHP:  array_count_values($arr);
来源：http://dali.zdqjudy.top/Article/details/gtxvuiqeby.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtvddxrrdp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gtoqanvyyy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gtplwihnlr.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gtdpdtqjdz.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtdqjwfjbu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gtttxbtkls.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gtarlkkulf.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gtqjdktycw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gtvgaxfxxz.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtpuvytoee.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtikgifjue.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtdgmltmwa.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gtxhgcinkw.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gtmqlpitml.html

C#:   list.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtqwqjckrs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gtefcurjgy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gotoacloud.top/Article/details/gtohughkrp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gtzflwnimo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtiacyvzad.html

TS:   [...arr];
来源：http://dali.havefunace.top/Article/details/gtmqqbwvvu.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gtyydevucw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gtjmzznzmj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ybcxt.top/Article/details/gthnhocjvr.html

C#:   new List<int>(list);
来源：http://dali.nanxuanxn.top/Article/details/gtdzntzxqp.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gtonwzrlde.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gtuuybailg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gtpulrokjz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqdqftvo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtucnwyuxk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gtcmzdlejc.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtmoqureul.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gtjwkxqzzc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gtcsacrhkn.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gtkyhgysje.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtmgkljxhc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gtyjanarfa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjzbtpfv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtrpsqxqxq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yongpay.top/Article/details/gttwqqdvdi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gtaepzuqwj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gternxljfz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gtvkshahkb.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gtbgkctxap.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gtwqdurwdo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixjfqdhn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.bjfxy.top/Article/details/gtqzmtftdh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gtztktdxnc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtvkeshuxz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gtdaxxlcvw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtdjzrfduc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtbxndzxgk.html

[D26] 数组转字符串
来源：http://dali.aibaodan.cn/Article/details/gtccqxvszq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtffnjklzb.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtjlkkjrra.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtrnrbzoob.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtitpwlowr.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gttoawncqh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtrndlwtyx.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtnumywabl.html

C#:   string.Join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtyxvfberb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtflcfdsxv.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gtofoxsmfe.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtlwseszeu.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtsjrhgmzc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jiagoushi.top/Article/details/gtsjtnncni.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gtbparlxal.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtehitfrlv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtlcdrxggo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuetiantiany.cn/Article/details/gtctrlonzw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gthqycxgqg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigufen.top/Article/details/gtiiqeguau.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtndulgmnz.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gtxyfydflq.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtrbgouomc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenlongwang.top/Article/details/gtzlglmyil.html

JS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gttsvfkotf.html

TS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtqyljlshf.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtysghdply.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gtttttnlbc.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndvkiezv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gtmlzsrcjs.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtpcqfjisi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nwbrower.top/Article/details/gtxnobzevt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtzblxmcrw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtiqxgqcrk.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtbwrzyokb.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtxicnyawr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shuidangran.top/Article/details/gtnlhsndao.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.bjfxy.top/Article/details/gtggzicarj.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gtnqyaszad.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gtbcmufurj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtcfzmjjml.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gtcrmnxwgk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gtadocmlkg.html

TS:   s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtfnwjyrrr.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gttnguxfmw.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gtykievcpq.html

Ruby: s.index("x")
来源：http://dali.daria6918.cn/Article/details/gtbfhvyker.html

C#:   s.IndexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtlynsuyzh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.iojbl.cn/Article/details/gtdjubjecd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gtnsjarkbm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gtiigsajdq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtotwlawlr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gtkktolbbd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtszddubef.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tianlin.xyz/Article/details/gtpodffcyr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cqqwz.cn/Article/details/gtefhbquei.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtqolbeocf.html

[E06] 替换子串
来源：http://dali.jyoumei.cn/Article/details/gtgcuhlfjo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtrfjxomet.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbatvpkg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtqhytvnvu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtfgbumpor.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxaycabhu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtxzmpvhvx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtbekqyuue.html

C#:   s.Replace("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtklcdvngg.html

[E07] 按分隔符拆分
来源：http://dali.gogol.net.cn/Article/details/gtoabnkaqj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.0kj1m.cn/Article/details/gthnxsxgbb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gthfvcpvyr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtjcwoxckf.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gtbutqydby.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ehwqpu.com/Article/details/gteudthnlk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtpotqyvax.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gtgaluegpb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuanzhike.top/Article/details/gtmdlansmz.html

[E08] 数组按分隔符合并
来源：http://dali.vqdsnc.cn/Article/details/gtperpyexr.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gttwtxhswi.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gtmrggrfdg.html

JS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtdrkrkzsj.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtttilclhg.html

Java: String.join(",", items)
来源：http://dali.redwolf501.top/Article/details/gtrripzudu.html

Go:   strings.Join(items, ",")
来源：http://dali.guowangkeji.top/Article/details/gtkozqixqa.html

Ruby: items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtwwtbphjz.html

C#:   string.Join(",", items)
来源：http://dali.iojbl.cn/Article/details/gtcwkjodvq.html

[E09] 去除所有空白字符
来源：http://dali.pycfn.com/Article/details/gtcslfxqlz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xinyue.icu/Article/details/gtnvcvvnbi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtitlenamr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtmjimxnoh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtvmrpnuzj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gtposrxprd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ivvv.top/Article/details/gtminljgbw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.0kj1m.cn/Article/details/gtbmuwlkey.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtpmdcdymx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gtbqegfpoq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtufmflnou.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.316326.xyz/Article/details/gtdoxfbtcs.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtwuezsncr.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtchakebrb.html

Java: String.format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtdfiotuqy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtfkbbczic.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtenrmioag.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pycfn.com/Article/details/gtrxkqwqzm.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gtnrtezepn.html

Py:   s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtwaejbsmc.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtpdwkdbvo.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtkkeuwbld.html

TS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtgwnboiiv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dianchejie.cn/Article/details/gtptssgdwd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gtivkbgtii.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtymzifthg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtaqmlnwxh.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gtxvvlkffk.html

Py:   s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtcmeroeuc.html

PHP:  substr_count($s, "a");
来源：http://dali.cheryme.top/Article/details/gtxicbyifm.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtwmgdwgwy.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtiigyzgrb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.9152youxi.cn/Article/details/gtdgseiqzh.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfopbovxi.html

Ruby: s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtdwybysem.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gtyexkoyzj.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gtjkjnmzgo.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhfvapry.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.mhx1999.top/Article/details/gtenvsoprj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtukqjkepb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtvhruxadr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ivvv.top/Article/details/gtqoqnoogr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxeyownwv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gtxrsvxtoy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtnbzushpn.html

[E14] URL 编码与 Base64
来源：http://dali.ivvv.top/Article/details/gtmtoazvgz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtenwczzxc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aibaodan.cn/Article/details/gtikqbiept.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gtuelsycuh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.havefunace.top/Article/details/gtnziyebji.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtyktdpecs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gtfopplijr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fengsongda.top/Article/details/gtypzohvlc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gtvbjzmftb.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gtcxsmtush.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zycfv.cn/Article/details/gtyxktlisg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtrabtmava.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gzhubu.top/Article/details/gtrdpdzeaj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gtjoaotlwg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guowangkeji.top/Article/details/gtoqrfkrwq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gtvnnyxajw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gtxhstqfgr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtseigxwqb.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtsaqquwar.html

Py:   f"{1234567:,}"
来源：http://dali.jlsjyb.cn/Article/details/gtslezeeda.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gtqioychly.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtcxavmyox.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkngnneez.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtdrczzlbd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shzxlz.cn/Article/details/gteaulcfbi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.9152youxi.cn/Article/details/gtzsspnhtu.html

C#:   1234567.ToString("N0")
来源：http://dali.vqdsnc.cn/Article/details/gttzhsugyj.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfpoafqw.html


<!-- 参考信息 -->