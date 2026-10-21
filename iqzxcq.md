代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtsxngiihf.html

Java: Collections.reverse(list);
来源：http://dali.jiagoushi.top/Article/details/gtltjrnrwr.html

Go:   slices.Reverse(arr)
来源：http://dali.ehwqpu.com/Article/details/gtoqwpenyl.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfonhirlp.html

C#:   list.Reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gterxbvoro.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gtzexzpydq.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gtcfpybpld.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gtbbaproan.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtroanidju.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtqnidpkrg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yanxiufei.cn/Article/details/gtseetxjqv.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfzbgkbx.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtqdmyvcaw.html

C#:   list.IndexOf(x);
来源：http://dali.iojbl.cn/Article/details/gtiddexgpz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xziqi.cn/Article/details/gtmihjueue.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gtdgksgrlb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gtlxpucwxf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtcdqnakoq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gthqxtwxzj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gtmdvrfusi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daria6918.cn/Article/details/gtgafosluc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cqqwz.cn/Article/details/gtkqwegpcj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtagwiuqym.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxuanxn.top/Article/details/gtvvxilter.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gtmwvkqdyr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtlrswbkgf.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtmmgaqjgt.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekttrfwl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sxryk.cn/Article/details/gtokkwnomi.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtwglpjwaa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtxxkvojzp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zycfv.cn/Article/details/gtutrgdbos.html

[D15] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtkgvodops.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gttrftbxav.html

PHP:  array_unique($arr);
来源：http://dali.guowangkeji.top/Article/details/gtlpedcnmz.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtuvrzapcu.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtzmggdrau.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sufxvd.cn/Article/details/gtkbpatilt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gtbenectmh.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgnwlpqx.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gtgprvqaas.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gtusbpvbbx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtrmhtzxzs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnqzz.top/Article/details/gtgcibftoc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtpradngpi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gtzgzwqeap.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cdnleiting.top/Article/details/gtkvukopuo.html

Go:   // 手写循环累加
来源：http://dali.cucudq.cn/Article/details/gtljyycsfd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gtooqybvkl.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtgwaqspte.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gtidckyzav.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtjrnlcwfw.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gtfisfrkml.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gtgkbzjxeo.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndbulznv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nwbrower.top/Article/details/gtsfadqjlu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtmbqsmzob.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gtkhhzffmk.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtikuxooyg.html

[D18] 扁平化嵌套数组
来源：http://dali.zhongyouzk.top/Article/details/gtweiefmfu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gtxgdtzqji.html

PHP:  array_merge(...$nested);
来源：http://dali.snrcjt.cn/Article/details/gtgowygbto.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yonumen.top/Article/details/gthclknmvq.html

TS:   nested.flat();
来源：http://dali.feifeiyinyue.top/Article/details/gtuicslwcu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gtjmdhtgkz.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gtpedqixkj.html

Ruby: nested.flatten
来源：http://dali.birdmap.top/Article/details/gtgxouljjo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gtctpbtgde.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gtrsssmbis.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gtnfmmkvhd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gtddhiyzuv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuanzhike.top/Article/details/gtbuktobfs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtzrxzrlqs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gtqwwsizkw.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gtetctlnnu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenlongwang.top/Article/details/gtpkspmfwl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gtjvtmfkjt.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gtcheugftx.html

Py:   Counter(arr)
来源：http://dali.iojbl.cn/Article/details/gttkrggkyh.html

PHP:  array_count_values($arr);
来源：http://dali.dianchejie.cn/Article/details/gtlzxhqljs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtolarqzck.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gthwlkigfz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.smart0.xyz/Article/details/gtskwumomm.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gtribgccmk.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gtuwlfmuot.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gtpdmxekcb.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gtaoroifkw.html

Py:   x in arr
来源：http://dali.iojbl.cn/Article/details/gtyvuswocn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gtibsbtkxx.html

JS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtvxohxpjr.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtottkggvj.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gtrfnurnto.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrslyrref.html

Ruby: arr.include?(x)
来源：http://dali.yuanzhike.top/Article/details/gteunhlqbf.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtfbighdry.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gtgwvxawee.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ivvv.top/Article/details/gtwcrbnmve.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhengqikj.top/Article/details/gtrwwizrgt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xylfe.cn/Article/details/gtftrcxnbb.html

TS:   [...arr];
来源：http://dali.yj20258888.top/Article/details/gtvknpyygs.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gtgsictpan.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoixdogzw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.vqdsnc.cn/Article/details/gtjttewbir.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbgdoasd.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gtdyfojcwi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslndawkx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gtlvjdnemp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gtgtvmubfz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtaxwlidmv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtyvbfyttr.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtvmpshpcq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvpnpnzc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gtpyqyvtfs.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gttprrdqmk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gtmldqywxs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gtlabtwwme.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gtkqtlfrkn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtiioojsnb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gthkntpbfv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gtrmqxgrzu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gtcrudwbqr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gtpftyuyoe.html

[D25] Set 集合去重与交并差
来源：http://dali.vqdsnc.cn/Article/details/gtzleudrzc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sufxvd.cn/Article/details/gtgybcyjtd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gtdwflvqfw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.andypj.xyz/Article/details/gtrmztuoez.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksjlfzlb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gtsietjfvb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gtlgnvqlun.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yongpay.top/Article/details/gtbotqbkvh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gtlashedmo.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gteeuapfbf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ppjwa.cn/Article/details/gtapnyuvzj.html

PHP:  implode(", ", $arr);
来源：http://dali.tian-w.cn/Article/details/gtkjghxptw.html

JS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtigiqqwik.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtquufaqsv.html

Java: String.join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gthxdjohkp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gtoixsoagv.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtskqgsuxe.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gtntitszkx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttvneqonr.html

E. 字符串处理
来源：http://dali.yvedp.cn/Article/details/gtmezhgogx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtoqrtlbeh.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtmnfsqydz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zycfv.cn/Article/details/gtadvitdaz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqjavxvb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqdohoxm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtjkhbwvug.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cashguo.top/Article/details/gtqttqahem.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gtkvqsiggx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtjffokbob.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtkdzrrbdu.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gthqcacrij.html

Py:   "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gthonxocgy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gttbbehsyu.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtnxrjibsg.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtokhekaxn.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtddonkltw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gttfnlexkc.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtspmpcwmw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuanzx.com/Article/details/gtizjhnqhc.html

[E03] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtdhdtxkdr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gtvpsoilji.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtkfrvraln.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtlavlvydt.html

TS:   s.slice(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtuqdjnuld.html

Java: s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtfwpctruo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gtjnczvjxr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtrdeisbcc.html

C#:   s.Substring(1, 3)
来源：http://dali.havefunace.top/Article/details/gtrlaiqfmt.html

[E04] 查找子串位置
来源：http://dali.zycfv.cn/Article/details/gtgeziuter.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtiwmnqugw.html

PHP:  strpos($s, "x");
来源：http://dali.svipenyu.cn/Article/details/gtzevhsheo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gtdzgleghv.html

TS:   s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtyhvozxsz.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtvwmbottd.html

Go:   strings.Index(s, "x")
来源：http://dali.xinyue.icu/Article/details/gtdgiyynfy.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gtgfgujgxa.html

C#:   s.IndexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtedizoujq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixopuwsv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gtzerlsguj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmhvtmxs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtfmlygqop.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gtjmfulhae.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtvrhdkqyh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gtziklldui.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gtlwfdemor.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtgoszbtbq.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gttxpqrbmn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gtsfgojskk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gtdenksgwa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtuseihqsh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtubjxhooy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtsljgaocj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtxkmwvohe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtjyjnrmra.html

C#:   s.Replace("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtlhswlquh.html

[E07] 按分隔符拆分
来源：http://dali.hfpthk.cn/Article/details/gtywyuwtjn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenlongwang.top/Article/details/gthugoljug.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtmvlsocfv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gthoycxopa.html

TS:   s.split(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojyaejgv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gtcxoollji.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhengqikj.top/Article/details/gtwjahbpwu.html

Ruby: s.split(",");  s.split
来源：http://dali.xuanzx.com/Article/details/gtbcjsgsep.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hfpthk.cn/Article/details/gtvzdxqoeu.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gtfyxuzskc.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gtgwjrtgky.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gthyggkygs.html

JS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtkhgnvqqk.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gtioutdhll.html

Java: String.join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtuywjeheg.html

Go:   strings.Join(items, ",")
来源：http://dali.ydzc1.top/Article/details/gtjcfdyikm.html

Ruby: items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtdaqrzdou.html

C#:   string.Join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtgcdqmfem.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gtaniklpwx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gtpwxmcyku.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gtpncrzqlr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtojxisiiy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtwetesvew.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtqmoqyzxx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guannengcc.top/Article/details/gtdnqpawzi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwnlpogq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtcootumnl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrzoqssd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gttaxbllyo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shuidangran.top/Article/details/gtzslwpqvq.html

JS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtyxmuleko.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtilzgfuso.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtfryziurs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfggcegkb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtgkfhuabv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gtousmrhbh.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gtgmqjqkxj.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtadkwevfz.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gttegybnqu.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtvepfzfop.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtrwaqdyzm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiwlemue.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shuidangran.top/Article/details/gtspsjzvrl.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtvkhtulxx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtvnrhopxk.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gtijlwcbmx.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtbqfhwsqz.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gttzlojmmu.html

JS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gthcghruzc.html

TS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwimerlq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gtipxuuljh.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsaknrwog.html

Ruby: s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gttoapuspn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gtfveliesx.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gtmyzscprd.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gtvuqsgnaw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gttdrwhqig.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtalawakmd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtbqsrbzno.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gtiakjxuli.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gtgfttrfiz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gtspggoocb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtfqssvpet.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gtinktcyox.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gtqjhwxcbb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ehwqpu.com/Article/details/gtpuxxzztk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gtafztilaz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtsdgxnnyp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtetvtdvka.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangdashe.top/Article/details/gthkhikrfk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tanke756.top/Article/details/gtpeulmcol.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtubzhlyff.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gtwimrnjie.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yangfankeji.com/Article/details/gtpcoaiwvf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gtpgqcdoma.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gthfwuxzwq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtjejhtiyd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sxryk.cn/Article/details/gtonvsjrgo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gtarpcpkmz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.bjfxy.top/Article/details/gtqvbmiytl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gtxtsojwqr.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtrldqoeia.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gttctleqzd.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gtneahdudm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtwngpcpmp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtpvrjctkw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guannengcc.top/Article/details/gtwkrmdtkj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gtknavsqvt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtuientaew.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gtinsqkffl.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gtnfzbaukz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gtzypontcp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gtwyzrkxrn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gtlyelinsu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gthvyhrfub.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pycfn.com/Article/details/gtufbhpaut.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuanzhike.top/Article/details/gtqpomngrg.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gtjuyhveuy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aizwys.cn/Article/details/gtbabwpkin.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gtisyiuxxb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gtkwblkvqe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tian-w.cn/Article/details/gthmvjxtxh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtmuikdmiw.html


<!-- 参考信息 -->