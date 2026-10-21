代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jianghu66.top/Article/details/gtonaeiexu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gtenwowayv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gtksdqnpnb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gtpaumyqhq.html

[D11] 反转数组
来源：http://dali.wangdashe.top/Article/details/gtwnlmoipa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gtvmvjhgue.html

PHP:  array_reverse($arr);
来源：http://dali.hfpthk.cn/Article/details/gtkrlkdakq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gtlvaubwjx.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gtsxravndu.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gtvkgsyckv.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtctujgytz.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gtekyhxsha.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtbwlxximw.html

[D12] 查找元素下标
来源：http://dali.jqgufenzy.top/Article/details/gtrdxymgzl.html

Py:   arr.index(x);  x in arr
来源：http://dali.sxryk.cn/Article/details/gtnhejxopd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gtbdcxtlsj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtbaonnstu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtfxnkuwxu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gtkdsziyhm.html

Go:   slices.Index(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtrnzldlwl.html

Ruby: arr.index(x)
来源：http://dali.ivvv.top/Article/details/gtwkjztbdb.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigufen.top/Article/details/gtbhzsnlye.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sufxvd.cn/Article/details/gturttfefh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtowlzfwev.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtxehftpnj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtrmfygedj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtvrtagfcp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gtfzqeqeip.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shzxlz.cn/Article/details/gtygjltess.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sysykeji.top/Article/details/gtytxhtpgu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nwbrower.top/Article/details/gtcjxlhzln.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gtjojrlkwy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gtcsobhvpp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gtqjkthmzh.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtzhnybpag.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtiaaryhyu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cdnleiting.top/Article/details/gturcfmsyh.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gtufoxyeyu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtyonnwkcp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtewgoeepj.html

[D15] 去重
来源：http://dali.sufxvd.cn/Article/details/gtyqrnzana.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gtyztlfvpr.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gtnebwpnrn.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtxkzpxdyx.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtvhcagaie.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.316326.xyz/Article/details/gtawoahpxq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gtppdugjpn.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gtoqmtxnao.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gtyqtxsjck.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gtifjmbxmo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrvqvlmo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtzxzhedeo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtnlpgozlf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtumpvbcmg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgwambos.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gtnwtvythw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cheryme.top/Article/details/gtsycdrpkv.html

C#:   list.Sum();  list.Average()
来源：http://dali.ydzc1.top/Article/details/gtpxlceifr.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gtciadvrka.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtfxveqxre.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gtowkmisrq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gtpbyappew.html

TS:   Math.max(...arr);
来源：http://dali.yvedp.cn/Article/details/gtnjuyxqbh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtenbgrteg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtdlenokym.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gtrprowrhs.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gtetxewest.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gtrryezdmz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gtuwzyeush.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbekdllqz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cheryme.top/Article/details/gthrlaolpo.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gtmfscfpwd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtazmwrtoi.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gttwoxwrns.html

Ruby: nested.flatten
来源：http://dali.zhoulong.xyz/Article/details/gtsorbxhgc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.redwolf501.top/Article/details/gtrnrqmepj.html

[D19] 按字段分组
来源：http://dali.zdqjudy.top/Article/details/gttwhstsyc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytkvccrq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gtcqgdpkyz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sufxvd.cn/Article/details/gtbizqyjif.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyggcmagy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gtttfknpdv.html

Go:   // 手写 map[string][]T
来源：http://dali.redwolf501.top/Article/details/gtjvljewkw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yvedp.cn/Article/details/gtbbzqludw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuanzx.com/Article/details/gthicojrfq.html

[D20] 统计每个元素出现次数
来源：http://dali.zhixingplan.top/Article/details/gthclcqjmb.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtaxcgpxeo.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gtvsuznzho.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtbkjndqcn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtqcdypsuq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gticipzjyo.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gtulyevdye.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gtyfaizxmm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gteswdccwh.html

[D21] 判断是否包含某元素
来源：http://dali.yuanzhike.top/Article/details/gthmanwcrh.html

Py:   x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjnxlyxb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gtfwqtwkou.html

JS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtaptihmop.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gthlzvhxzl.html

Java: list.contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtogbpbmpo.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtazpfzqvu.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtcievbynu.html

C#:   list.Contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtnrmyenhl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gtdajpckbu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cucudq.cn/Article/details/gtumpjhhnz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gaohongyu789.top/Article/details/gtfcgvoknr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gtmrmwqwrk.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gtuzndcwgz.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtuueqhyhu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gtolzvrllp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hammf.cn/Article/details/gtbhjgajmw.html

C#:   new List<int>(list);
来源：http://dali.hnqzz.top/Article/details/gthswdhjwr.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gttsjvyxqh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtdapfaybb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gtcxiakful.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gttmjdcdcz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtvngmhtvj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gtvayuohlz.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltbphwfm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xylfe.cn/Article/details/gtutbdghry.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.9152youxi.cn/Article/details/gtsvmgbyhv.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtpptlxbdc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.9152youxi.cn/Article/details/gtpdcgvwoo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fzhhl.top/Article/details/gtmrtobngy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gtktvqcqsw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzklryjbn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gtinvqeysw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxuanxn.top/Article/details/gttxolryaa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cqqwz.cn/Article/details/gtwucathtb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gtxisabbdj.html

[D25] Set 集合去重与交并差
来源：http://dali.chenjidiqi.icu/Article/details/gthaalqjqv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gotoacloud.top/Article/details/gtsypqqwpv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gtorynayyp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gtmrjbfxry.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gtaojbntcl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtslpzeghf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gtkjaulhuk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gtltvmbjeh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtzrihhciv.html

[D26] 数组转字符串
来源：http://dali.yongpay.top/Article/details/gttzrarnrx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsopqzqdq.html

PHP:  implode(", ", $arr);
来源：http://dali.daxiang520.top/Article/details/gteizhhbcz.html

JS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtsdmlekly.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtlpyhysin.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtbuwxnknt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gtjntxejyw.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtuvmfqkyx.html

C#:   string.Join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gtkwytnqsa.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtcvykzddw.html

E. 字符串处理
来源：http://dali.yuxming.cn/Article/details/gtxvykpvgq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtokjxohmx.html

[E01] 拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtldswaevk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gtxmzgaqad.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tian-w.cn/Article/details/gtzoskbbxk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtunpdfnnz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtkfgmgsad.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gtufvjxldb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gotoacloud.top/Article/details/gtgyakfaho.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tian-w.cn/Article/details/gtaudwalsp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtvntkuzxl.html

[E02] 重复字符串
来源：http://dali.ehwqpu.com/Article/details/gtsgieygoo.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtegfkxuyu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daxiang520.top/Article/details/gtrzffsfxr.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtirxnymau.html

TS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtmvqorwex.html

Java: "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtqenxnnah.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gthyaqusfe.html

Ruby: "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtphikbrfa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gtqiwmdgww.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtcotvioyt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gtsvegisnb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gthtmlebwd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtnfkxagez.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtfcbompsp.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtcxrlqtkr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtdnchnslg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigufen.top/Article/details/gtpghxzwgp.html

C#:   s.Substring(1, 3)
来源：http://dali.ehwqpu.com/Article/details/gtkybfoqsh.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gtbnoydlnk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgajivwl.html

PHP:  strpos($s, "x");
来源：http://dali.daxiang520.top/Article/details/gtbtiwmili.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.havefunace.top/Article/details/gthzkgtdol.html

TS:   s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtonvidqxi.html

Java: s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gthngvscda.html

Go:   strings.Index(s, "x")
来源：http://dali.yj202588.top/Article/details/gtuuwmjpvb.html

Ruby: s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtnctyvves.html

C#:   s.IndexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtojixdupx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.vqdsnc.cn/Article/details/gtarobjjnu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnqzz.top/Article/details/gtnaqvhoco.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.meibo888.top/Article/details/gtrzaegwyd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtfnwbdexr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gtuvvxnwif.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtfkkteigo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yanxiufei.cn/Article/details/gtrgwyzrfw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gtmwnuzpoh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtgkxbrfbd.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gtgbhjkuvk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtxshppfgs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gtbvvbtnmj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtoipuqkee.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtdsxlapbi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtkhafkvni.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtulmmmerd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyumlezs.html

C#:   s.Replace("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtpmbmujvs.html

[E07] 按分隔符拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtmqfdvvkc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ybcxt.top/Article/details/gtgdfapgwi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtsuarnnll.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.svipenyu.cn/Article/details/gtnmqbrdix.html

TS:   s.split(",")
来源：http://dali.daxiang520.top/Article/details/gturqhaibg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gtkxerjdns.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cqqwz.cn/Article/details/gtixtqcdyo.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gtlguadhzq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ehwqpu.com/Article/details/gttyivaypi.html

[E08] 数组按分隔符合并
来源：http://dali.c1oappe.top/Article/details/gtrsikhhtx.html

Py:   ",".join(items)
来源：http://dali.c1oappe.top/Article/details/gttdplpndc.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gtxnvvysge.html

JS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtdevxezwu.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtgjoqrshf.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gtjenaqeqn.html

Go:   strings.Join(items, ",")
来源：http://dali.xziqi.cn/Article/details/gtydbwadqi.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtaaqdgdhx.html

C#:   string.Join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtegrijwrj.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gtwrfzwbzc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gtmebqirgp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtjqbvdjxu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtkucnrebk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtdatuxlmg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtsbzfqdyu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cdnleiting.top/Article/details/gtmxwzgkfy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gtzckxoqtp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtnlwbexti.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gtgxplffsv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzmykral.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgfzy.top/Article/details/gtuljfrecq.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtphgzbybc.html

TS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtetcbffbe.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gttlwzshjn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtddrxidgw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtbndvrosc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gtmupmrppr.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gtbodoypew.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gtxbbhmgwp.html

PHP:  strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtsrpqmcvx.html

JS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtdylpsmfc.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtwnldsuit.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gtjhikwflq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fengsongda.top/Article/details/gtyecnxxml.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtyrxzrseg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gtgvmopkan.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gtechtsbhf.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtsvhcecnt.html

PHP:  substr_count($s, "a");
来源：http://dali.smart0.xyz/Article/details/gtakwkamfh.html

JS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtdvabwmzz.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtizrusrwy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gtifusfwis.html

Go:   strings.Count(s, "a")
来源：http://dali.hywenlv.cn/Article/details/gtiexkwtft.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtlsvhdgyy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gtwijamwxz.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gtzbikgunv.html

Py:   for ch in s: print(ch)
来源：http://dali.ydzc1.top/Article/details/gtwsllohfg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigfzy.top/Article/details/gtjlmxcbxa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtlfgtfcpa.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gtnxeniira.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtthyhvysy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gtefklsdxk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gtmbxigjxw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gtxlrsdmme.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gtyqibchyo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gtkehpjjnj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj202588.top/Article/details/gtdverlcvh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.quarkkingdee.top/Article/details/gtlxezpqew.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gtawrftfhr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gtfsqyffdo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gtxaxjasfl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gtazvqoixu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gteqrkjtmj.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gtusucplex.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gtafsbtbpf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtmsappoyp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gtazwjdabb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dianchejie.cn/Article/details/gtccmlzjuo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gtwzgunqdu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zycfv.cn/Article/details/gtkuoktrqx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gthdutwkxy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gtebxvedoo.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtxqfajqda.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gtkgqwgxlm.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gtmstcbmck.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtcwxrzsqe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtnregnlna.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtcylgomuh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenzaomai.com/Article/details/gtndkevtqb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gtpbiuwpkx.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeitlkaw.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gtlakrlfcb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhixingplan.top/Article/details/gtcgchfuut.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ehwqpu.com/Article/details/gtrwmpvnqm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtuebjjomk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gtempofyrz.html


<!-- 参考信息 -->