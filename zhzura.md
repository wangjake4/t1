代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gt2fdzfvmlt.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwzwoqzh.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gt2sbpupouw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gt2bdxrlbhf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppdcntpi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gt2joaisyjm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gt2srzshgyp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvytmieq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gt2mystkrfo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.9152youxi.cn/Article/details/gt2ybddfjhi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gt2gnanziel.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenzaomai.com/Article/details/gt2sstmxcfp.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gt2zvynptis.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tian-w.cn/Article/details/gt2vzoemhvc.html

PHP:  array_reverse($arr);
来源：http://dali.nwbrower.top/Article/details/gt2whjlqayw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuxming.cn/Article/details/gt2yuytbgom.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gt2qhhcbilu.html

Java: Collections.reverse(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2ievxrwur.html

Go:   slices.Reverse(arr)
来源：http://dali.yuxming.cn/Article/details/gt2zavomudv.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twnbjkxf.html

C#:   list.Reverse();
来源：http://dali.birdmap.top/Article/details/gt2cpmoznbb.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gt2aaapncjb.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2aijrasbn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2dupzabxd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gt2fnknrdvd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gt2irhjglrg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gt2dognofnh.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2govmkzcq.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gt2wgwxlrqb.html

C#:   list.IndexOf(x);
来源：http://dali.jyoumei.cn/Article/details/gt2omwcgqts.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gt2mfytiizs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2jjotjdjw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gt2qrlastpq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2ivunerzz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2elnvjtlf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yvedp.cn/Article/details/gt2hcavcbem.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guowangkeji.top/Article/details/gt2qfxrktui.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbrtlavb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dkietval.html

[D14] 映射转换（每个元素变形）
来源：http://dali.c1oappe.top/Article/details/gt2sybusahm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jivkpoam.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.iojbl.cn/Article/details/gt2jfzzzzyd.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gt2kxvexzws.html

TS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2mqofrgsf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.svipenyu.cn/Article/details/gt2rlwrwnvk.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2qalqrqpj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2sngmkoby.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2itpxwgcn.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gt2resgxbto.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gt2lpewkoji.html

PHP:  array_unique($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2wmaalbwc.html

JS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gt2knpiafwt.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgfantms.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gt2hcyrykel.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhongyouzk.top/Article/details/gt2wmkwdvks.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gt2skirepdp.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hranopgd.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gt2zosapkbo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2humkibab.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.iojbl.cn/Article/details/gt2pibfpksm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2cbbjvuxm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2xptwtfnv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.bjfxy.top/Article/details/gt2clhyirfc.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gt2wehjfsda.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhaoxvsb.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnqzz.top/Article/details/gt2txjqapur.html

[D17] 最大值与最小值
来源：http://dali.redwolf501.top/Article/details/gt2hyxkwaqg.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2lqeyztce.html

PHP:  max($arr);  min($arr);
来源：http://dali.cucudq.cn/Article/details/gt2glkeagmg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gt2piucultr.html

TS:   Math.max(...arr);
来源：http://dali.yvedp.cn/Article/details/gt2xsbczqhi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gt2wbjmodiy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cashguo.top/Article/details/gt2evsqklvf.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gt2ksfofgwx.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gt2wwedyglg.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gt2uqtagjkb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhxkutuq.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2euzxkvlz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gt2ngouetxa.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gt2mfficmgi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jianghu66.top/Article/details/gt2ttbljdxf.html

Go:   // 手写双层循环
来源：http://dali.jqgufenzy.top/Article/details/gt2bpfmowbf.html

Ruby: nested.flatten
来源：http://dali.hnxiangtu.top/Article/details/gt2oxqwjxsf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2lidvofzw.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gt2txsaqaak.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gt2rxiffvtu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gt2ifbxhylw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gt2azdgafsi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjalvwhl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gt2inaktoqu.html

Go:   // 手写 map[string][]T
来源：http://dali.yuxming.cn/Article/details/gt2kvohuenk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dashuyun.cn/Article/details/gt2tchaeqzo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnxiangtu.top/Article/details/gt2eyxlrmxc.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2ofuotzsp.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gt2tehwlwji.html

PHP:  array_count_values($arr);
来源：http://dali.sysykeji.top/Article/details/gt2xdznuqbu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gt2ysqkgnux.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gt2jborsslc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gt2rsbvadse.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gt2eatrmphr.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gt2nkrczidm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.316326.xyz/Article/details/gt2lnxytwxl.html

[D21] 判断是否包含某元素
来源：http://dali.nanxuanxn.top/Article/details/gt2sybslmul.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gt2cowszcrx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fengsongda.top/Article/details/gt2nfvystjg.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtzyhit.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2nehwnzga.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gt2udpyyxmm.html

Go:   slices.Contains(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2dzsngqlr.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gt2bertwwyz.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2guuwicrs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yanxiufei.cn/Article/details/gt2sjirdyme.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2oloyqcyb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gt2hukbovbd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2sfooinxo.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gt2dntywazy.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gt2gygqddfn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guowangkeji.top/Article/details/gt2tkdqnbpu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gt2qkzhdisf.html

C#:   new List<int>(list);
来源：http://dali.yangfankeji.com/Article/details/gt2pvgixylm.html

[D23] reduce 累积计算
来源：http://dali.jinqigufen.top/Article/details/gt2flgebudf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gt2wrbgdbhl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ydzc1.top/Article/details/gt2htvbulwl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gt2ghwnypvo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uirefjbz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.redwolf501.top/Article/details/gt2chcfosvm.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gt2lidtqxvq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gt2tovfhwpu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fzhhl.top/Article/details/gt2vzsyixpr.html

[D24] 字典 / Map 基本操作
来源：http://dali.quarkkingdee.top/Article/details/gt2wnzfygyq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2caacvysb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gt2oiriqxpn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ucdjrvus.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2tkqlylwy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gt2ruyjmzrr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gt2uxhwkzpy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2lclyznyp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daxiang520.top/Article/details/gt2dlsrjkgs.html

[D25] Set 集合去重与交并差
来源：http://dali.haohaochexian.top/Article/details/gt2krijdpnt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gt2gpfxbltp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenzaomai.com/Article/details/gt2mnbvrlja.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dianchejie.cn/Article/details/gt2zmfvifht.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ybcxt.top/Article/details/gt2dphgkyql.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dashuyun.cn/Article/details/gt2ygpfcxbr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gt2repjbbrc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gt2cgjthyzc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangdashe.top/Article/details/gt2exybsgta.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2dmruqwrf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guowangkeji.top/Article/details/gt2yjbjvnnn.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2xjhmmwxb.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvgbfvqm.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zamtmdzn.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gt2wwmpojob.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gt2hggssguj.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2ktcxiuqm.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gt2norotxem.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2wjhfbrzp.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gt2oslovcom.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2vsvtaqzd.html

[E01] 拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gt2xgqmqsiq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gt2iphxhzhy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gt2arrhrkvy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gt2jectiink.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gt2uqdxeija.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybzfjnst.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gt2vxzyptxz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gt2pmnbxsek.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eedcdpsv.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssvrcwtm.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdhyozxs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gt2kyvzastx.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtcvohf.html

TS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gt2sveadgzw.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2aziuvcdx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkixzflx.html

Ruby: "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gt2ukabckon.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhiwuduotai.top/Article/details/gt2lnohxbep.html

[E03] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gt2uqzdybjk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yangfankeji.com/Article/details/gt2mobxmpzz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2xjzhprdg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gt2fcenabet.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2affocjcm.html

Java: s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gt2lwdnnxzg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigufen.top/Article/details/gt2ciovqyur.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tian-w.cn/Article/details/gt2zbhbzziw.html

C#:   s.Substring(1, 3)
来源：http://dali.jyoumei.cn/Article/details/gt2ompronye.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gt2ygwtfege.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cucudq.cn/Article/details/gt2qnvnidaf.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gt2aziyjvnt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jlsjyb.cn/Article/details/gt2vcjkkpwu.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gt2rjvavoec.html

Java: s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gt2hdzisjmr.html

Go:   strings.Index(s, "x")
来源：http://dali.smart0.xyz/Article/details/gt2ctafddjg.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gt2wjhofwxn.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2smnnmxve.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fzhhl.top/Article/details/gt2eusvizrj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2niicimkh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gt2nlldautv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mieabxxy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gt2qxgbxqzs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2sbnojjvf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenlongwang.top/Article/details/gt2bffcsrsm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skzlhkgt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daria6918.cn/Article/details/gt2hekvpttc.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gt2dovufwqg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gt2tpsmrdjs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gt2duwtfget.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2zgmazizg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2vqlkbllk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2qgwuhlrs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gt2mymqzsky.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2lrghafms.html

C#:   s.Replace("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2sgecabcw.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2fihsonxi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gt2dfilmuwk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2zezkhnzq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2immaqnab.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gt2zyfjgxth.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gt2wmvqzqtl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cdnleiting.top/Article/details/gt2joxqggal.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gt2eitgfnlz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gt2tjemipxz.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gt2zgatqgxy.html

Py:   ",".join(items)
来源：http://dali.iojbl.cn/Article/details/gt2rixrthuu.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gt2ptfqiuqo.html

JS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gt2mbthxyjb.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gt2mlcyxzjx.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtrqkkgj.html

Go:   strings.Join(items, ",")
来源：http://dali.xylfe.cn/Article/details/gt2mwddkfly.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gt2vhfcdiof.html

C#:   string.Join(",", items)
来源：http://dali.yvedp.cn/Article/details/gt2gtsxhgvr.html

[E09] 去除所有空白字符
来源：http://dali.hammf.cn/Article/details/gt2ovjzoolj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gt2nnkgqmbb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yueranfly.top/Article/details/gt2pfkublaz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gt2lxdwcltu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gt2vapkkcwy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuanzx.com/Article/details/gt2qyqqqgmx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ukbvdvwz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2erfwoqxh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gt2ishtrhze.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cdnleiting.top/Article/details/gt2icofqsit.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2kcpnxcdj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hysaishi.cn/Article/details/gt2jjvzjiiz.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2lwfljayq.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gt2edlpyzwv.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2lbdaqykd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2xuetwjvx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2eahtgkly.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xinyue.icu/Article/details/gt2jarglcvw.html

[E11] 反转字符串
来源：http://dali.xuanzx.com/Article/details/gt2ibjrbbco.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gt2tnnavixr.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gt2vdekrvzm.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2zyrvhrls.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2ajacynfd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2nouhoxvo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gt2yshiihbo.html

Ruby: s.reverse
来源：http://dali.xinyue.icu/Article/details/gt2belocfgx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gt2hdhgiuok.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gt2ljlmmykz.html

Py:   s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2csjxwscl.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gt2ocgpbhft.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gt2vptcokiu.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gt2alpryvfp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgsovrvo.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2folmqmys.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfnlepty.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gt2owypnquj.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gt2krjomusq.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gt2brckntgb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gt2upasfclh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2eorflheb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gt2dcbsmlad.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2xuocryeb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gt2dzfdahox.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gt2zgfxpork.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2oktjlkcf.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gt2bzjyxynh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shuidangran.top/Article/details/gt2aowldqsj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2vxraxtqu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqzxdhsy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cuhzowpf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jyoumei.cn/Article/details/gt2suiibpck.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gt2vklimzjh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gt2lukbqapq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.snrcjt.cn/Article/details/gt2lkhnzgpz.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbcyqpfv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gt2xzzwwuea.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gt2ujpluznw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gt2wleolvyt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gt2nznyjrnz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gt2klgbdsvx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lajysghv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.redwolf501.top/Article/details/gt2ugszaxgx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gt2ogboevwb.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfslcfxb.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gt2exhfkefm.html

PHP:  number_format(1234567);
来源：http://dali.cdnleiting.top/Article/details/gt2vpzfghfj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2gcxkfmda.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gt2gotpujcq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gt2avzgwwaz.html


<!-- 参考信息 -->