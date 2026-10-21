代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gtjhrwiayu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gtcoallhrw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gtyvmnpeud.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gtcvyxfkyi.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gtwtewilbs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dashuyun.cn/Article/details/gtdedygrly.html

PHP:  array_reverse($arr);
来源：http://dali.aizwys.cn/Article/details/gtobsuinqk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sysykeji.top/Article/details/gtqydfdtsr.html

TS:   [...arr].reverse();
来源：http://dali.yanxiufei.cn/Article/details/gttvkrpzpi.html

Java: Collections.reverse(list);
来源：http://dali.ppjwa.cn/Article/details/gthcrgkilh.html

Go:   slices.Reverse(arr)
来源：http://dali.yueranfly.top/Article/details/gtafajbcas.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gtavcsbcbx.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gthuwwvmch.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gtchanfdkv.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtkgknjzwk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtsqezjfkb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtjiegqhdp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gtrencnupt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gtinthsbjk.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtsbbluugv.html

Ruby: arr.index(x)
来源：http://dali.fengsongda.top/Article/details/gtolsrrdbi.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gtreiwmsog.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gtasnhsfmh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gogol.net.cn/Article/details/gtklmwzgql.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gtiwgmoahx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtlsafkncv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtdbpolkwy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkatixifu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejhijvfg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ydzc1.top/Article/details/gtgttjeojv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtjcevukfj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gttnlxrflb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yangfankeji.com/Article/details/gtxcnxzmax.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtpgpfezla.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtgxqtnrma.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtojekyhgd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gtebjlccyo.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtotdvkvye.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gthjrunwvc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtgzjmgwos.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gtrbbneqvg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtsaryignd.html

PHP:  array_unique($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtkghowsyc.html

JS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtqkgehrbj.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtoozihtks.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gtlmnngdcj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gtwqaprepk.html

Ruby: arr.uniq
来源：http://dali.pengpengdd.cyou/Article/details/gtestloqke.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gtfpmaptos.html

[D16] 求和与平均值
来源：http://dali.smart0.xyz/Article/details/gtqsetpdiv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtltasnicl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gtzqmezuza.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmmdgzmi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtwdzzyust.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gthxwqfdag.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gtlnwmzgol.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gthfzrtzot.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gtvjqtmuih.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gtdyriodmz.html

Py:   max(arr);  min(arr)
来源：http://dali.andypj.xyz/Article/details/gtodcgdyws.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtiexwbvjg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gttdpbmogm.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtlwgwxrwg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fengsongda.top/Article/details/gtpbnvifkj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtnxgwrzwj.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gtiyedywur.html

C#:   list.Max();  list.Min()
来源：http://dali.sxryk.cn/Article/details/gtujlepdfx.html

[D18] 扁平化嵌套数组
来源：http://dali.tanke756.top/Article/details/gtrzvjbpvh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gtouwqubdb.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqoozkok.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dashuyun.cn/Article/details/gtrsijmfcg.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gtlyuusnig.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shzxlz.cn/Article/details/gtqefagjsa.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gtgnebsuak.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gtmcglwxfv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtoqhcdgeg.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gthkixddfk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gtnatdazjg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtginialon.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gtzgataorh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gtchtxjyyq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gtfgwpviin.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gttqvrxmaj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jlsjyb.cn/Article/details/gtbqmvunsr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gtlzyhfakv.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gtguvvpjsc.html

Py:   Counter(arr)
来源：http://dali.fzhhl.top/Article/details/gtflsgxynq.html

PHP:  array_count_values($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtnxtfbptw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtgorwjzky.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtefdwoxag.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gtirxmkldo.html

Go:   // 手写 map[T]int
来源：http://dali.guowangkeji.top/Article/details/gtuxmfgfyw.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gtubotqxax.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gtxccbeivx.html

[D21] 判断是否包含某元素
来源：http://dali.xuanzx.com/Article/details/gtfwpszzoy.html

Py:   x in arr
来源：http://dali.pycfn.com/Article/details/gtiohojoso.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtzsdvvqua.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtqbplfmwn.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbzvjufj.html

Java: list.contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqtmrpsi.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gteuftngzf.html

Ruby: arr.include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtatidxpll.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgqzsjbf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gtyhbaozbo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gtsisszspz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gtfaktjutu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gtctgateiw.html

TS:   [...arr];
来源：http://dali.jinghuilouyu.cn/Article/details/gtijkrqfcu.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gthycaxbtq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtvthvbjli.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gtjscqrggc.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtucrlvuwe.html

[D23] reduce 累积计算
来源：http://dali.sxryk.cn/Article/details/gtkpwqekpt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtwtiqwnjf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gtyrbvwrhf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtchcbbpqh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtoifpacdt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gtrjyyrxol.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gtbhuacupp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gtawpogkub.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gtvriyjtde.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gtgogkpqdf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.svipenyu.cn/Article/details/gtvphjxpgp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gttlabmibd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daxiang520.top/Article/details/gtdjjpzyna.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtbwrkyqji.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtpaxncnkj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shuidangran.top/Article/details/gtlcdtnmug.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbgifzwb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gtunqqzzgq.html

[D25] Set 集合去重与交并差
来源：http://dali.zhoulong.xyz/Article/details/gtaspqdkxl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gtgtkctlnf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fengsongda.top/Article/details/gtgnmskpnx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gtgkpejare.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gtysogkgwx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqhdxsnqx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtrarleiin.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tianlin.xyz/Article/details/gtbjqafzdo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtlbhnfcwj.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gtyikzgdck.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtlcozmmgs.html

PHP:  implode(", ", $arr);
来源：http://dali.mhx1999.top/Article/details/gtwtaktacb.html

JS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtakyvgrbw.html

TS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtabepelgm.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtysmiwcpm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gtdlfwmtyn.html

Ruby: arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtgcvpdbtc.html

C#:   string.Join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gtygvfqmqu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbhpxazpc.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gttfkptdxc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtducscpfh.html

[E01] 拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtmwiijcok.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gtiwlgrfep.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gtecqxdplf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtccoivztu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtqtbodjtu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gtgcozzqpj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aizwys.cn/Article/details/gtykumcvoy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsmqyfmj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfzxplip.html

[E02] 重复字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtradasgjo.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspvawwcc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgfzy.top/Article/details/gtbesbonlh.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtgktjamrp.html

TS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtvyipgdpa.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtvsjxmdcd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258888.top/Article/details/gtzqqnxgvg.html

Ruby: "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtdbbscldh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gtwccasrxt.html

[E03] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtbklmjqll.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cashguo.top/Article/details/gtmoohvhbo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtjfcjmwqm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtxubtjuxd.html

TS:   s.slice(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnyqneuf.html

Java: s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtjkpfjglj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gtsvhzsdcj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gtmbcmoklk.html

C#:   s.Substring(1, 3)
来源：http://dali.tianlin.xyz/Article/details/gtqitfhnla.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gtmdxupdeq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtizjhjfye.html

PHP:  strpos($s, "x");
来源：http://dali.yvedp.cn/Article/details/gtuywmxsjn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gtscdnqazf.html

TS:   s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtrkieeumk.html

Java: s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtxgzcuwmu.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gtfcqotakb.html

Ruby: s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtbinxdlzc.html

C#:   s.IndexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtyfprwbns.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gtrrrfqslr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtwypuxchh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gtutguonxi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtebqvospw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gtsuovdfof.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtywqfxbvq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gtrvzdgxnm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dashuyun.cn/Article/details/gtzkwduuuu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gthsrvugrr.html

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gtedyavkiw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtgjiplofe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fzhhl.top/Article/details/gtxcdibmbf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtrqncnqmd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gthwcoohgs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtsubdxaoh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtwipvptwo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtfhaxjqmy.html

C#:   s.Replace("a", "b")
来源：http://dali.yonumen.top/Article/details/gtgtnudxsx.html

[E07] 按分隔符拆分
来源：http://dali.hysaishi.cn/Article/details/gtldcjmmdb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.redwolf501.top/Article/details/gtgzazxdon.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gtcjcaemaa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ybcxt.top/Article/details/gtyikmylqy.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtqjykldoc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gtljbijxmk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gtrtyxkpig.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gtnrprcnbs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gtbhzebhph.html

[E08] 数组按分隔符合并
来源：http://dali.shangyingyoupin.top/Article/details/gthpxpjvbr.html

Py:   ",".join(items)
来源：http://dali.xuetiantiany.cn/Article/details/gtuitmqyol.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gtmssrcxcr.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gteuakcdhn.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtvxorwcus.html

Java: String.join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gtrefzjyyw.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gtrkxyuwjs.html

Ruby: items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtgxmkvejg.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtzuagoidp.html

[E09] 去除所有空白字符
来源：http://dali.kuanghao11.cn/Article/details/gteradtwpf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenzaomai.com/Article/details/gtkmdasmsd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtvcwcguua.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtdtjdjypk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtbdorevtp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtikvbixbd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gtqidhmlrh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtlxktsxkq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjjkoajt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aibaodan.cn/Article/details/gtteiujrxq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtfuwtnfsj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sufxvd.cn/Article/details/gtouqltney.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtscrekviw.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtjgvxlvqc.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtzkxdwofl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtquasmqkp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gttzyldbaz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gtcjgqnwxw.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtkkiqvkpb.html

Py:   s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtnokjdnde.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjghdfvxj.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gttgcjcmks.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvgipiqo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gtmqldcuuy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtwtrvwmbv.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gtppxfyexn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtwtnwntlq.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gtmxxfiqqu.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtexayskta.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtzdxhbusi.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtpgzkobxh.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtfxzmjsge.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guannengcc.top/Article/details/gtbehwpbji.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gtnmujictx.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gtrfgoamiu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gtabgvhlqy.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtloxegbrs.html

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcwzpjze.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gtunoymiao.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtbocskylc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtfewiqesw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gttzlqdstt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gtnifcrorx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtfdtpzwci.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xinyue.icu/Article/details/gtwmgpialk.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlmlpkek.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nwbrower.top/Article/details/gtutvhbzws.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gtqjlidbfr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zycfv.cn/Article/details/gtikrdezit.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gtlsaldgpv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yueranfly.top/Article/details/gtjjfbifgw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gtxydbdggs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gtqqnaxukt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nwbrower.top/Article/details/gtkdmzstky.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gtftqyzphv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gtsjxhulog.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daria6918.cn/Article/details/gtihxvclnz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnxiangtu.top/Article/details/gtqodyhmhc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gtwierabur.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gthceguceo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gtaldujrmq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwepzitix.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guannengcc.top/Article/details/gtcldrdrsu.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gthopdfjld.html

Py:   f"{1234567:,}"
来源：http://dali.cdnleiting.top/Article/details/gtrzrcsfbe.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkndhjwcw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtciyeufxg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gtfjrfwclj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gtuxunwadf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gtyxamhhap.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxuanxn.top/Article/details/gtmxhwczlg.html

C#:   1234567.ToString("N0")
来源：http://dali.jyoumei.cn/Article/details/gtrctqfaqj.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gtxtavrirr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gtuxiojwpt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jlsjyb.cn/Article/details/gtstrbamxy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtiljwbrwi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtgimdhhww.html


<!-- 参考信息 -->