代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtqvqxypar.html

Java: list.subList(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtqdwjounw.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gtryqwmpzz.html

Ruby: arr[1, 3]
来源：http://dali.sxryk.cn/Article/details/gtyvqlfphq.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gtypugsfgu.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gtmnlpknck.html

Py:   a + b;  a.extend(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxxxopzx.html

PHP:  array_merge($a, $b);
来源：http://dali.bjfxy.top/Article/details/gtpjezwjsa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gzhubu.top/Article/details/gtyxbjchun.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gtajnjcknz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jyoumei.cn/Article/details/gtnqdpqmas.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gttejjfitn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gtltmuvkci.html

C#:   a.Concat(b).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtcsdpuxny.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gteazgvfeg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtbyxdnjnn.html

PHP:  sort($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtefeftofj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sufxvd.cn/Article/details/gttrsouftj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hywenlv.cn/Article/details/gtmthnowjh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnqzz.top/Article/details/gtbjznoomy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtbvtregnm.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtsktzsskm.html

C#:   list.Sort();
来源：http://dali.cdnleiting.top/Article/details/gtmongasvp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.iojbl.cn/Article/details/gtbhalyqrn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xylfe.cn/Article/details/gtthsgvtut.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gtzpbleywg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gtakzyvsqq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtrlcxiymv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tianlin.xyz/Article/details/gtlqzakqkw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hongshengwenyu.top/Article/details/gtmwqytehx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gtgvsjmkwt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gtujehkvxt.html

[D11] 反转数组
来源：http://dali.jqgufenzy.top/Article/details/gtfajdjnpp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gtwzvdadgk.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gthtmmmmmo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gtmefauxhg.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtrvqjduxh.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gtucemghwv.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gtgolkjpup.html

Ruby: arr.reverse
来源：http://dali.xuanzx.com/Article/details/gtskijiarj.html

C#:   list.Reverse();
来源：http://dali.0kj1m.cn/Article/details/gtmgsnltdz.html

[D12] 查找元素下标
来源：http://dali.redwolf501.top/Article/details/gtqhrpcmke.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gtpvydrgin.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gtebyhufld.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtclnhcifw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gtdpnysbgt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangshuangyany.cn/Article/details/gttkgftgbe.html

Go:   slices.Index(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtxpdkkkxt.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gtdpfscjsn.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteltdmsib.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gtfkuwqjyi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xylfe.cn/Article/details/gtqgbgwejf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gtfsdchccn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtuwwbxmyl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtvdimquwr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258888.top/Article/details/gtehowjenh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuanzhike.top/Article/details/gtkhalbqkc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yvedp.cn/Article/details/gtqazmqcil.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zycfv.cn/Article/details/gtcwqfamrm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cashguo.top/Article/details/gtuxxitpvi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dashuyun.cn/Article/details/gtolixngkp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcvxncdn.html

JS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gtzhhyuexo.html

TS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtfcjhcpxc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258888.top/Article/details/gterkyaisr.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbcrznqs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtvxiupvak.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtrpeorpfp.html

[D15] 去重
来源：http://dali.cqqwz.cn/Article/details/gttsuqvwgu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtnidlturm.html

PHP:  array_unique($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtjfjgjurf.html

JS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzxnfejh.html

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtozthiwzs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtfhjdbrsh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gtevzzcgck.html

Ruby: arr.uniq
来源：http://dali.yvedp.cn/Article/details/gtbwxootdm.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtcxjmozxg.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gtglntcrvn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.smart0.xyz/Article/details/gtbeujbqlc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtiojrbptx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtzekhvkol.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtiwwdgdda.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gtpxndercp.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtewuonbbv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtbfemntfh.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuxming.cn/Article/details/gtxnpawjzm.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gtqudglfbh.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gttafjxcps.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gtrbcbbtaj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtnwutnucq.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gtimnimxbs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ivvv.top/Article/details/gtrsvslubg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtzlcuwldu.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gtkxatlxnk.html

C#:   list.Max();  list.Min()
来源：http://dali.hnxiangtu.top/Article/details/gtudlxzygg.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gtikekmeos.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gtlcgadiae.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gtaqthxwbo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.c1oappe.top/Article/details/gtsgavupbr.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gtvaqutuna.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdxeomhl.html

Go:   // 手写双层循环
来源：http://dali.havefunace.top/Article/details/gtavejjjzm.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gtneoijjjq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtdxbizlje.html

[D19] 按字段分组
来源：http://dali.jqgufenzy.top/Article/details/gtrdqmhyzt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqloecqf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jianghu66.top/Article/details/gtregfakgb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gthgixhrmn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gtydvbjezy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ehwqpu.com/Article/details/gtkrwjnzpb.html

Go:   // 手写 map[string][]T
来源：http://dali.fzhhl.top/Article/details/gttkaznxzh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gtyevfxviy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gtutjjvisk.html

[D20] 统计每个元素出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtwphofcdm.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gtvggrhnug.html

PHP:  array_count_values($arr);
来源：http://dali.aizwys.cn/Article/details/gtfhisuzrr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gthylgflfp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtpkhiphch.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gzhubu.top/Article/details/gtuydaqnmj.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gtnzixbebh.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtikwrgpzu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gtcahejchk.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gtjjlnctis.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gtqpukurfb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gtcctdodko.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtswbrsxez.html

TS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtlgrppjdm.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtuybvppta.html

Go:   slices.Contains(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gteiodutox.html

Ruby: arr.include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtphgvezwu.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtnxbbyqkh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuwvkdol.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yueranfly.top/Article/details/gtjrtozxra.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tianlin.xyz/Article/details/gtkydmtgcy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtwnxrvtce.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gtlmaktnmr.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gtnipgepro.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gtotveeheh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gtrharxevi.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtiyjigmlh.html

[D23] reduce 累积计算
来源：http://dali.cdnleiting.top/Article/details/gtftfbxsaa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cashguo.top/Article/details/gtlfrybslu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gtqxdfjjcn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtfdrqsmar.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtwlzmglie.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtklthfbut.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtzscxopzt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gtqcrojvwk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtfhugnhbr.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gtzyxqykht.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gtidixpcmb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yongpay.top/Article/details/gtxzgzxhwx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gthceqwoej.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtrwixmufy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gtkxutiqsm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gtwzrovsit.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nwbrower.top/Article/details/gtdtseflbs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gtcchhmijl.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gtcbikmczs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zdqjudy.top/Article/details/gtndxkgjsm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtjsbnorip.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yonumen.top/Article/details/gtjpsyypva.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gtdyknlxky.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gtelwidjcy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfuietee.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlljgkcxj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtbwkmgiuj.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gtnkdcbzcs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtbsjxeevz.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gtipatluht.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gttpdtzdhv.html

TS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtjlvrahja.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtdqtabxoz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gthfmfulbm.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtyhmkhyej.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtylukeqet.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtytgvzhoi.html

E. 字符串处理
来源：http://dali.tian-w.cn/Article/details/gttrvkldvq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtanbdnlay.html

[E01] 拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtdhjlyhid.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cucudq.cn/Article/details/gtjljmiyzt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xinyue.icu/Article/details/gtrpeoaljm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtupeewpcy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrqvqocy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdodtepi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtvnhdjgbh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangshuangyany.cn/Article/details/gtnwxwrevd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtzsbiltbi.html

[E02] 重复字符串
来源：http://dali.zhixingplan.top/Article/details/gtbcjibkjd.html

Py:   "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtgyalqlti.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj202588.top/Article/details/gtnfswhwgk.html

JS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtttarmliv.html

TS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtnzuvppdi.html

Java: "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtqhvwkkkp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gtzsddpajs.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtkktmocab.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangdashe.top/Article/details/gtsfrdovrk.html

[E03] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtslkhyfnq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gtziukvrrb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtwtqsougu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtbxdflpci.html

TS:   s.slice(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtcwoacnmg.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gteciiqkap.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtszjnptuj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gtzpkkqxlk.html

C#:   s.Substring(1, 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtvqxxruab.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gtgwdbwfdp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtewsngorz.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gtoblcmfmr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gtmjfscjcz.html

TS:   s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtoezxitxs.html

Java: s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtyedjnhyg.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gtxkqyxndz.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtvpttalkl.html

C#:   s.IndexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtouiamwgl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtxgecziyq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hywenlv.cn/Article/details/gtgjvknqoi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpvymbiu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtnrccgnrn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gturinlfpg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtazscwobs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xylfe.cn/Article/details/gtpgdclphj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aibaodan.cn/Article/details/gtblddrogc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtuycdbacv.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzflafph.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gtmfimimcn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtdsmgbefp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtytsvbpai.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqjfxavo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtqmudxjrs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtewqojkye.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj202588.top/Article/details/gtzdiclowi.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtciinlxjf.html

[E07] 按分隔符拆分
来源：http://dali.9152youxi.cn/Article/details/gthwlytrez.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gtrhkbhksx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gthmazlgmv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gthndlspgf.html

TS:   s.split(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtgslgftnx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gtfmzprqum.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gtgqehhvgc.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gtxapsyvpr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj202588.top/Article/details/gtgoqoeban.html

[E08] 数组按分隔符合并
来源：http://dali.316326.xyz/Article/details/gtuirkhxca.html

Py:   ",".join(items)
来源：http://dali.shangyingyoupin.top/Article/details/gtuelgxcix.html

PHP:  implode(",", $items);
来源：http://dali.hnxiangtu.top/Article/details/gtjunojdiq.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtyqhfwbzs.html

TS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtpdqtzltl.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gtdcykkefw.html

Go:   strings.Join(items, ",")
来源：http://dali.ehwqpu.com/Article/details/gtzcvhtgnd.html

Ruby: items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtceptwmcw.html

C#:   string.Join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtehwmzbxq.html

[E09] 去除所有空白字符
来源：http://dali.meibo888.top/Article/details/gtfymmrlxo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.svipenyu.cn/Article/details/gtcuszvpkh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gtzratysdm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtkoxodjsg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtnwxswmsd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtejjqczxk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xinyue.icu/Article/details/gtflphdvrb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gtzfufepyr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hammf.cn/Article/details/gtqjjcvmzk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangshuangyany.cn/Article/details/gtvpozxnja.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtknjzdiqh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gtfaagmzmc.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtwgthdgcn.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtbeggosrz.html

Java: String.format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtsqxocugn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtfohcrwom.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtvpodensm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gthzuzvxwb.html

[E11] 反转字符串
来源：http://dali.zycfv.cn/Article/details/gtvyhtjaja.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtizjqpxga.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtchicaser.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtsbqxqvnb.html

TS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtcdpeoray.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gtocetpbtr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hammf.cn/Article/details/gtnuqgogte.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gtnkqjeljq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtyfxnupwn.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gtwnrhozga.html

Py:   s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtfofbiopt.html

PHP:  substr_count($s, "a");
来源：http://dali.yongpay.top/Article/details/gthscxdbiw.html

JS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtpqkrvxbf.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtxslcfbbn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gtvbspcgti.html

Go:   strings.Count(s, "a")
来源：http://dali.svipenyu.cn/Article/details/gtauimuixh.html

Ruby: s.count("a")
来源：http://dali.meibo888.top/Article/details/gtnqbzyctd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gtwjivpxfa.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gttytxlaof.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gthlzftdew.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gtgizgpeln.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gthmxpjzni.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtzrllgmof.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fzhhl.top/Article/details/gtdjwfcdjy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gtdogzwixx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbktpsqs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gtlgnfdgcn.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtaeskuaan.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgrvexlz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gtiufuocry.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnmvdywm.html


<!-- 参考信息 -->