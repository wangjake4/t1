代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gtvneptqdy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gtkdyqprhy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gtzfljtifp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ybcxt.top/Article/details/gtturacloh.html

[D11] 反转数组
来源：http://dali.jlsjyb.cn/Article/details/gtlkhgbjnk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthoomggnr.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtzbjrweyq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aibaodan.cn/Article/details/gtjxhmlfde.html

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gtwmdknkby.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gtepqdjimt.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gtupdupukm.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gtjmivmltq.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gtniagrgqb.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gtcoiuerml.html

Py:   arr.index(x);  x in arr
来源：http://dali.shzxlz.cn/Article/details/gtlcsgvgpl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gtdgpfvtyd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtgntpntzp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gtprleogfq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yongpay.top/Article/details/gtpocpfxta.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmutpggfm.html

Ruby: arr.index(x)
来源：http://dali.tanke756.top/Article/details/gttrhhdghx.html

C#:   list.IndexOf(x);
来源：http://dali.shuidangran.top/Article/details/gtarvqnigk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gtzjlebwsx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gttzdgnbzm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gtvcfmmkni.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtxevpxyqy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtcuprgukv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sxryk.cn/Article/details/gtuvmlpcmh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj202588.top/Article/details/gtoxmpwykw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gtizfwncqw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyeqhlgjh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tanke756.top/Article/details/gtaqysoxmk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gtoeubaudg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnqzz.top/Article/details/gtxzyorwxu.html

JS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtjysxcsxf.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtignxlngc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gttpmtufhk.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtqzoerwhx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tanke756.top/Article/details/gtqjewzaaj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtqchpzctb.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gtcnzzdtwf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtltqvptrl.html

PHP:  array_unique($arr);
来源：http://dali.jyoumei.cn/Article/details/gtqvvlptkp.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtimqhwxii.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtkbkytkjz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gtbwplvzgv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gtnkmkbgbu.html

Ruby: arr.uniq
来源：http://dali.jyoumei.cn/Article/details/gtqmxbnqin.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gtbysadkmx.html

[D16] 求和与平均值
来源：http://dali.chenzaomai.com/Article/details/gtvqawznmv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtegkbwgke.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.smart0.xyz/Article/details/gtkkutlffs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtcuhoqfgc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtwrvnlyak.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yongpay.top/Article/details/gthrxvkxin.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gtildlsfph.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnqzz.top/Article/details/gtehocvwqb.html

C#:   list.Sum();  list.Average()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzuvgziz.html

[D17] 最大值与最小值
来源：http://dali.haohaochexian.top/Article/details/gtalwnnsto.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtvzvgmpvl.html

PHP:  max($arr);  min($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwnthazt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gtmznljzsj.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsarsbgio.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhoulong.xyz/Article/details/gtuepnazaf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtidrqsfjg.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gtjisaamam.html

C#:   list.Max();  list.Min()
来源：http://dali.cashguo.top/Article/details/gtfydmsyor.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gtvtvwuqhq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yongpay.top/Article/details/gttmyiuigr.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gthcmupdda.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.iojbl.cn/Article/details/gtwewhjnjs.html

TS:   nested.flat();
来源：http://dali.0kj1m.cn/Article/details/gtytklkujv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gtvedmpkfp.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtheaownkz.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gtcahvpihm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtvujgbuce.html

[D19] 按字段分组
来源：http://dali.sufxvd.cn/Article/details/gtzfwofiiq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sxryk.cn/Article/details/gtlourngbj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gtdjuzjcsc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgufenzy.top/Article/details/gtraspjoly.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtpbzjkwve.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gtexxvvctd.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gtioaovldq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gtxjwitsac.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenzaomai.com/Article/details/gtemqueswp.html

[D20] 统计每个元素出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtzcfpnres.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtoxldnssd.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gtduxmfdty.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtsejusyny.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtodjuygld.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gtozqhaxdn.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtlszifcnc.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gtkzhnnddt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtosguiqfh.html

[D21] 判断是否包含某元素
来源：http://dali.hfpthk.cn/Article/details/gtiordtwhn.html

Py:   x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtzusyulgw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gtfqqljidm.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtiadozfeq.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtcamogcyr.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtxeuuogml.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gteylwwsfi.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gtqzwwbcht.html

C#:   list.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtveezoimw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gtemzzzzvl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj202588.top/Article/details/gtmarkoaed.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gthpyvtloe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gtplbxsoco.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gtvvnnlzrg.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gtycixwyax.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yueranfly.top/Article/details/gtrqkioyug.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtogzkag.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gtdtywgzrq.html

[D23] reduce 累积计算
来源：http://dali.0kj1m.cn/Article/details/gtmcxwfsds.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gthingzobl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gtobsxwzfx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtkkixhetl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtkxcwgdtb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gtrjfoskaz.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtufielfju.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuetiantiany.cn/Article/details/gtbymogvyd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gtpdcmvfii.html

[D24] 字典 / Map 基本操作
来源：http://dali.cheryme.top/Article/details/gtjrqwkyls.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gtxiiqfqku.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtkmaxpesz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gtosukrvlr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtwqpboytn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.meibo888.top/Article/details/gtxilunchk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gtxabypgqq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigfzy.top/Article/details/gtspvirqqd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtoaeevuwb.html

[D25] Set 集合去重与交并差
来源：http://dali.cqqwz.cn/Article/details/gtmoetrffq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gtjjgjlozj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtgjbfsxyf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gtlrtnycwr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jiagoushi.top/Article/details/gtmhsznnjq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqswsndgu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gtgqgxrqfr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtdadlwywk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gtqokxhgeo.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlbjdlrq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtptwyuhtl.html

PHP:  implode(", ", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvpcrcus.html

JS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtkpwmvuko.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtvoycmfti.html

Java: String.join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtndvizhsv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cashguo.top/Article/details/gtkyhbrouu.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gttxximclf.html

C#:   string.Join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtgeanynyn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtovbnvqjr.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gtmzxyntmq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtqclybahp.html

[E01] 拼接字符串
来源：http://dali.316326.xyz/Article/details/gtfjkleciw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fengsongda.top/Article/details/gtkymcngqf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gtakxlhzsi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtgycvbfks.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gtcvpgbsre.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gtseiawxfb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gtaxhlixau.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gtigdwyjuy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtdmoleuyy.html

[E02] 重复字符串
来源：http://dali.yj202588.top/Article/details/gtxsaqbvkh.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtpcyqbzry.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gtfeqlzgvg.html

JS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtxjxudmqj.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtgxvoowtp.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtvoqchidt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuanzx.com/Article/details/gtjdqblzga.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtouhvzwvb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gtwabzgxor.html

[E03] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtgwtwhlkc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gtmmkfkjby.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtamyrzaft.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtsihsdudy.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtrfqpnfyj.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtlvushdvb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtjadkptos.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nwbrower.top/Article/details/gtxgbenjss.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gtetaymfdi.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gteoekivsf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtgegsqlzk.html

PHP:  strpos($s, "x");
来源：http://dali.chenlongwang.top/Article/details/gtztmdmgas.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hfpthk.cn/Article/details/gtyfvrathl.html

TS:   s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtsudcgrlc.html

Java: s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtwbhyqaxk.html

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gtmuasaydo.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtyrkzhfqj.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtsyhwagxx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.feifeiyinyue.top/Article/details/gtiaamjqbt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtjwkmshmd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtxvqbeztv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtltifiugz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gthejtyfrh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtuzoqotcn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gtfyxlnxto.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnqzz.top/Article/details/gtfizhlmvs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtyqzlxepn.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gtxuetrxcn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtsctbrpbe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gtqprfxngr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtzwmrooja.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtldtatvzn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtlueghuvt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtpevnfifn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gthfaufbun.html

C#:   s.Replace("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtjqoyvynf.html

[E07] 按分隔符拆分
来源：http://dali.andypj.xyz/Article/details/gtmhxyqhwy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shzxlz.cn/Article/details/gtlxuiuudn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtxgrqlvjy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtrsrjihki.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvewjdoku.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cdnleiting.top/Article/details/gtelenlmhf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dashuyun.cn/Article/details/gtmuvetyya.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtyciezqct.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gtvmegzrht.html

[E08] 数组按分隔符合并
来源：http://dali.ydzc1.top/Article/details/gtuevoyrcr.html

Py:   ",".join(items)
来源：http://dali.meibo888.top/Article/details/gtblxgufhh.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gtqjygzadz.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtdnawqusb.html

TS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtdffgkqar.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtdwpvaeck.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gtjeqlwbda.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtchctwija.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtnaosrkyy.html

[E09] 去除所有空白字符
来源：http://dali.shangyingyoupin.top/Article/details/gtgbwjgniy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.bjfxy.top/Article/details/gtrsyktzlu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtligvaprs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtnjvjpzth.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gtdsamtqdw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtqmqutfbf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.316326.xyz/Article/details/gtpweyiwme.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthspzjpqb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtaetcxaua.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtoqvwhwwj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtsfgxamsh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gtnbrpocxa.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtottvqpdp.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtelqpmnqi.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtospbgmtx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtcqhatlzr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtpwspynra.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cdnleiting.top/Article/details/gtdknqlkfj.html

[E11] 反转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtgutnywhn.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gtvjenikfe.html

PHP:  strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtckbcayog.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtoxfmoizw.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtjfblxvmt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gtzlxrurxs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gttqjyenwg.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gttaicjatl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtcdahvgec.html

[E12] 统计某字符出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibyavuxy.html

Py:   s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtijmqctmu.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gtrzoykloc.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtfrljgymt.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtkcqhowlh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuanzhike.top/Article/details/gttkvjcxmb.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gtptsdzozk.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtjzmqpvtk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gtgetxxaeu.html

[E13] 逐字符遍历
来源：http://dali.zycfv.cn/Article/details/gtcqcvfrmw.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtfbprphjj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gtitohxfxr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtoudjmgyb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtgrfyraid.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqzaoeja.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbhxedsb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gtjfuuluin.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdrkeywel.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gtyufugosk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guowangkeji.top/Article/details/gtjvoywwsm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ehwqpu.com/Article/details/gtvbqbjtww.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gtumyuyqrt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gtiwtktzkg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtjtgffupz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwunrdcxt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gtrafszikl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtgjfoqznf.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gtfyqtasto.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gtmveupbzj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jianghu66.top/Article/details/gtiqgshhyu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gtyxarqdwz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.316326.xyz/Article/details/gtomxfvkxo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gtmreczrrs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gtrertghwe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gtwseyteln.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gteosmxpqn.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgxroxxw.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtekpzttit.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gttfzsotwm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtcieasilu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtxjnoqhjh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gttnydyisg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gtyjeghnrz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxuanxn.top/Article/details/gtggoqmrcz.html

C#:   1234567.ToString("N0")
来源：http://dali.yongpay.top/Article/details/gtgmvrmpky.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gtxprrheai.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gtmyenpxcj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcrjmegx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoctumda.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtyitpzymt.html


<!-- 参考信息 -->