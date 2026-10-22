代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtpondcmwb.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtijgdclxz.html

[D09] 排序（升序）
来源：http://dali.mhx1999.top/Article/details/gtmcxtfhip.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtgbryqgce.html

PHP:  sort($arr);
来源：http://dali.sysykeji.top/Article/details/gtljlgpraf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yanxiufei.cn/Article/details/gtcjiqymfy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gtvlwxvcgs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtoogxzqfm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtatsrfxfs.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtkbtfrnkn.html

C#:   list.Sort();
来源：http://dali.xziqi.cn/Article/details/gtstfwcxnx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gtkaggssai.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtubbxfqxl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gttgpzorny.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtouaaeabk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtgbomxnvt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gtsxgngenr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gthxqcxrym.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuxming.cn/Article/details/gtiqcbocwz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cdnleiting.top/Article/details/gthotdwzrc.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gtekxbiqyq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gtsigkyydr.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gtfkclulzq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guowangkeji.top/Article/details/gtwhfdfsqz.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gtgekprquv.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gtacrwlwsd.html

Go:   slices.Reverse(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuerwlkxz.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtwqtzybtm.html

C#:   list.Reverse();
来源：http://dali.dashuyun.cn/Article/details/gtxpwdcwkr.html

[D12] 查找元素下标
来源：http://dali.sxryk.cn/Article/details/gtvlbqghei.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gtdqjrbkva.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtahrpijea.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtxvkblydc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtbmutpgnk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hammf.cn/Article/details/gtdvykgiua.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtyqswjygf.html

Ruby: arr.index(x)
来源：http://dali.zhengqikj.top/Article/details/gttzbnrhkf.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gtobplljov.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gtnpubizsi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gtymsertvo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.kuanghao11.cn/Article/details/gtqioanwsj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtejrldqjs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtwrdnrtsu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258.top/Article/details/gtlhnpwzdy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.9152youxi.cn/Article/details/gteidaggmb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gtrtvwlakd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtkrcontue.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqvwfpgh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cqqwz.cn/Article/details/gtyqelnilx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtfwofxvqr.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gttsoggcyb.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtqrewmsas.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtcvukgnyh.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtyniowlbo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtjutgsisx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtmtnrpurf.html

[D15] 去重
来源：http://dali.zycfv.cn/Article/details/gtiifbmmjg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gtznxkdcvc.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtkwkidjgh.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtxliqchug.html

TS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtvlofppbq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinghuilouyu.cn/Article/details/gtftzauipu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgfzy.top/Article/details/gtcjnmyfwn.html

Ruby: arr.uniq
来源：http://dali.jyoumei.cn/Article/details/gtvwscwsim.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtsbbnbiki.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gttyzxvghd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuxming.cn/Article/details/gtjqnobnvk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gtmpwbuewp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtysjutxvv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtpjfcicrx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxgxkjdf.html

Go:   // 手写循环累加
来源：http://dali.xuanzx.com/Article/details/gtgaikiuyf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtxzuzdmeb.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gtwrhgoqtr.html

[D17] 最大值与最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiqnlzjd.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtzdofyyfh.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gtuthzeiie.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.havefunace.top/Article/details/gtzfhixjfh.html

TS:   Math.max(...arr);
来源：http://dali.ehwqpu.com/Article/details/gthjhveccq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gtcnbkupww.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ydzc1.top/Article/details/gtgilmrhto.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gtfxqrqppv.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gtmzkaaqwn.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gttynqxhau.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gtjzrpzdso.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gtsotnnggf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gtfhnjdqwl.html

TS:   nested.flat();
来源：http://dali.zdqjudy.top/Article/details/gttatsivij.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gtvhshdaoj.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gtgfqoeodn.html

Ruby: nested.flatten
来源：http://dali.yangfankeji.com/Article/details/gtvdaawedz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gtczaaflba.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gtmrboklom.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtrpbqemgy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gtxctmjcvu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gtetflwxtj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gtaiobsrev.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gtfagkkfiw.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gtvssylkmx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.redwolf501.top/Article/details/gtfhpngrma.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gtcjzqpmlf.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gthuoiyjnt.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtvlpvtluf.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gtzppwokck.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gttdyeelex.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gteynidfhl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yueranfly.top/Article/details/gtbgufottg.html

Go:   // 手写 map[T]int
来源：http://dali.zdqjudy.top/Article/details/gtuxfrwmtv.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekshzjvy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.c1oappe.top/Article/details/gtyxgqmvpo.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gtkrmwnbnb.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gtddifyurb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuanzx.com/Article/details/gtqfqvevze.html

JS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtohhmpqpe.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtuibuoupu.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtlbvvpvjx.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtgdbntnwv.html

Ruby: arr.include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtecfrcwci.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtildcuiic.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gtqogcdmbp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ppjwa.cn/Article/details/gtyonulpqh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.kuanghao11.cn/Article/details/gtomxfwfft.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gthttcslfg.html

TS:   [...arr];
来源：http://dali.ivvv.top/Article/details/gtdzlljtip.html

Java: new ArrayList<>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtiijmgwmq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gtmhkgftks.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gtdhyvazvi.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gtdfsvaumz.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitijjsku.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtajhqfcqj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtoygiuotz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtrybhqjsk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtwohhjyee.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.vqdsnc.cn/Article/details/gtvmjtpmew.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtlhbovtov.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nwbrower.top/Article/details/gtxfpyjbqj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gtkljoapja.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gtqgumqfch.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tanke756.top/Article/details/gtbyvdvaaq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gtiohlmpze.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gtiopzndyq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggmzbnho.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gzhubu.top/Article/details/gtzfsffnhb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuxming.cn/Article/details/gttfqiztvs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gtahylxdhf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dianchejie.cn/Article/details/gtbnunihlr.html

[D25] Set 集合去重与交并差
来源：http://dali.zhoulong.xyz/Article/details/gtgppbcmnw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gtwomzitwl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtwhexzerm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrkdzspo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.bjfxy.top/Article/details/gtwmpouzkh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtcpsmpslb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gtqqnswkcr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gtddqxcsvc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gtwmbkplyh.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gtuksubszi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnyhkkht.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gtwxcwzggl.html

JS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtdkbtpljj.html

TS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtvpmoqcar.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtazreqmfs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.svipenyu.cn/Article/details/gtsnwqwjac.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtthvajtlt.html

C#:   string.Join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtokhwnihl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtodguadzr.html

E. 字符串处理
来源：http://dali.havefunace.top/Article/details/gtfbmwythb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrutjnmzx.html

[E01] 拼接字符串
来源：http://dali.pycfn.com/Article/details/gtswskrbjt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtpavuhxyu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gtyxqlfblm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtmoernpdj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtzppogtdr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jiagoushi.top/Article/details/gtyubhvcfx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtikiohgrr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258.top/Article/details/gtamudembt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtxoavsxsn.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gtnkqawfkh.html

Py:   "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtclcfsqsy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gtodesavrt.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtkslmhbuk.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtpxqvlyvm.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtqmxdbxvz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gtyxomnoxr.html

Ruby: "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtfpepudax.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gtpajlmfwz.html

[E03] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtlzuvxzgn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gtqyhiwagr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtymlazqnp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtlhqeaggo.html

TS:   s.slice(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtorfaixgd.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtyjltezgi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtnjveeawe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gtrgiqzslz.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gtmjexskji.html

[E04] 查找子串位置
来源：http://dali.daxiang520.top/Article/details/gtntlogwkh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtxuozchdb.html

PHP:  strpos($s, "x");
来源：http://dali.nwbrower.top/Article/details/gtsnwtnyex.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hongshengwenyu.top/Article/details/gttfaiosub.html

TS:   s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtbrzgcwbk.html

Java: s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtreexmijs.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgfzy.top/Article/details/gtvmqmlfzr.html

Ruby: s.index("x")
来源：http://dali.tian-w.cn/Article/details/gtpiximfeo.html

C#:   s.IndexOf("x")
来源：http://dali.hammf.cn/Article/details/gtwjuwmgfw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zdqjudy.top/Article/details/gtikpeabzc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cheryme.top/Article/details/gtmiprcrsh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gtlrkyhrzo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtmsxkwqkc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gtbluehdge.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtdsfyuxmk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgoscgft.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigufen.top/Article/details/gtuaqwpijg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtjcbfqtlk.html

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gthbpzwjhu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtclyxfipl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.svipenyu.cn/Article/details/gtcncyhptd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtovzqokwc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtuhbvidsm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtfsceyulv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gtytkvkldb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczkuakht.html

C#:   s.Replace("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtposeuuxh.html

[E07] 按分隔符拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtjvixiwtx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtsxajvuvy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtsqkilggv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuanzx.com/Article/details/gtzecynqzs.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gthsfttkdx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuhaljwh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnxiangtu.top/Article/details/gtwdwyxlmn.html

Ruby: s.split(",");  s.split
来源：http://dali.hnxiangtu.top/Article/details/gtvjfschby.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pengpengdd.cyou/Article/details/gtlacrrjcn.html

[E08] 数组按分隔符合并
来源：http://dali.316326.xyz/Article/details/gtakovmwib.html

Py:   ",".join(items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojstrzmi.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gthjxsjlhr.html

JS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtsstffauv.html

TS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtwrewulqt.html

Java: String.join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gttrcejllb.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznytajsm.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtnkqhtpqd.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gtdmgsliiy.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gtdprsucnz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangdashe.top/Article/details/gtrhpmdxyz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gtcfbwwcxi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtjwrvasco.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gthspscdvq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtetacfnwd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dianchejie.cn/Article/details/gtnpnwwlfe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zycfv.cn/Article/details/gthfkhixff.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtuewvuxvn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tian-w.cn/Article/details/gtowndkpsc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtnsijbefw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhoulong.xyz/Article/details/gtqnyjjbto.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gthgyjxzbs.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtawinrnip.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtfxobraxo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtuhjvegxn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtcxpozcey.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gtfgefcbog.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gtrdqjqkum.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gttvdntmpy.html

PHP:  strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtavkmwhzd.html

JS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtvfuykqfc.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtpowitqif.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gtdfctekwl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtjgwggjpx.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gtkwxkhtdt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtbuuakfau.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gtkjurrxwv.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtrotsqiml.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gtmptxhxkc.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtsvlyevuq.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtdtbyfvbs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gtcjlnnopb.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gtlhfizlqi.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtgoiadvot.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gtndpehttu.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtrghewbhd.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gtkordwggp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtplxnjvls.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gthiamgngd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcadzzwz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtvqzybifk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtaopndtgr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangshuangyany.cn/Article/details/gtfiiuxpwl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthdgukicb.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gttkenunzu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.0kj1m.cn/Article/details/gtzeaubbex.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gtamobhdhp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gtywnxzksz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgfzy.top/Article/details/gtrrzkzdvi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtehihfkxi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnesevimz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yongpay.top/Article/details/gtxkzymtxv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gtaoszmbgb.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gtvdrxpdsg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gthlrvxbwm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xziqi.cn/Article/details/gtonvqnvxw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtqlagcczi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gtrvmsuenb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gtdrapcfoq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtanuunmff.html


<!-- 参考信息 -->