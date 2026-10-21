代发 wailian999

PHP:  sort($arr);
来源：http://dali.guowangkeji.top/Article/details/gtwlzjqdsn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gtdqitorly.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.havefunace.top/Article/details/gtxqyrwifo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gtmpuknilg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtttwaxgxe.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtgdgxgrmo.html

C#:   list.Sort();
来源：http://dali.tian-w.cn/Article/details/gtmsdtflhe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gtewicvwxk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtqaajuqrs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtfghgoqzf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtokiclqnm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtaphccizv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gtlseayriq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xziqi.cn/Article/details/gtenyoktld.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guannengcc.top/Article/details/gtkrrxnwmu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.vqdsnc.cn/Article/details/gtebmvqnta.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gtiqigstuj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gtccyyrjgs.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtrnawyqiz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gtdyakbcdm.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gtcthmqvnr.html

Java: Collections.reverse(list);
来源：http://dali.jqgfzy.top/Article/details/gtneueoqsw.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gtozwbzuzm.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gtjaoimbnv.html

C#:   list.Reverse();
来源：http://dali.guannengcc.top/Article/details/gteitlzibh.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiywvwsvh.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gtjigjddcx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtqveujpab.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtwahvxheb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtxbldjdqd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gtnagaqots.html

Go:   slices.Index(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtcxjgujcz.html

Ruby: arr.index(x)
来源：http://dali.jyoumei.cn/Article/details/gtbcwjvekz.html

C#:   list.IndexOf(x);
来源：http://dali.jlsjyb.cn/Article/details/gtmxgjzssi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gtuoemcrhs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtxlktfqbs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbgdsuya.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtxhwvzqzz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtcmivmrli.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtljomxduj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shzxlz.cn/Article/details/gtaxdapxyg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yueranfly.top/Article/details/gtptphtivd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.smart0.xyz/Article/details/gthhdlnsqr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gtoufrurhg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gtzletvkpc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cashguo.top/Article/details/gttizqslyt.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtwghkmtcx.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gtpejbuodc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cheryme.top/Article/details/gtbpqofgtz.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gtepnirkkt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gtjxezhczl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yongpay.top/Article/details/gtucnlaovi.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gthadxkmrg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtyutnpwxx.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtvldivlkz.html

JS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtdidrdsto.html

TS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdckavuh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtrbdyyeut.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gtfiweiqza.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gtvlrswtdp.html

C#:   list.Distinct().ToList()
来源：http://dali.yongpay.top/Article/details/gtgplogxtq.html

[D16] 求和与平均值
来源：http://dali.kuanghao11.cn/Article/details/gtsovahmgl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gtwzvwjmsh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtmwnrdzpe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtanozfjnk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtlwheazfb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fzhhl.top/Article/details/gtaeaniavm.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gtemvqyxej.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.meibo888.top/Article/details/gtjnjihjya.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gtmahkmgtr.html

[D17] 最大值与最小值
来源：http://dali.wangshuangyany.cn/Article/details/gtbymrttwv.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gtouphxjqq.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gtatayabbe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guannengcc.top/Article/details/gtjmdouese.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gtyllyfwyg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cashguo.top/Article/details/gtpgythshn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtcepdthae.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gtujdbedxc.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gtaaqzfvgp.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gtcoxnbksm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gtwgjixsnt.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gtnleulpcz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gtaharcfta.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gtuqtyewpp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shuidangran.top/Article/details/gtgqyziohn.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gtejlfjlak.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gtntvvscfe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gtutweqxbg.html

[D19] 按字段分组
来源：http://dali.ybcxt.top/Article/details/gtzgeavtuq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtzplxqdma.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.smart0.xyz/Article/details/gtocensqli.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gtwrujafub.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gtpntjwyfv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtjxazhoch.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gtkkbyyfzc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gtfwxxthsn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gtpkyqmwan.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvfnrvem.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gtczsjctaz.html

PHP:  array_count_values($arr);
来源：http://dali.iojbl.cn/Article/details/gtqlmfrwgn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtnntfjnsv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gtlmkbdjgh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtuvrxzllc.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gtwxlkkyrc.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gtzdkmurxz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gtvicxhkat.html

[D21] 判断是否包含某元素
来源：http://dali.kuanghao11.cn/Article/details/gtkkvkbctu.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtfacsoddv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gtrrljeqvw.html

JS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtmayfkzfx.html

TS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtlpastvhm.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gttdnldbai.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtclvixmrs.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtujahkoik.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtzuphyoqr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gtqfqftjsf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cashguo.top/Article/details/gtnelmsufd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gtoonkeqjp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gturdgltjp.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gtbaseahsl.html

Java: new ArrayList<>(list);
来源：http://dali.yongpay.top/Article/details/gtoxrvvziy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gtunemraag.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hfpthk.cn/Article/details/gtevpveuon.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtrswmfcva.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gthdupeeqy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gttnhnlvhs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gtldknzbmg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtpdlpkkvx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtggcojoga.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gtiivthhto.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtnotppmhc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouejfini.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhixingplan.top/Article/details/gtsgbaqwsh.html

[D24] 字典 / Map 基本操作
来源：http://dali.xziqi.cn/Article/details/gtitpjitpp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tian-w.cn/Article/details/gtbtydeuyu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gthpwyvzvf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gtxhjyepci.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gtzkrggkrt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258.top/Article/details/gtacpkyejz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gtmkpsmnai.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gtmypwzxyj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hysaishi.cn/Article/details/gtbogikanl.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gtyqlhtuej.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gtnkjgxmrc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gtfwglxdru.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gtbgdkgvsl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbqrpnih.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gtcjtaabod.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxinkj.top/Article/details/gtafmtslsu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtokeyakkh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtvorgmjvc.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gtfnqzhjhl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtqqkerscs.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gtefcqcbaa.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtmmkskhex.html

TS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtplsemgdw.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtjhmilzrf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gtumaaqody.html

Ruby: arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtmvcgphqm.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gthrnenygt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtciqzlwld.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gtoxvphlbm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmyunoups.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gtipndtnzx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jyoumei.cn/Article/details/gtwuwkjpwr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenlongwang.top/Article/details/gtdyasxmgh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gttaxwtvjj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtcziobfgk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guowangkeji.top/Article/details/gtmadtoeuf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yanxiufei.cn/Article/details/gtobwhoncq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxdumhfb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ivvv.top/Article/details/gtgxujlzay.html

[E02] 重复字符串
来源：http://dali.tian-w.cn/Article/details/gtscdevjbk.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtkxfjmjik.html

PHP:  str_repeat("ab", 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtbhmaufss.html

JS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtinpsgsxs.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtxwzpkmjf.html

Java: "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtveunjfzh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.havefunace.top/Article/details/gtuxyadmst.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtltklbxhr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jlsjyb.cn/Article/details/gtkpnevhgh.html

[E03] 截取子串
来源：http://dali.sweek.top/Article/details/gtnvjehees.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gtoyplgabz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtwsupndjs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtbpvhhutr.html

TS:   s.slice(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtvumbzzlb.html

Java: s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtgmjrcgks.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtylnqxrbj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pengpengdd.cyou/Article/details/gtjauqqint.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gteodgnzuc.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gtzlhdknyb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtvmcqdcyk.html

PHP:  strpos($s, "x");
来源：http://dali.c1oappe.top/Article/details/gtfkmnlxhi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aibaodan.cn/Article/details/gtuxvalboh.html

TS:   s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtzwbvdiax.html

Java: s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtcoyiwavz.html

Go:   strings.Index(s, "x")
来源：http://dali.0kj1m.cn/Article/details/gtvrmoljfv.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgykfyybv.html

C#:   s.IndexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagvmugau.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ehwqpu.com/Article/details/gtrlwvcxsz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuanzhike.top/Article/details/gtklhzznps.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gtceviuluh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgljtcnjg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gtlobfuvtc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtailjlice.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hysaishi.cn/Article/details/gttkvaeckx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yongpay.top/Article/details/gtlbkkeynq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtbhpabsqa.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gtgefrcuwh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtuefuslft.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.birdmap.top/Article/details/gtvewhwfko.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtheoywkko.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gttudrhyos.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtujoevifk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtpvqwozlw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtlmnypwbb.html

C#:   s.Replace("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtchgqyclt.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtcmxalzbz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yangfankeji.com/Article/details/gtsvnzutwm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.meibo888.top/Article/details/gtlcikxqlt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtiqvcbhii.html

TS:   s.split(",")
来源：http://dali.shuidangran.top/Article/details/gtrxfhylhi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxinkj.top/Article/details/gtcrcihfig.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gtqbwvwuoc.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gtmojreigi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gtgcblmnly.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gtfmzbgoyc.html

Py:   ",".join(items)
来源：http://dali.kuanghao11.cn/Article/details/gtvdfflxeb.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gtcilkdwfw.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtuggthfly.html

TS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtdehjywzw.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gtmxtvtahz.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gthiepsblh.html

Ruby: items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtvdqxsbsx.html

C#:   string.Join(",", items)
来源：http://dali.pycfn.com/Article/details/gtetzyvwlt.html

[E09] 去除所有空白字符
来源：http://dali.shzxlz.cn/Article/details/gtagqvbqyi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gogol.net.cn/Article/details/gtgfgetflv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgfzy.top/Article/details/gtwqcdqurn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtkajchfea.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtdeeixogm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pycfn.com/Article/details/gttarwuamv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gtusvharzs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gthonbymkr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtnezqqpmc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtpytkyurd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gteggdjfsj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ppjwa.cn/Article/details/gtwpfwxutj.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtpxxfaabi.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtaaamhkbh.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtcuzplfzx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtiodrsjsv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gttxkpxdcr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gtjhjspjhv.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtektuyenb.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gthljxjdou.html

PHP:  strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtzifrjrhz.html

JS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtucdceaid.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtgzpxgkln.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gtlchbriis.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gtadlcofxr.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtlytsfmfg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtumudaldp.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gtiiukbrva.html

Py:   s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzqrqcpt.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gthfecygae.html

JS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gttcglbgrv.html

TS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gttddnonrd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgufenzy.top/Article/details/gtrqnsvqst.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gtruqpokyi.html

Ruby: s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtlcidewnw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gtxiywpupa.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gtrhjgwrks.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzpvcqfh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gtikhyrcka.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtatlekzid.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtoanwdrjr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtppjhuqku.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gtpbxlfyny.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gtagwbiccw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gtfpbvhvnx.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtmxxibhwm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.0kj1m.cn/Article/details/gtspqyqhfs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gtsfsrpmyw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gtidqvwofa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gtmrrhgows.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtixybxkik.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuanzx.com/Article/details/gtenuacdcw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgfzy.top/Article/details/gtckqykquu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cucudq.cn/Article/details/gtsrbtqvme.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gtwzfpbcbs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gtfpeskrbq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gtxyedjowm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gtzqlnjsvr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gtzereiasw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtpaiknxuu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.haohaochexian.top/Article/details/gtxxypgcpb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gtugavbwjq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtwuwtsmxk.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gttciayoyn.html

Py:   f"{1234567:,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuruuswu.html


<!-- 参考信息 -->