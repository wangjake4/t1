代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtxcnzayxm.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gtgkfnujkw.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gtghceraxp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtvxpvhxlu.html

PHP:  sort($arr);
来源：http://dali.cashguo.top/Article/details/gtvzgnbung.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsvnnnil.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gtpbapjjts.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktxwbcmf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtmutxrwad.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtfacftvup.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gtifdldoey.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gtpekezjgg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gtrkmmwtdk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gtbbggpvzy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gtdzeeixij.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtxbfwogkm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtthjwddhx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtviscelwj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gaohongyu789.top/Article/details/gtsvvlobxn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zycfv.cn/Article/details/gtdpngdqzk.html

[D11] 反转数组
来源：http://dali.jiagoushi.top/Article/details/gtnzkswcxz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gtmnstkfei.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gtqeyygzul.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.vqdsnc.cn/Article/details/gtwjxfmjen.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gtuqxoyuxf.html

Java: Collections.reverse(list);
来源：http://dali.bjfxy.top/Article/details/gtkrmvpksq.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gtozvejmhg.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtgrfrcyhk.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwskjdwko.html

[D12] 查找元素下标
来源：http://dali.haohaochexian.top/Article/details/gthughifgy.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenzaomai.com/Article/details/gtkraqquib.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gtxcntxlvz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtwplbzbbs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gtfhixczdq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gtasgneajb.html

Go:   slices.Index(arr, x)
来源：http://dali.mhx1999.top/Article/details/gthzpvlcfh.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gtzscrhoiw.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gtcmkbjnqt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shangyingyoupin.top/Article/details/gtnpmcibpu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gtcduxposs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cdnleiting.top/Article/details/gtzparpgef.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtylypfyut.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtbkcmfoho.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gtdqtrcezx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgazseehj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gtfsiewava.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gtfawcjlhn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtvsilbhbp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtwtqqxgsx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gtugwnrsrp.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtdupwrlff.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtpyyvfkcy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sysykeji.top/Article/details/gtusvuvhdh.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteslmtenm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gterebimva.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtplnlghrd.html

[D15] 去重
来源：http://dali.tanke756.top/Article/details/gtfaptysyp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtlhccelgi.html

PHP:  array_unique($arr);
来源：http://dali.shzxlz.cn/Article/details/gtpvtufljc.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtugkxconz.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtxplzkrtp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gtbxlscrsr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gtkqeqnpto.html

Ruby: arr.uniq
来源：http://dali.jqgufenzy.top/Article/details/gtkfamzuab.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtdoaicxlr.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gtbhqmlkvt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gtopmertne.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gtkiekkjyd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtwombbnqc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhwifywq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gthjtifdop.html

Go:   // 手写循环累加
来源：http://dali.hnxiangtu.top/Article/details/gtwqvkoicn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258.top/Article/details/gtwlujkzte.html

C#:   list.Sum();  list.Average()
来源：http://dali.cdnleiting.top/Article/details/gtbromnktu.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gtihhnsahq.html

Py:   max(arr);  min(arr)
来源：http://dali.meibo888.top/Article/details/gtyrqhfifd.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258888.top/Article/details/gtmcyqpflf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.9152youxi.cn/Article/details/gtbotxiwlp.html

TS:   Math.max(...arr);
来源：http://dali.gaohongyu789.top/Article/details/gtsjwtoydu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fengsongda.top/Article/details/gtdosogmce.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.birdmap.top/Article/details/gtwflufvsx.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gtjromezyv.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gtycfcyfom.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gtoydqjxvk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zdqjudy.top/Article/details/gtfwoiypwp.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtgwxmqohy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenzaomai.com/Article/details/gtrmaypqcv.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gtusofoxzp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gttqasggpy.html

Go:   // 手写双层循环
来源：http://dali.ehwqpu.com/Article/details/gtmieofmkn.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gtmsnttnng.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cheryme.top/Article/details/gtltjruikz.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gtuqbhtdmu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gtzvjrjbdz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gtfgikzsxm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yongpay.top/Article/details/gtevbqbyzz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gtjbwimmlw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gtkxjyjgav.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhmwqxcx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gtwmvrucjy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gtzrrrmxqu.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtffbulrrq.html

Py:   Counter(arr)
来源：http://dali.cucudq.cn/Article/details/gtgokgxsjm.html

PHP:  array_count_values($arr);
来源：http://dali.xuanzx.com/Article/details/gtcsutdweu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtdwpgbpxw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtqyycxqgl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtqwmdzxyr.html

Go:   // 手写 map[T]int
来源：http://dali.jqgufenzy.top/Article/details/gtizkohxgh.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gtmdymnvio.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gtbohvptji.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gtsqrfzrjv.html

Py:   x in arr
来源：http://dali.xuanzx.com/Article/details/gtdlrmoqoh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gtvvjoujfm.html

JS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtavdkufll.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtrugmjfib.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdprxsmgr.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtreljqhow.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtsxaoojxk.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gttbgxciin.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhixingplan.top/Article/details/gtfimhotdh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gtwfqmnknw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gtczzprzos.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.haohaochexian.top/Article/details/gtdwnmsoad.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gtkmftetzy.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gtzntkvcbz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gtbxaurwpv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuanzx.com/Article/details/gtqjkusroq.html

C#:   new List<int>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtakuwiyyn.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gthtgpgbvj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.mhx1999.top/Article/details/gttjwesata.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhengqikj.top/Article/details/gtzxqwuvgc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtjkxcjrvn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtyddkgolu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gtudcutsme.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtfufzfmlb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqnwkdgn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gthhhgkdlc.html

[D24] 字典 / Map 基本操作
来源：http://dali.fengsongda.top/Article/details/gtdxpmblpz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258888.top/Article/details/gtsxrfdijr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjeoporpw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gtpumucase.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtirffzufm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hammf.cn/Article/details/gtkepbseoq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenjidiqi.icu/Article/details/gtyuvsuptf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gtfudgdfpx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hysaishi.cn/Article/details/gtddbpfxzk.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gthsokwxzq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aibaodan.cn/Article/details/gtfenwjixf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gtckpeibis.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gtjlcqxcam.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtzeapgceh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangdashe.top/Article/details/gtlylurhbp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtzhzrrged.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gtlrorvein.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtrnsttikg.html

[D26] 数组转字符串
来源：http://dali.aizwys.cn/Article/details/gtjjszcjxg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gtffttdwtq.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtwkrenmry.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtvgnmzmzw.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtspqrinqv.html

Java: String.join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtozphojrz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gtvrgwirqy.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtcqcbwpbj.html

C#:   string.Join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gtfxrctsqk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtavenlyqg.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gtkqnbpkwu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfqxntouf.html

[E01] 拼接字符串
来源：http://dali.sweek.top/Article/details/gtmkyjxrcp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlnnjmid.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtppiciexn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtcdrkxuly.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gtszfrfkvu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gtgvktcyql.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkgfngxv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtvfauaptd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtadifkjfg.html

[E02] 重复字符串
来源：http://dali.cashguo.top/Article/details/gtlowctgau.html

Py:   "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtohngugsq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.haohaochexian.top/Article/details/gthidtibag.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtqcnhhnwi.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtwijpffee.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gthaudeqqu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gteoqzvpil.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gtaclxtsjj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gtlngukjqv.html

[E03] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtrarqrvwd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gtyhvvfezt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gthbrkeact.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gthkdvswwc.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtqkqkuscl.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gttproeato.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gtzoytoiia.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guowangkeji.top/Article/details/gtiwgeciax.html

C#:   s.Substring(1, 3)
来源：http://dali.guannengcc.top/Article/details/gtwbgccdah.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gtpiajugoq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tanke756.top/Article/details/gtgsiqxvyh.html

PHP:  strpos($s, "x");
来源：http://dali.chenlongwang.top/Article/details/gtmclfnbkg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guowangkeji.top/Article/details/gtpsjltuuo.html

TS:   s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtprtzyrwx.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtyehbsvpw.html

Go:   strings.Index(s, "x")
来源：http://dali.hysaishi.cn/Article/details/gtsdkadbmx.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtwccinigd.html

C#:   s.IndexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gttfzrlhgq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gtcbpodgrb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yonumen.top/Article/details/gtnpoavatx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqljgdlpk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtoxpzwzrd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gtytnvmcra.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtrsfsjlhx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jlsjyb.cn/Article/details/gtimnafuek.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gtatwjlnjm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtmwqkokox.html

[E06] 替换子串
来源：http://dali.smart0.xyz/Article/details/gthmoflorh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjfwkwxn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.smart0.xyz/Article/details/gtlothonnh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtdzheixfq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtnzgbczno.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtgnlwkhhu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtjrietozl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtuxlxfoje.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtirnahaoo.html

[E07] 按分隔符拆分
来源：http://dali.mhx1999.top/Article/details/gtfodchcpr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gtqijkcmjq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtwervuxzk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuxming.cn/Article/details/gtxjdtqgfc.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gtpxddupdg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gtwxejpabn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzdmlwxub.html

Ruby: s.split(",");  s.split
来源：http://dali.ydzc1.top/Article/details/gtpdbefefh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxzalchg.html

[E08] 数组按分隔符合并
来源：http://dali.birdmap.top/Article/details/gtkddbnxhi.html

Py:   ",".join(items)
来源：http://dali.xuanzx.com/Article/details/gtvppyuywn.html

PHP:  implode(",", $items);
来源：http://dali.smart0.xyz/Article/details/gtgcodkroq.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtwtxzynaw.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtaizizrni.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtumnpccel.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gtilarppit.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtgoxqghvc.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtrzelgisb.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gtgenrlrck.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gtzkfuqteq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gtnwflbxqo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtknshgsvl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gtggazdxfw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtejwvysju.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gtowextplr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gtmabxzocm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtygthkbff.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gtvsjwuvxc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtgtjzdhgu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ppjwa.cn/Article/details/gtaqifibsg.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gttlcyeqzi.html

TS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtvitfsrrp.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gthorfispj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtikcfxorh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtvvjsiypp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cdnleiting.top/Article/details/gtydrroqes.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gtwfdzcdll.html

Py:   s[::-1]
来源：http://dali.hnqzz.top/Article/details/gtmluhacql.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtmoavddze.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtwuzcpklc.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtamhnuago.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gtjezrabfm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gtlwpbjtvi.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtfefnaqnd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtummfrwgc.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gtvhnfahfc.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gtdjozcget.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gtgvfsfocg.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtvvjkueds.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtadjmlnev.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gtlmrtwsfm.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gtocgblryb.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtfuddkvek.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gtsjxoborf.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gtteotgynk.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtodqaljta.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gtwbwlkkzg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtioanamcu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gthfsohmhc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtfjturwxi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdknuqiz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gttmuaatmc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gthpytkhzd.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigfzy.top/Article/details/gtzoflclrz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtaawjczsp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gtzxpsodws.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gtcdqavbfd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gtuelfgmbn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gtzkuqugdb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gtimrxsksg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gzhubu.top/Article/details/gtriodvffp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtvbgewpkc.html

[E15] HTML 转义 / 反转义
来源：http://dali.yvedp.cn/Article/details/gtjvisrifr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gtxljvczmx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gtyecifitj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gtafwetxgp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtzimulhmf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtxyyjcrvc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gtcmtyzgap.html


<!-- 参考信息 -->