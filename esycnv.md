代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtoixorpgi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgfzy.top/Article/details/gtagqjrwlj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhiwuduotai.top/Article/details/gtvjqiewrh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuxming.cn/Article/details/gtdnmblbtu.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gtsuqtdnli.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gtbizsxwqp.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gtylrldepx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgufenzy.top/Article/details/gtytahabsy.html

TS:   [...arr].reverse();
来源：http://dali.jianghu66.top/Article/details/gtrxsvhfmk.html

Java: Collections.reverse(list);
来源：http://dali.cucudq.cn/Article/details/gtpdthxyle.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gtirsuwgfr.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtimkbneaf.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsgnjsbk.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gtuosekbxs.html

Py:   arr.index(x);  x in arr
来源：http://dali.guannengcc.top/Article/details/gtiunruuyq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gttzkelxii.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtwneqpduc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtfkmegizb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pengpengdd.cyou/Article/details/gtpnfyzrki.html

Go:   slices.Index(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtyicfyvme.html

Ruby: arr.index(x)
来源：http://dali.jqgufenzy.top/Article/details/gtjsnepzgv.html

C#:   list.IndexOf(x);
来源：http://dali.jlsjyb.cn/Article/details/gtxbmyzauj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gtxwfrptqe.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtziqcuoai.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hysaishi.cn/Article/details/gtibgozhoo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtgibqocoz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gtycfkkqpu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gthuwvavco.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuanzx.com/Article/details/gtugvigyzd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj202588.top/Article/details/gthvvbxkkm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtvkzzmdsd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dashuyun.cn/Article/details/gtczmalubv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtskovdxoo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hfpthk.cn/Article/details/gtgbgnzdjy.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtqwixkzxn.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtnoxpqfom.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gtztkhmiwh.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtyfbcgubz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtetwgckgd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gtakasxaon.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gthsfkvirb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtobrzrgoy.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gtldqfmlxn.html

JS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtqfdyibyw.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtgtdbvpeb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hongshengwenyu.top/Article/details/gtioziatnv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cheryme.top/Article/details/gtxchdkslw.html

Ruby: arr.uniq
来源：http://dali.tianlin.xyz/Article/details/gthrplbpcy.html

C#:   list.Distinct().ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnpuwmae.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gtopfpefoc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fengsongda.top/Article/details/gtergktcry.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gtxigclmnr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gttmzqivot.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtzsmwqspq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gthroegnpe.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gtxamnstok.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gtnrtofuko.html

C#:   list.Sum();  list.Average()
来源：http://dali.daria6918.cn/Article/details/gtkyypmldn.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gtjtvueyay.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtwxxflrth.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gtaqakbenq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gtcbmxkycv.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gthqkbgkqq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gotoacloud.top/Article/details/gtercntuyy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtsqhyjenk.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gtbatsupvl.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigufen.top/Article/details/gtgillmryg.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gtqcsveveg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ybcxt.top/Article/details/gtdvdonmii.html

PHP:  array_merge(...$nested);
来源：http://dali.yonumen.top/Article/details/gtclezyzdf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.kuanghao11.cn/Article/details/gtdiihzbnf.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gtattmdfuj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfzltrxe.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtzfnhqhmj.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gtwllsfput.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gthcqpszcm.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gtkbfqndeo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hfpthk.cn/Article/details/gtsewrhkna.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gtryayezgf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gtyhzmhbcc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gtztebazdr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aizwys.cn/Article/details/gtdejevpnc.html

Go:   // 手写 map[string][]T
来源：http://dali.yj202588.top/Article/details/gtztogmclz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gtawkklfjm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gtxjngbtnz.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gtecoxgvio.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gtpzplhuyw.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigufen.top/Article/details/gtakqyyclx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtayigusfp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtruzooaob.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fzhhl.top/Article/details/gtyjytgmig.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmykkakac.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gtmczxehnp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sufxvd.cn/Article/details/gtdoffilra.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gtfhfqforb.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwhadnox.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmehexnsd.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtyvuqwarb.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtgltqnrgz.html

Java: list.contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtmzupibsn.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtsrtxzord.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtrksplddv.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gtzrwvupey.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtryeygbqt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gotoacloud.top/Article/details/gtqkqbacve.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzfpcbjn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gtmgclejna.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gtanpylanf.html

Java: new ArrayList<>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtgprsdtja.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtbbpnyerh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gthktjtvvk.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gtugxldtym.html

[D23] reduce 累积计算
来源：http://dali.svipenyu.cn/Article/details/gtnbxsnhyw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtsrqpcpwv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gtsrykqlrx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gttihdzagq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtsqltnjrw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gtyspgdqwd.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtozkktqdr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gttwyhuatb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gtdljxwuvq.html

[D24] 字典 / Map 基本操作
来源：http://dali.hywenlv.cn/Article/details/gtbyioqjfr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jiagoushi.top/Article/details/gttiagsqus.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gtelksbrjb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258888.top/Article/details/gtoxuimawr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskdlwlma.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gtddyihuwd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gttpypqafj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkitalxs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypmfeqoj.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gtieqygduu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.svipenyu.cn/Article/details/gtcgsamxyk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gogol.net.cn/Article/details/gtmdakibcp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gtehcqflcb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dianchejie.cn/Article/details/gtkzlxqpof.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gtnmbraemd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gtewdhrgvd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxuanxn.top/Article/details/gtyfscsakt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtuvkmmekr.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gtqecrnvos.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gtrkgzdxqv.html

PHP:  implode(", ", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtszgtahzj.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtmnsmvfoj.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvydoccj.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtlhdkicbu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gotoacloud.top/Article/details/gtwrijpozr.html

Ruby: arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzenfpryg.html

C#:   string.Join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtssqfnlbt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtslnrjjla.html

E. 字符串处理
来源：http://dali.svipenyu.cn/Article/details/gtpmmcphrb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbcipvplp.html

[E01] 拼接字符串
来源：http://dali.tanke756.top/Article/details/gtdvnaqztl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gtmituoqps.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtodhmdnzm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gthshzdcrq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtbbturzjt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gtagrxnpze.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtnezijuda.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.bjfxy.top/Article/details/gtmfdednai.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtxrturliy.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gtuxnsopfw.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gtywyohiom.html

PHP:  str_repeat("ab", 3);
来源：http://dali.316326.xyz/Article/details/gtntnvhftg.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtwhtbnbtx.html

TS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtcnqvgfkm.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtczvgarck.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gtyzyiykgz.html

Ruby: "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtwokkwqow.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj202588.top/Article/details/gtsrwtbprk.html

[E03] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtzxosrzvb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gtuboeuhqv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtniixzlfg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gteiovwfrs.html

TS:   s.slice(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtafpqhygi.html

Java: s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtjdrhelia.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gtptccdlkz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gtldicvvro.html

C#:   s.Substring(1, 3)
来源：http://dali.shzxlz.cn/Article/details/gtnazxcqor.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gtshswreym.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gthmktsooa.html

PHP:  strpos($s, "x");
来源：http://dali.jyoumei.cn/Article/details/gtvkqgdqrf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gtqzrjftex.html

TS:   s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtpsdcufsq.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gthcvgnifc.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gtjydigwcm.html

Ruby: s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtwurdjplt.html

C#:   s.IndexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtzcttfhnr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.c1oappe.top/Article/details/gtdyyxpwlp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtkrwofcvu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.svipenyu.cn/Article/details/gtjvmnbkfe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtkulritcm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gtvutmdnmw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gttndwtjcl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jianghu66.top/Article/details/gtjqpzvziy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hfpthk.cn/Article/details/gtvbbdennq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtprzwbvsl.html

[E06] 替换子串
来源：http://dali.mhx1999.top/Article/details/gtyiwxusce.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gttojsotvn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.snrcjt.cn/Article/details/gtufwkgdqr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtonmkzsjh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtxttuzkgq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtwasajkmx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtfxyxrhgb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtemoawiwu.html

C#:   s.Replace("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtziyxmlmh.html

[E07] 按分隔符拆分
来源：http://dali.jinqigufen.top/Article/details/gtvpefgjka.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhiwuduotai.top/Article/details/gtbfxlznux.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtyrprmnrl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.quarkkingdee.top/Article/details/gtvvnfmbwm.html

TS:   s.split(",")
来源：http://dali.cqqwz.cn/Article/details/gtgmbyhpri.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvpomczw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmhcqjqn.html

Ruby: s.split(",");  s.split
来源：http://dali.tanke756.top/Article/details/gtalajxpfs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pengpengdd.cyou/Article/details/gtiffukztd.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gtowkslqbp.html

Py:   ",".join(items)
来源：http://dali.zdqjudy.top/Article/details/gtwemegpyd.html

PHP:  implode(",", $items);
来源：http://dali.sxryk.cn/Article/details/gtiqmbtxxx.html

JS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtqybfcmvf.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gthufwxygr.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gtghjztnkr.html

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gtmwarjcsf.html

Ruby: items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtetgudfao.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwlaybdb.html

[E09] 去除所有空白字符
来源：http://dali.iojbl.cn/Article/details/gtxywpeofz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gtirxmhfox.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yonumen.top/Article/details/gtyqwabjfm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtuzqqjfgz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtcinetwgt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gtwznkflyr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gtlxvlmsib.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xylfe.cn/Article/details/gtosbhttij.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gtbqsjfygl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gtsnfwxqax.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtqjsqskyb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gtijibtgds.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtlyfzumqq.html

TS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtfgzzmybs.html

Java: String.format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtywniwakp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtnbxsuzav.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtmjiayqqm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gtjuhlcdek.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdnbhonz.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtyhmfgulb.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gtdnwpdnti.html

JS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtjyriwmxn.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtdwcmgrfr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gtjxeumoli.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gteaaksrsv.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gthfvssbzr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtrfsdvgcf.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkeuwjwk.html

Py:   s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gtiwdtypka.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gtzijnqhri.html

JS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtulimtfbb.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtyfitnxbh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gtbengigcg.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gtmrhobmjc.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnzeztuh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxinkj.top/Article/details/gtywxqfsek.html

[E13] 逐字符遍历
来源：http://dali.gaohongyu789.top/Article/details/gtwsvbmedv.html

Py:   for ch in s: print(ch)
来源：http://dali.xuanzx.com/Article/details/gtvabosqwj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaxthcrx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtgkwntoqj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtxzyyjpqq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtukbyhyke.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.quarkkingdee.top/Article/details/gtboatgpvz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.snrcjt.cn/Article/details/gtlllstomg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gtjpupakyz.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtbqqsqran.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zycfv.cn/Article/details/gtugbyjtmr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hywenlv.cn/Article/details/gtoqqvqrpg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gtaiclzbpw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gtevcuugme.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduetgbhu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gtgormbmex.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtaasiusok.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.havefunace.top/Article/details/gtmccycwxw.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258888.top/Article/details/gtgxryacxa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtnhfgxgyc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gtspaheygu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gtseaeshwj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gtxudsaurh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhoulong.xyz/Article/details/gtuizyfqjs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtylvqnbrt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpfqqrmk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.0kj1m.cn/Article/details/gtfcjxguho.html

[E16] 数字千分位
来源：http://dali.shuidangran.top/Article/details/gtbpyszind.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gtdghutrer.html

PHP:  number_format(1234567);
来源：http://dali.chenjidiqi.icu/Article/details/gtbyvqmgub.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gttpiwvbnv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtpiopsxzq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtinuyrfvp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gtncvvwhfp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gtoartpizb.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gtcvxmitgn.html

[E17] 首字母大写
来源：http://dali.aibaodan.cn/Article/details/gtyfdllpkl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtnpcokcmr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gtsvzbcnvf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtufytzqoc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtladigukm.html


<!-- 参考信息 -->