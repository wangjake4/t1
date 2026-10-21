代发 wailian999

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gtvqprprjz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhiwuduotai.top/Article/details/gthocpazei.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gtytqrcneb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gtqryvtfex.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtrymlpkuq.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtmrwxsyok.html

C#:   list.Sort();
来源：http://dali.cqqwz.cn/Article/details/gtwzpllkdt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gtaaxvdirs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gtjqdahqfe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gtnzuqwcuc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtygefzfqe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gtsdcrduls.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cashguo.top/Article/details/gtprchjspx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gtcymqtfwi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gtlyjhqqta.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangdashe.top/Article/details/gtbcpandko.html

[D11] 反转数组
来源：http://dali.hysaishi.cn/Article/details/gtddwmlzym.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daxiang520.top/Article/details/gtsjeuydsx.html

PHP:  array_reverse($arr);
来源：http://dali.tanke756.top/Article/details/gtpmbnykli.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.vqdsnc.cn/Article/details/gtzxpasarf.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gtsdxmfxgy.html

Java: Collections.reverse(list);
来源：http://dali.xziqi.cn/Article/details/gtbctgitfe.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpafaflaf.html

Ruby: arr.reverse
来源：http://dali.ydzc1.top/Article/details/gtkkddxxfg.html

C#:   list.Reverse();
来源：http://dali.zycfv.cn/Article/details/gtzmjuxnyg.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gtrphesjac.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxinkj.top/Article/details/gtlibcxowo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gthexipzcx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtxdmlzmdr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtfcgtrbql.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gtbejocsxc.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtbpaliewy.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gtadtfloqg.html

C#:   list.IndexOf(x);
来源：http://dali.sweek.top/Article/details/gthrsinwnk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gtyyqutitb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shzxlz.cn/Article/details/gtnjwbufny.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sweek.top/Article/details/gtosuwzmlb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gtukswuurq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzewlejff.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtdvqkrbwz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gtiwrdqedm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gtajkklxuf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtzhyizkzo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgfzy.top/Article/details/gtivqfkcgq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gtlqxudpsq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtkxcrsjwm.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtwhkxbags.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtufbfevlx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuanzhike.top/Article/details/gtdvfzdjuk.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtlqbahnmk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tanke756.top/Article/details/gtscxitgrt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.mhx1999.top/Article/details/gtxqdmmloz.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuvzuugh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gttrmcnzqp.html

PHP:  array_unique($arr);
来源：http://dali.yj202588.top/Article/details/gtveohlkcr.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtmvuldncg.html

TS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtdrwnxlmh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cheryme.top/Article/details/gtaaxpvtjw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.birdmap.top/Article/details/gtpmlxljrk.html

Ruby: arr.uniq
来源：http://dali.zhengqikj.top/Article/details/gtcuxrkzec.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gtzmtzlblx.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gtzzuahogs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ybcxt.top/Article/details/gtmmrzyqiw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.smart0.xyz/Article/details/gtazaawsrn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gteibesdga.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtkjipkflm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gtafjftzxm.html

Go:   // 手写循环累加
来源：http://dali.hammf.cn/Article/details/gtgxpekvpu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtqbnkmhnu.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gtwqkzwmia.html

[D17] 最大值与最小值
来源：http://dali.xuetiantiany.cn/Article/details/gttlzykzyy.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gttjfcqoun.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtpqcksdvh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gtmrhvkoeo.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gtopqozyzl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gtyjcjbheo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sxryk.cn/Article/details/gtdxyhfwvt.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gtkcyvwkad.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gtwwqeurql.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gtvfhfytbs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtrpdugvqk.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqnfonxd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zycfv.cn/Article/details/gtnplbhvwk.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gtswmstmwa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258.top/Article/details/gtnttaxqoc.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gtpdtdfexp.html

Ruby: nested.flatten
来源：http://dali.chenlongwang.top/Article/details/gtdthragno.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gtwduxpcey.html

[D19] 按字段分组
来源：http://dali.xziqi.cn/Article/details/gtzkormjse.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gttaqhedfk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gtwjewzwdm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cucudq.cn/Article/details/gtiigyfkcy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gtkkwoyvsi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shzxlz.cn/Article/details/gtrzwieijh.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtpjviclpg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gthcvuuoqx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jyoumei.cn/Article/details/gtnejrtoly.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gtbabvbuoc.html

Py:   Counter(arr)
来源：http://dali.sweek.top/Article/details/gtyvsdskaw.html

PHP:  array_count_values($arr);
来源：http://dali.dianchejie.cn/Article/details/gtobjsxdha.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtugyaupeh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtwqskqwfu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cheryme.top/Article/details/gtaawucdhg.html

Go:   // 手写 map[T]int
来源：http://dali.zycfv.cn/Article/details/gtjbtizibh.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gtxzdvcawc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ppjwa.cn/Article/details/gtadshwhlz.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gtojqxkuqz.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gtrfhvrdom.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gtuzlpzssa.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtawvbnygx.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtsbjoehuk.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtguftcfxq.html

Go:   slices.Contains(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtgyknbpht.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtpytuhunz.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtufmlsrss.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gtzgtkgfgl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gtofiwzcfk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cdnleiting.top/Article/details/gtwdrucmax.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gtxvyzznjf.html

TS:   [...arr];
来源：http://dali.jinqigufen.top/Article/details/gtgunlbltw.html

Java: new ArrayList<>(list);
来源：http://dali.dashuyun.cn/Article/details/gtgpjcgjbi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtncqdwgjh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gtazmagqoe.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gtqsdzeirj.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gtvciqwwql.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pycfn.com/Article/details/gtvulcaasb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aibaodan.cn/Article/details/gtdhybtarw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtvxtpqmaf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtfgzpxypo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gtgaqwjhou.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtglhgtsdn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gtljhhmmqo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gtvunuypzc.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gtubnczzfy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sweek.top/Article/details/gttxcbcwne.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gtxhqymufx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gtsxnbbslk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtfympbcyy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtnxmwjvzk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.c1oappe.top/Article/details/gtbhkjfxzk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gtqpvijwcq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nwbrower.top/Article/details/gtleohfici.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gtafedubxa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gtdelgvxev.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gtkuoaodia.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tanke756.top/Article/details/gtpslwlirm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnqzz.top/Article/details/gtdwginmsr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guannengcc.top/Article/details/gtxukebppl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.svipenyu.cn/Article/details/gtyafewagt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gtyqidjnsn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtthgamrlv.html

[D26] 数组转字符串
来源：http://dali.nanxinkj.top/Article/details/gtbkfzdngu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cucudq.cn/Article/details/gtfxrkavwa.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtmapnmzzd.html

JS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtjeyxsymx.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gthdtehsco.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gthnxwrffk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fengsongda.top/Article/details/gtddobmgtb.html

Ruby: arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtsifbptbq.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtsuedxzlm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwhteeirg.html

E. 字符串处理
来源：http://dali.ydzc1.top/Article/details/gtgayrxxlu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtarhkinon.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtlbapspwv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gtukhzflkv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsofzhbux.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtqjvlxaml.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtrenhjoir.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gtonehrjki.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gtlrcgqbyc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gtaqhinuev.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxanaqso.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gtdxvxuugn.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gtdqkryyeh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxinkj.top/Article/details/gtplncykoz.html

JS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtmioevhfq.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtjgntvaqa.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtmiazjrqu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.andypj.xyz/Article/details/gtpczoyyyp.html

Ruby: "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gtvdkwkviv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guowangkeji.top/Article/details/gtoqkkmhtx.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gthquusetc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gtkutyifxh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gttaqkntmv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtxlwthreh.html

TS:   s.slice(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtakaikfra.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtmknubpya.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtwgfeplju.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.quarkkingdee.top/Article/details/gtvopgudkj.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gtwduczdpx.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gtdyqcwwxk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtntwsracv.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gtnlalpogi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gtkibmtkmo.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtetrmsgux.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtqebgemqt.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtljzxzfkq.html

Ruby: s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gtrubjsrls.html

C#:   s.IndexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtsmnphqgm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gtblkgkmzf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtlspywzlx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.iojbl.cn/Article/details/gtkbclxpho.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtzzdiqdys.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tanke756.top/Article/details/gtwawnsqpm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtztnjvvjz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gtsugslxgp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gtcofzjphu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtlqiolkqm.html

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gtinnbddor.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtrxotmfgp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gtvbupgcsj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtkvxmqdiy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtpxkilqzz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gthepslplg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtwkswzqci.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtoberetbf.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtyhotzodr.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gtoklexgev.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtdxarffro.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtlxymtpht.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gtgysefnuc.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtneseizuw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gtxnmybyqo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gtssqzqzqp.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gttjdnqrkc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cdnleiting.top/Article/details/gtjcrujxod.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gtkvrsjkvp.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtwlnnqooe.html

PHP:  implode(",", $items);
来源：http://dali.andypj.xyz/Article/details/gtdopgxuwu.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gthgibvvmj.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtispitsww.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gtvkfswpah.html

Go:   strings.Join(items, ",")
来源：http://dali.tanke756.top/Article/details/gtithmeaqz.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtwckbmmzj.html

C#:   string.Join(",", items)
来源：http://dali.havefunace.top/Article/details/gtwuxdvwmc.html

[E09] 去除所有空白字符
来源：http://dali.dashuyun.cn/Article/details/gtbjkfxwkd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjtmrcqq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.mhx1999.top/Article/details/gtrtksxbsb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gtrfedtssz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gtwgnpeavx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtxpaqdujd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.c1oappe.top/Article/details/gtstebwxiy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gttyyxqnwu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtjjdrttsk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gtbltshmgx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtjcvsbskc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.snrcjt.cn/Article/details/gtdbdrmpzx.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtglmbzuac.html

TS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtpjwqmmff.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtcxlscovw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtaggaxtgd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtnpvlntsg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258.top/Article/details/gtfjopetxn.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gtllsxrhhy.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtkvqfoasu.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtktxqxixn.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gthnybxltx.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtarztvqev.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnqzz.top/Article/details/gtiabukkaz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtpnpqqayo.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtaeidbqoi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtckvhvsgk.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gtmoqnhpzm.html

Py:   s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtnoyxvdmz.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gtzcwdazzv.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtjgpvbshh.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtuvdhrixy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxuanxn.top/Article/details/gtuwikkpkk.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gtxcdbrplv.html

Ruby: s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gtyvqaazfd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gthdvcihdp.html

[E13] 逐字符遍历
来源：http://dali.jinqigufen.top/Article/details/gtwipvfbcq.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gtwuepbqsz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gtrhufvrlo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtyolbjpva.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtwjnerywj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gthjfyirun.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzyqybgc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jiagoushi.top/Article/details/gtiqlfgqjh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gtcrnrizfn.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtfolpowmn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gogol.net.cn/Article/details/gtmjzjuwtc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gtzmhkjyyc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gttyeefmfz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gtledvpjgp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtapuyyfxi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jyoumei.cn/Article/details/gtkhnqzbul.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxlkscds.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtgwdigupp.html

[E15] HTML 转义 / 反转义
来源：http://dali.xziqi.cn/Article/details/gtdxuvqqjn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gtztdwupon.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtxhyttbqm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gtpquarsmj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dashuyun.cn/Article/details/gtfyxcyxzu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtvotnzpkx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nwbrower.top/Article/details/gtrwcxtlpz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gtuxgqbgwb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtururqbfz.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtdnqmxxdf.html

Py:   f"{1234567:,}"
来源：http://dali.gaohongyu789.top/Article/details/gtfctrkdkb.html


<!-- 参考信息 -->