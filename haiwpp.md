代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ppjwa.cn/Article/details/gt2zigpdtof.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnupandu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gt2ajsxbdon.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gt2lqbvltgv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gt2teugvqpq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbigmhch.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hysaishi.cn/Article/details/gt2tkkanyor.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gt2citsjduf.html

[D11] 反转数组
来源：http://dali.hywenlv.cn/Article/details/gt2aofohkyy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yvedp.cn/Article/details/gt2yffktebj.html

PHP:  array_reverse($arr);
来源：http://dali.shuidangran.top/Article/details/gt2mdfoitaz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj202588.top/Article/details/gt2vcxymlxo.html

TS:   [...arr].reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gt2xuazlihw.html

Java: Collections.reverse(list);
来源：http://dali.zycfv.cn/Article/details/gt2dlihslri.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nawvemzx.html

Ruby: arr.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2ytncsbyp.html

C#:   list.Reverse();
来源：http://dali.sweek.top/Article/details/gt2iktswnod.html

[D12] 查找元素下标
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gapflkcp.html

Py:   arr.index(x);  x in arr
来源：http://dali.sufxvd.cn/Article/details/gt2pkfcoykv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gt2rzzmpikv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2gybndbvj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gt2jngoccko.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gt2rohtxmnh.html

Go:   slices.Index(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmwscgnu.html

Ruby: arr.index(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2newnzekj.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qegwrnbl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gt2yavhserf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ydzc1.top/Article/details/gt2nwthcpkt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gt2udqdtwuq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gt2dxekviyg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gt2ugvofsfj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2kimnpfbz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gt2nvphddmk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zycfv.cn/Article/details/gt2fxppfgdw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2glfumjia.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aibaodan.cn/Article/details/gt2ogakiclw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2gtkvlczh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2hlfwimqg.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eiqrbiom.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2tgfwanku.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2lmfdlsgm.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gt2yoqbavxr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gt2kyshbohb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2arvslmhj.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gt2vjddiknk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gt2gnjxeaon.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gt2tyxewfyg.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gt2bxxeakjd.html

TS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gt2wanoywoi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gt2dtgoxvtm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tianlin.xyz/Article/details/gt2kjknztae.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gt2mdspuhqr.html

C#:   list.Distinct().ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2rgflqsmy.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gt2gvdgrbmc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2amudwtjr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.c1oappe.top/Article/details/gt2qdmtvhfc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gt2ufvyndnk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2uuplpskj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwapbxzd.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgqtqyde.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gt2vzwzlbxn.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gt2bjccsilk.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfcwhzyi.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xgqjlmtj.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2vrazgeol.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wkyyomvg.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gt2mmksxzqx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gt2tloanize.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2gnwoawox.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gt2rarvlbbf.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gt2ffnxjkfm.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdavozhr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gt2jzoodeta.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gt2ahrwvrpl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gt2iwfrpqwf.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gt2wfxdhhpp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2cjkhmxmj.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gt2adngcvti.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gt2kefakkfb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gt2spoyxnpa.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gt2yxgsojqx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gt2cvwzrxby.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gt2bbopekms.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pengpengdd.cyou/Article/details/gt2asynvggz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gt2werjriby.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gt2sfeiicup.html

Go:   // 手写 map[string][]T
来源：http://dali.ybcxt.top/Article/details/gt2zwdpvzyh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gt2zkbiftol.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gt2jcacjpvp.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2uxzkjcyb.html

Py:   Counter(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2citxscrd.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gt2osuikcmh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gt2zxlepcot.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gt2wlothzpf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.svipenyu.cn/Article/details/gt2whusxqug.html

Go:   // 手写 map[T]int
来源：http://dali.aizwys.cn/Article/details/gt2iepygteu.html

Ruby: arr.tally
来源：http://dali.shzxlz.cn/Article/details/gt2cutoudbv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gt2yapiwtbn.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gt2gnivlmik.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gt2yxgqkmyz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gt2qrhfhqbf.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2zdruyqrd.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2swgzfauo.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2tognvyyg.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbnxxoqx.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gt2ciigfjvx.html

C#:   list.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gt2fxzxcglu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gt2widvuhkh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gt2bbnapzdo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gt2xhbpskgs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2vqbhwxoc.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gt2avkxecbs.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctolrpmz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.havefunace.top/Article/details/gt2moqlfzwh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.iojbl.cn/Article/details/gt2fgwssjyq.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gt2flvytvxh.html

[D23] reduce 累积计算
来源：http://dali.jqgufenzy.top/Article/details/gt2cnqepvlk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xinyue.icu/Article/details/gt2knjbrslj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hylkfhpj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2bxrmngwq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gt2lqencsoo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenzaomai.com/Article/details/gt2vwjroiba.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gt2glrvqewr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gt2xdhqdjxu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gt2vfbdgwcn.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gt2ojyajwjq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gt2kkwflvrd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gt2rskmkslw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daxiang520.top/Article/details/gt2fhtfqgvn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2rudkktqw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hammf.cn/Article/details/gt2xrrypkiq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hongshengwenyu.top/Article/details/gt2keuirflj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.9152youxi.cn/Article/details/gt2ojwlysax.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sysykeji.top/Article/details/gt2iojhjvde.html

[D25] Set 集合去重与交并差
来源：http://dali.haohaochexian.top/Article/details/gt2zntolqzl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgfzy.top/Article/details/gt2gujjbmsk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gt2avkpisyy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxzkqhpc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2astkxkci.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gt2jilquyrz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jlsjyb.cn/Article/details/gt2wupdnjdl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypdntcqh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gt2myhypelr.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gt2hxopyvls.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gt2sgddmehx.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gt2sqacmrcp.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pamyxmxo.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2frnqmpwv.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmlhabev.html

Go:   strings.Join(strs, ", ")
来源：http://dali.snrcjt.cn/Article/details/gt2iebvejqk.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gt2eseoyzvr.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gt2wxxhderl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2nnjygvbz.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2kguxkmlg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2oinfxoss.html

[E01] 拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gt2ikcrkvvl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhixingplan.top/Article/details/gt2rtutbzoi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxinkj.top/Article/details/gt2uxtpnulo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gt2pyqhdecz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gt2viwdbmuk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258.top/Article/details/gt2upzqqhcr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gt2kpxnqenl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fzhhl.top/Article/details/gt2qbdtfiag.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2kvhcdtdz.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ornhfonr.html

Py:   "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gt2bfzfwevs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gt2xhimvcpn.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkaniwhc.html

TS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwyhzvvi.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2hmmmjenk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dufpwjjd.html

Ruby: "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gt2lxchrrbw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hammf.cn/Article/details/gt2yjbzgwyy.html

[E03] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gt2hkcagxqb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvgtqaau.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2rvvopmpw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2abyccrxk.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2kqjwvums.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2sxdnbsta.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gt2vrhpkkav.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkjimtav.html

C#:   s.Substring(1, 3)
来源：http://dali.shzxlz.cn/Article/details/gt2cazvzkxi.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gt2wabcbxvt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwlvjfll.html

PHP:  strpos($s, "x");
来源：http://dali.jianghu66.top/Article/details/gt2flhmkdca.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gt2yksqugej.html

TS:   s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gt2kttjjrdh.html

Java: s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gt2vrudxgcl.html

Go:   strings.Index(s, "x")
来源：http://dali.pycfn.com/Article/details/gt2jvrmygpi.html

Ruby: s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gt2vgyuduhd.html

C#:   s.IndexOf("x")
来源：http://dali.fengsongda.top/Article/details/gt2evxjvhnj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sxryk.cn/Article/details/gt2fgnjoram.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gt2iyikwupi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gt2qchqples.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2stgwheod.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gt2qykasrva.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2hrwfdcrc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gt2elaywbzr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gt2oqcnzjyp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hspdrdlv.html

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gt2znfwbbvk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gt2oeepkcmo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoumhzc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2wseonkso.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2tpyqvnfc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldgvrbyk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gt2tphlmpxu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2qxjsywgd.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2txrafpsu.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gt2gylaghhn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.mhx1999.top/Article/details/gt2pyqjouxv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgwgbkeu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.mhx1999.top/Article/details/gt2szyzvhmb.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqiiuulv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.birdmap.top/Article/details/gt2doigatkb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sweek.top/Article/details/gt2bvluspsg.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gt2ppghxjov.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oaikqicc.html

[E08] 数组按分隔符合并
来源：http://dali.jianghu66.top/Article/details/gt2tvpqiruz.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gt2wubqmhdw.html

PHP:  implode(",", $items);
来源：http://dali.mhx1999.top/Article/details/gt2vfeqwfvr.html

JS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2inklrxgr.html

TS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxvqjwjk.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gt2vkpapinx.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gt2nfaobrux.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2ypmytlid.html

C#:   string.Join(",", items)
来源：http://dali.pycfn.com/Article/details/gt2thxyuuyx.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucbpxteu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gt2iyscxflm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fzhhl.top/Article/details/gt2cpbxdfyv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gt2yudjpipv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gt2ewqcwvvv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2zpnskbia.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhongyouzk.top/Article/details/gt2ejciilyn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.iojbl.cn/Article/details/gt2rnnebixl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gt2wftrhajb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gt2jnpsrupa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2dfrbtdtq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigfzy.top/Article/details/gt2gocbfjbv.html

JS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gt2ejciqnze.html

TS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2sixdpcjt.html

Java: String.format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2cuolzerj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gt2cjrupeoo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gt2vaevfrae.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gt2vsoianga.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gt2lnghjkxs.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2zobxsfdg.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gt2uadjstwv.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2jgtlgpwu.html

TS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yjhcpqid.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnqzz.top/Article/details/gt2qwjimisu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gt2fdpohznj.html

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gt2nmvjihox.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gt2dgsbumja.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gt2lwoyimwn.html

Py:   s.count("a")
来源：http://dali.cashguo.top/Article/details/gt2jcxxekoh.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gt2gxgxxbpn.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2grndrgsr.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gt2mmihakgd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gt2wivqiung.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gt2uypmuibd.html

Ruby: s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2dqyqhxom.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgfzy.top/Article/details/gt2ifgmejfi.html

[E13] 逐字符遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxvpcstu.html

Py:   for ch in s: print(ch)
来源：http://dali.daria6918.cn/Article/details/gt2jbadodml.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gt2qtpvwopp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2ndkabgah.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2hpyvtdbf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2ikitmcki.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gt2jytgexhd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvkrzlw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2pvqvdadd.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gt2vnemqhpx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gt2txasobcw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gt2fapajusl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gt2ubpxorlz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gt2wfgqscwh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcywnpae.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gt2kndfabbr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gt2vzmyacte.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gt2blbwjfgk.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gt2jwcssocc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gt2wyaprsxz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tbpgjykw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gt2eiltylgm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tianlin.xyz/Article/details/gt2hkexdumx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gt2uxpyruvg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gt2zvebrsbw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guannengcc.top/Article/details/gt2xjwmuadf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gt2jhxtqnsw.html

[E16] 数字千分位
来源：http://dali.bjfxy.top/Article/details/gt2reiezdet.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2rnzkmtmp.html

PHP:  number_format(1234567);
来源：http://dali.yvedp.cn/Article/details/gt2njdngpqt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gt2vjrrtkez.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gt2xafucjna.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cheryme.top/Article/details/gt2knjknzzk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gt2hkxvssii.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuanzx.com/Article/details/gt2auibjaqt.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgufenzy.top/Article/details/gt2uhvgtrsg.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gt2ilxsmqiq.html


<!-- 参考信息 -->