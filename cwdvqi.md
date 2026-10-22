代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jcegwkvf.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2dhgorggu.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2cswvcapa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.birdmap.top/Article/details/gt2gehxvwoj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gt2fctkacow.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gt2oznbvdob.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gt2zlxqezmh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jysjyiyn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhoulong.xyz/Article/details/gt2ogvbudky.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gt2nriasrqq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gt2gspyxvht.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenlongwang.top/Article/details/gt2jgrsihaj.html

[D11] 反转数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpvxzzpg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gaohongyu789.top/Article/details/gt2zftfjgjf.html

PHP:  array_reverse($arr);
来源：http://dali.yongpay.top/Article/details/gt2vdcpxmuc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gt2iquyppcm.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gt2sfulvhpd.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gt2xinzyvxz.html

Go:   slices.Reverse(arr)
来源：http://dali.pycfn.com/Article/details/gt2mxhaxcqu.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyrywcn.html

C#:   list.Reverse();
来源：http://dali.yonumen.top/Article/details/gt2fwikkikq.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gt2cfatgics.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gt2hzxkqerm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gt2nihwsmnc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2fushgnlg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gt2mjszvtlf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qewkhbyg.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2bvrjgvou.html

Ruby: arr.index(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2fsduxosx.html

C#:   list.IndexOf(x);
来源：http://dali.quarkkingdee.top/Article/details/gt2odetvwsl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.birdmap.top/Article/details/gt2wdrzrjnq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.andypj.xyz/Article/details/gt2fyooawvb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2jxhtazuh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gt2tcvscxwx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gt2puduwrxw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2ucoprgdg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.c1oappe.top/Article/details/gt2qfukwqee.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gt2zngvovua.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2jeyyyzlr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyzvwosp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.316326.xyz/Article/details/gt2ctihdalk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2nvtxkwld.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2nfidkbnz.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gt2ekkwxvrr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gt2gzviwcuf.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gt2sezohsdz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2luusbycs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2nlexswqp.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gt2gpiwwyoj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gt2cchycklv.html

PHP:  array_unique($arr);
来源：http://dali.xylfe.cn/Article/details/gt2kzuxfbls.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gt2ztyomnha.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2echubygg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gt2vlwyttwz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsgqfgbt.html

Ruby: arr.uniq
来源：http://dali.gaohongyu789.top/Article/details/gt2trlqhfuj.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tuxzrifs.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gt2ouaycfek.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2xkpueheu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkamehgy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2xapoyjwb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gt2bpsvzhgo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yangfankeji.com/Article/details/gt2xxjpouib.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gt2mshzmrjg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gt2iolwsnhi.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gt2fbdnhmrf.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gt2mhjfhxvb.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2krstlzff.html

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jgqacwyd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2ldzdhvlg.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gt2ddwqoggr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yonumen.top/Article/details/gt2lcupedvy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2ssogrfyc.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gt2rkhnxura.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gt2ubyakkjv.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gt2wlppjgrb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gt2ppircyzf.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gt2bzdeamgg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gt2debwounc.html

TS:   nested.flat();
来源：http://dali.pycfn.com/Article/details/gt2djlfqvcy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2kknfltvs.html

Go:   // 手写双层循环
来源：http://dali.ehwqpu.com/Article/details/gt2afelusnn.html

Ruby: nested.flatten
来源：http://dali.zhoulong.xyz/Article/details/gt2rvqgafrh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gt2cmaeflhn.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gt2licfnaki.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gt2nrpbzaks.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gt2bgnjsuqi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sysykeji.top/Article/details/gt2wwptgswm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gt2wfubxmdu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shzxlz.cn/Article/details/gt2gllprjpa.html

Go:   // 手写 map[string][]T
来源：http://dali.zhiwuduotai.top/Article/details/gt2qybxdpix.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gt2spsrmrgp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhoulong.xyz/Article/details/gt2hyjbxthr.html

[D20] 统计每个元素出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxlvgzyq.html

Py:   Counter(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2dzfurkbh.html

PHP:  array_count_values($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2eweynydd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gt2rnbuocem.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvtcyetw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ppjwa.cn/Article/details/gt2xpdyzmcj.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gt2ymavnaqc.html

Ruby: arr.tally
来源：http://dali.daria6918.cn/Article/details/gt2sztxwmny.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gt2jpsrbwyt.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpjdkqnx.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gt2hftzcxuw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asoubjgb.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2swuvbkpx.html

TS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gt2pixikqke.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2evzhwaay.html

Go:   slices.Contains(arr, x)
来源：http://dali.sweek.top/Article/details/gt2ebhdwdel.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qkwalyzh.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2cjpanijz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pycfn.com/Article/details/gt2swsfgeyf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2pivoogaa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gt2eiexkoli.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gt2nhtsdlca.html

TS:   [...arr];
来源：http://dali.zhiwuduotai.top/Article/details/gt2ayegayjd.html

Java: new ArrayList<>(list);
来源：http://dali.gotoacloud.top/Article/details/gt2gldjvluf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.redwolf501.top/Article/details/gt2bipbksdp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gt2yfzxzfed.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gt2fkqudsls.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gt2ouasivsf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oeoccmgk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2jqyttkqx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2jymaxzfq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2sbdlfzyk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gt2onsgqbdd.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gt2pqtslhzq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fengsongda.top/Article/details/gt2epbsmojy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gt2fdbqheds.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2iibshgmk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.iojbl.cn/Article/details/gt2ouocrsld.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gt2rdmkafve.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gt2biiptsdz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2heszwtii.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gt2bjhetgky.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prcktvgz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yueranfly.top/Article/details/gt2xygncxex.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gt2qxbefglt.html

[D25] Set 集合去重与交并差
来源：http://dali.pengpengdd.cyou/Article/details/gt2tcndcvrt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gt2cmvgrvrj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gt2xjhzyhwc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gt2jugpvvqb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2houaoqys.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2yehlfdyg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzmszdsv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnqzz.top/Article/details/gt2vdczlsna.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2epylvwpp.html

[D26] 数组转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzwuhdyz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2sgisquai.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gt2frollpez.html

JS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gt2gusndzms.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2jifpaaiz.html

Java: String.join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gt2vcrszxwn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gt2knamxisz.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gt2szriagsb.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2qplzrhgi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2dkvsymcl.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gt2lvjxmgmv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ceigsgxg.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2dzdqpbrz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gt2girzqgxo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2modtmfzk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfzbhkbj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gt2ocaoefrp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2zokfifyv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnqzz.top/Article/details/gt2gabevazi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gt2estrudxw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukyccxfo.html

[E02] 重复字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2simwcmoy.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gt2srpiyudz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.mhx1999.top/Article/details/gt2hnhymnmv.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dyulzrcn.html

TS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gt2kawilooa.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2qcridghn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yvedp.cn/Article/details/gt2govhdlqi.html

Ruby: "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gt2yarmualg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gt2uvurufrs.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gt2tgwbtenj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2qutpunkz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2gfdyhhtj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2qfurgiop.html

TS:   s.slice(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvzbhckg.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2xgwxxsga.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gt2hgeqwowp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guowangkeji.top/Article/details/gt2hvicpeki.html

C#:   s.Substring(1, 3)
来源：http://dali.sysykeji.top/Article/details/gt2ngwbnwhu.html

[E04] 查找子串位置
来源：http://dali.redwolf501.top/Article/details/gt2ogjpqori.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuanzx.com/Article/details/gt2ywyjwegw.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gt2gvtprzzs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cashguo.top/Article/details/gt2skfpsydp.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyskxsu.html

Java: s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gt2rrjmdqzf.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgfzy.top/Article/details/gt2icxtkene.html

Ruby: s.index("x")
来源：http://dali.xuanzx.com/Article/details/gt2zqrvdkla.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2ktpkryjg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jlsjyb.cn/Article/details/gt2vyateegm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2kuwziujk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daria6918.cn/Article/details/gt2yfbbxunp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2yigxegli.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mencawkj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujdgvgba.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gt2xxojvkcz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gt2whprglxl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tanke756.top/Article/details/gt2skhmidnv.html

[E06] 替换子串
来源：http://dali.hnqzz.top/Article/details/gt2qtzodpzs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2airaopjb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cucudq.cn/Article/details/gt2yujgvpma.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2ccvarpmt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2qnzrhyei.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2utumsdyz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gt2yocthvex.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgqkjcm.html

C#:   s.Replace("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uchuglcu.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gt2jggpyukl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gt2xdrqkuqf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2mqstctub.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gt2jldzkrmt.html

TS:   s.split(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2bcjpwzpo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258888.top/Article/details/gt2tghuuxgp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daxiang520.top/Article/details/gt2psonfiaj.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gt2npufuoxy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ivvv.top/Article/details/gt2uznbvxru.html

[E08] 数组按分隔符合并
来源：http://dali.hysaishi.cn/Article/details/gt2cqknpqfx.html

Py:   ",".join(items)
来源：http://dali.tianlin.xyz/Article/details/gt2dwhxhvok.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gt2dtsvuyux.html

JS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gt2sialgbzd.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gt2xtyeneti.html

Java: String.join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gt2tpiktvee.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gt2ezhvrwgj.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2agsnevcx.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gt2sdtslhfx.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gt2epfvookn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gt2qtrspnoe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2qqwancvg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2tzgnxqsb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsmspknl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2omoteyjm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gt2quxparkb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gt2yhbonobw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.316326.xyz/Article/details/gt2vkxvgniq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gt2vzqrfyyb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2bcvtskhp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gt2bwcfighs.html

JS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gt2hponaubh.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2jajvhqcp.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2gluyxciq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gt2agilpvwt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2fatcccja.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pengpengdd.cyou/Article/details/gt2dznkzxpr.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gt2sbxhxqgw.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2gjvoaouo.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gt2oikjedbc.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2cgsimpkc.html

TS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2waopjyip.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gt2ccaxixdx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gt2nbemgpqb.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2uebnrfta.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gt2snbqqgeh.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2fusillgo.html

Py:   s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2ewegfuhd.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gt2nvesisef.html

JS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gt2fvvpxetb.html

TS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gt2wmetrmuu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tian-w.cn/Article/details/gt2blohkotn.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gt2jlqxymtu.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gt2xaxxwtaa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gt2bxrkjwem.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gt2ykbiojzj.html

Py:   for ch in s: print(ch)
来源：http://dali.9152youxi.cn/Article/details/gt2nykmmcvl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnxiangtu.top/Article/details/gt2veytjajl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2grjjlkuh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2pfshnuim.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2maebtotw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gt2wgysijyi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gt2bsyesvtv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2rlvswccj.html

[E14] URL 编码与 Base64
来源：http://dali.yangfankeji.com/Article/details/gt2dmnuwjsg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.316326.xyz/Article/details/gt2pxxofpsj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2bqqsuejp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gt2guuxqsvm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2cwsjtbmq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2qlqskqah.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gt2jfxwxome.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gt2jweptvxp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2mezfbndv.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gt2tqqlobkm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2wpsfdgpu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2prghdkas.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gt2wrcuxkdj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyrmahh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gt2noshcuyd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.svipenyu.cn/Article/details/gt2kotflsss.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenzaomai.com/Article/details/gt2lhhigjrh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenzaomai.com/Article/details/gt2ehkhzeyy.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gt2ozoqvail.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gt2gskxmcdt.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gt2myctgtpx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gt2knvfyurx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gt2jweaojtm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gt2mnhrzmhc.html


<!-- 参考信息 -->