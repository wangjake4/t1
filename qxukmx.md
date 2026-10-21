代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtgpamvpry.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtikadrrfp.html

C#:   list.Sort();
来源：http://dali.chenlongwang.top/Article/details/gtmyedvufg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guannengcc.top/Article/details/gtcnnincln.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gtyexlmkoy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gthvmxxmgj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtevvlfaqa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gturdzzzkx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gtdvkdjovd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtvuopgxhy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gtxzsmxfaj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gtxmrimpam.html

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gtzwyerjcl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnxiangtu.top/Article/details/gthhgqfvly.html

PHP:  array_reverse($arr);
来源：http://dali.tanke756.top/Article/details/gtlheksrue.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyvczbdd.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gtzfwakpex.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gtlmtpbgkt.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gtcfzlvxdg.html

Ruby: arr.reverse
来源：http://dali.gogol.net.cn/Article/details/gtrdzzgozv.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtqibzguje.html

[D12] 查找元素下标
来源：http://dali.shangyingyoupin.top/Article/details/gtfsmszulf.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtujtamldw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sxryk.cn/Article/details/gtivkroljg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtrdlcrmgk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gtceeouach.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guannengcc.top/Article/details/gtngpzoiqu.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtwhtrzosw.html

Ruby: arr.index(x)
来源：http://dali.zhongyouzk.top/Article/details/gtrajpgjtd.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gteeqtokvu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gtjdipjmdx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gtadfudxtr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dianchejie.cn/Article/details/gtfkeslour.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtxnqdefax.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gttwxmlmdb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guowangkeji.top/Article/details/gthphplwpy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtnannripm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shuidangran.top/Article/details/gthokiqhpu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gzhubu.top/Article/details/gtxijulnui.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhixingplan.top/Article/details/gtnxfognky.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhengqikj.top/Article/details/gttbadanpw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtbmlaqred.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtekheeecf.html

TS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtrdtftalk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigufen.top/Article/details/gtwgfteymc.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gtljzjzpac.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtsbykcwot.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtcqrhokcd.html

[D15] 去重
来源：http://dali.zhengqikj.top/Article/details/gtmevbudlc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtlvmgwxwy.html

PHP:  array_unique($arr);
来源：http://dali.cdnleiting.top/Article/details/gtwkejzhiv.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtnfbfkrsq.html

TS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtmvbzpsjw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gtdadyyboe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gtaxyuhktw.html

Ruby: arr.uniq
来源：http://dali.zycfv.cn/Article/details/gtykmalyot.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtkzfimeyg.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gtuwxzhgym.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guannengcc.top/Article/details/gtmlqnceox.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gtqdcqxqwu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gtciinvfpa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtlfbxmmmx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gtjpqufosw.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gtuhnvhstz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gtxrexjxfg.html

C#:   list.Sum();  list.Average()
来源：http://dali.haohaochexian.top/Article/details/gtbltvtqjy.html

[D17] 最大值与最小值
来源：http://dali.jianghu66.top/Article/details/gtazzikcvh.html

Py:   max(arr);  min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopzkvbqg.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtestrvsyc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gtkjdcbrol.html

TS:   Math.max(...arr);
来源：http://dali.fengsongda.top/Article/details/gtqndrlrnx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gotoacloud.top/Article/details/gtuwsnlpmk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtmjphjlda.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxinkj.top/Article/details/gteqnnfhzr.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gtoebrlhvs.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gtqxpazzer.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangdashe.top/Article/details/gtagesvrsw.html

PHP:  array_merge(...$nested);
来源：http://dali.svipenyu.cn/Article/details/gtjiqppvwz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gotoacloud.top/Article/details/gtvrevfvyy.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gtgkrhkthb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtcvyzwlcm.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gtuykhrapc.html

Ruby: nested.flatten
来源：http://dali.chenzaomai.com/Article/details/gtvbvzokrx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtzdscwrnr.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gtpbsklrfo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gtpawvedfc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gteqjwlepx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gtjtdvrchf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiypacfsg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gtwfldvfyr.html

Go:   // 手写 map[string][]T
来源：http://dali.ehwqpu.com/Article/details/gtjvtsxzep.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gtlsevibzh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.havefunace.top/Article/details/gtbibaeucf.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigufen.top/Article/details/gtfludwrdv.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gtzcslwuwg.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtcgukojkr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtbxocgcrg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtxswzekbk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gtxylwbmaq.html

Go:   // 手写 map[T]int
来源：http://dali.guannengcc.top/Article/details/gtjpjmkear.html

Ruby: arr.tally
来源：http://dali.daria6918.cn/Article/details/gteunipjbj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jiagoushi.top/Article/details/gtqiymqeid.html

[D21] 判断是否包含某元素
来源：http://dali.snrcjt.cn/Article/details/gtcrduqmtb.html

Py:   x in arr
来源：http://dali.hysaishi.cn/Article/details/gtnwplhypd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtmjqaantw.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtcqysaalr.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtehmuians.html

Java: list.contains(x)
来源：http://dali.sweek.top/Article/details/gtnevlwgik.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtesxlwjxz.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtphulgoxv.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtoletytrk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gtiipfxwqt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gtlxtlzsoz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gtxjoafocv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gtjxcafnsj.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjcbzeda.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gtgwkjdyst.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtleerxxky.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gtfofqqgwl.html

C#:   new List<int>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtxmuzkvdz.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gtvhzbhnko.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.havefunace.top/Article/details/gtovvuvauf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guowangkeji.top/Article/details/gtjlndfqki.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtmxydpudz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtmwvihmal.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gtdsjfafgi.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtzhqbfucs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gthzmqnwrn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gtsxbjwwvt.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gtouzrrjeu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhongyouzk.top/Article/details/gtdnlasgqe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjtgxcor.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cashguo.top/Article/details/gtcjhgafjn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtmjktwitg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258.top/Article/details/gtdawmfbie.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guannengcc.top/Article/details/gtenbmmrzk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cheryme.top/Article/details/gtogwvplut.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gtytstsfnp.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gtznklqeaj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtiiboabwk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ybcxt.top/Article/details/gtczazpget.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gtceurdsdt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gtafleapnf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtvrajyyqm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gtuhsohqvf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ehwqpu.com/Article/details/gtoyzeomol.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtbxuswajs.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gtvyrcivwe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hysaishi.cn/Article/details/gtiwvckhcw.html

PHP:  implode(", ", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtfeavlpzi.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtpezhrgbv.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtsjzalixt.html

Java: String.join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtqtaqonxz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gtthykgevw.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtykovwyvy.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtithscuea.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtdykxeees.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gtrjhkufke.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gthgxibtbh.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtwvjheqtf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.c1oappe.top/Article/details/gteizhfdbx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gtsotyreae.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtkklpvvuz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtfdgszolf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gtqztipjmv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtxwzvmzye.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gzhubu.top/Article/details/gtcuwpdyad.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtwubbqtal.html

[E02] 重复字符串
来源：http://dali.hnxiangtu.top/Article/details/gtczpzzpam.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtpmgdgnaw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fzhhl.top/Article/details/gtaugcicap.html

JS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtwnrhwrcg.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtdbsaamwc.html

Java: "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtskqyyndi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xylfe.cn/Article/details/gtqdhcorxf.html

Ruby: "ab" * 3
来源：http://dali.sweek.top/Article/details/gtisecfehc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gtzpqkvoep.html

[E03] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtzqjybgbk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnxiangtu.top/Article/details/gtsxdrvpdv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtfgxmgxwl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gteywrmhsj.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtcmkoajeo.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtqtnjntmr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yongpay.top/Article/details/gtocpnuiue.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gtodaetylh.html

C#:   s.Substring(1, 3)
来源：http://dali.316326.xyz/Article/details/gtzoardyic.html

[E04] 查找子串位置
来源：http://dali.jinqigufen.top/Article/details/gtzkdnsbou.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhbasppm.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gtxsgupipr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gtrthjxngg.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtwsilsyno.html

Java: s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtvmuosyrb.html

Go:   strings.Index(s, "x")
来源：http://dali.zhoulong.xyz/Article/details/gtvgkrwoag.html

Ruby: s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gtlrncgqay.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtlbawfyhn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shuidangran.top/Article/details/gtlujczqjj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sufxvd.cn/Article/details/gtuteydaba.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gtmncjbbkk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtktoptbgh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gtmtlpxnzl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrnfrfzv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jlsjyb.cn/Article/details/gtojntbqgr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gtcqmvfwzb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtulfwstvv.html

[E06] 替换子串
来源：http://dali.hywenlv.cn/Article/details/gtbvrsnxcv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtxpsyeovy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gttwbcsjmj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtqwqanmfa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmwqsgba.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtdnvdpfjj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gtoqbngtnp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gtqohrsikl.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gtklmfjata.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiablddcm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gotoacloud.top/Article/details/gtcxasfqoi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.iojbl.cn/Article/details/gtuofqdtdi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gtyyfvnbus.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gtqosfitxy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258888.top/Article/details/gtlmmeuyri.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtqsqysjgf.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gtytogvvru.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gtcegokprp.html

[E08] 数组按分隔符合并
来源：http://dali.zdqjudy.top/Article/details/gtkzdslikl.html

Py:   ",".join(items)
来源：http://dali.yuxming.cn/Article/details/gteplcptxm.html

PHP:  implode(",", $items);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjadfylre.html

JS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtdbmhwnnu.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gttvhzpjgj.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtxeovhymn.html

Go:   strings.Join(items, ",")
来源：http://dali.meibo888.top/Article/details/gtnmbbqgvc.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gtsnnvnxeb.html

C#:   string.Join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gtevgqzznv.html

[E09] 去除所有空白字符
来源：http://dali.andypj.xyz/Article/details/gtrosbuzwt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnqzz.top/Article/details/gtydqndfky.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fzhhl.top/Article/details/gtmezhwkbd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gtsmczdike.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtcqfvyykj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gtmilwmbce.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daxiang520.top/Article/details/gtrolsnagl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gtiajymrmq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gteveueqzr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gthcdnpiva.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkgjtvqr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.kuanghao11.cn/Article/details/gtfuypcplm.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtyccmryoj.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtbjyqbrwv.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrwwjqls.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtwoolhnhe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gturatkaja.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pengpengdd.cyou/Article/details/gtysdubcak.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gtyxomrhyt.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtajamwumg.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gttoxjljmm.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtvbtpjqjt.html

TS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtkwtexkhs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gtwknbvjvd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtogxpszja.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gtkaqbybzq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtlreqgxyt.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gtdgbugijy.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtpmgatvwn.html

PHP:  substr_count($s, "a");
来源：http://dali.svipenyu.cn/Article/details/gtcqmywuhw.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtefbryxmx.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtuudbrgsk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangdashe.top/Article/details/gtmcbboqus.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gtlgahfrgc.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxuxisux.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cheryme.top/Article/details/gtwsyewavs.html

[E13] 逐字符遍历
来源：http://dali.jinqigfzy.top/Article/details/gtxwstspfl.html

Py:   for ch in s: print(ch)
来源：http://dali.hongshengwenyu.top/Article/details/gtdhqtzwyj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtofxnitvv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtlssgkcmk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtcxxzkpfb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gthqponzam.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gtzflgovcl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gtgswxfyzu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtnmoxaitn.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gtuhoaolzu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.iojbl.cn/Article/details/gtktbdealx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtzlkbwgfy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shzxlz.cn/Article/details/gtppmslybq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtknjqiecy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtbsmfeszz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tian-w.cn/Article/details/gtnpckdlxx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gtjcudormk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtozbnyulj.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gtjiwqjjvj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gtyjjpique.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gtwaldfvra.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ehwqpu.com/Article/details/gtrtrpzxtp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gtjobaitgw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xinyue.icu/Article/details/gtotowxzur.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtkidekvoc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shzxlz.cn/Article/details/gtzmobijph.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtempjxecf.html

[E16] 数字千分位
来源：http://dali.svipenyu.cn/Article/details/gtqahouqzp.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gtitjrrgnm.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthururynh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtgyocuaat.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtllvywbvu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtfpnzbwxk.html


<!-- 参考信息 -->