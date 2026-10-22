代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gt2gkryrozg.html

TS:   [...a, ...b];
来源：http://dali.andypj.xyz/Article/details/gt2csiilfst.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gt2ujziuvds.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gt2fzgcnqbr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ppjwa.cn/Article/details/gt2mkowkqea.html

C#:   a.Concat(b).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2zmxteeah.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nydwmvei.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gt2tkbzxjji.html

PHP:  sort($arr);
来源：http://dali.xylfe.cn/Article/details/gt2yuedwikx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fzhhl.top/Article/details/gt2shdncaxq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gzhubu.top/Article/details/gt2uczmyjxc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.vqdsnc.cn/Article/details/gt2zwarkhtl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2adwamzvy.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gt2wszmwtku.html

C#:   list.Sort();
来源：http://dali.andypj.xyz/Article/details/gt2ztridheq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.smart0.xyz/Article/details/gt2whrzcxgf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xziqi.cn/Article/details/gt2zumyhcvg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2fmknismj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gt2iquchhia.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gt2tcclqtqe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gt2swhlupsh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hfpthk.cn/Article/details/gt2qbzqaxbp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hfpthk.cn/Article/details/gt2jwejidae.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gt2oizpmqtj.html

[D11] 反转数组
来源：http://dali.haohaochexian.top/Article/details/gt2nqchpdnf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gt2zgyzefnv.html

PHP:  array_reverse($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2hszhtwli.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gt2drvhrwrw.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gt2ncjfloam.html

Java: Collections.reverse(list);
来源：http://dali.chenlongwang.top/Article/details/gt2zgpqjzli.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2fjzozdai.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gt2rtsyrjss.html

C#:   list.Reverse();
来源：http://dali.zhongyouzk.top/Article/details/gt2ksswbzbb.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbpdwze.html

Py:   arr.index(x);  x in arr
来源：http://dali.jlsjyb.cn/Article/details/gt2mxumzhef.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ksrfrcgj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gt2drdmcdli.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2gvlgkssb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gt2vblqvqqx.html

Go:   slices.Index(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2xpunylzr.html

Ruby: arr.index(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xuoavgfd.html

C#:   list.IndexOf(x);
来源：http://dali.guowangkeji.top/Article/details/gt2qxkhwtuz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jyoumei.cn/Article/details/gt2snexrayp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gt2vnvtyyic.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2vtqewyjk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nggxszqf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gt2qowjkhjv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shuidangran.top/Article/details/gt2gjngtmqx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zycfv.cn/Article/details/gt2zlnicnnk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gt2eksxrktc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2wvcjvkky.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gt2gtnsjhsf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2ecjbdffd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2buhwoujy.html

JS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gt2xgdhagmb.html

TS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2bzjleojb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gt2kgthcnmw.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gt2mvsivheh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2yezkfawb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2cyxbqrga.html

[D15] 去重
来源：http://dali.xinyue.icu/Article/details/gt2nmivtuyq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hilzkpid.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2efwkssdr.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gt2iliyrgqh.html

TS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gt2nqelohqf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuwpmwux.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cashguo.top/Article/details/gt2leugduih.html

Ruby: arr.uniq
来源：http://dali.gotoacloud.top/Article/details/gt2zrpsffxo.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gt2xtqhxbtu.html

[D16] 求和与平均值
来源：http://dali.birdmap.top/Article/details/gt2dswbwcrp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gt2rljqthpj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2mhyajjom.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gt2ljcnicch.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gt2ypvibemq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigfzy.top/Article/details/gt2ezytrtcm.html

Go:   // 手写循环累加
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftpdvyxp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gt2prjxwoho.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gt2sgqvrlpa.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gt2vcatramo.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2tvpngpar.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gt2lafpxjqa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gt2mmyznliv.html

TS:   Math.max(...arr);
来源：http://dali.jinqigufen.top/Article/details/gt2uksfsztu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gt2tryovrud.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gt2pcvdwswe.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gt2orljjrav.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gt2izzjbdhp.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258888.top/Article/details/gt2hdtzjkgw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.havefunace.top/Article/details/gt2climnjhh.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gt2zvicfoln.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guannengcc.top/Article/details/gt2owtpohlz.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gt2xtqkjlgw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gt2acbyzcfs.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gt2yezfcaid.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gt2anhsdiyd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2cgibxhnu.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gt2heeevehd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2ylkbqgpo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgfzy.top/Article/details/gt2oczfcmsb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gt2txxaycul.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2rijumptt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gt2duzeqamq.html

Go:   // 手写 map[string][]T
来源：http://dali.andypj.xyz/Article/details/gt2szemwhgj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sysykeji.top/Article/details/gt2xsxmvqss.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gt2sklkxcmf.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gt2oykwclqi.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gt2tikdfovu.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2csvyumjh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gt2jvpfjihm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gt2pgwkmgqc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gt2ebgdaeum.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gt2iqlleiij.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gt2iuongurx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gt2jhaupndo.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjtazdmt.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gt2vedijjkr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gt2pewpkjbd.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2pqxxgesc.html

TS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gt2urykbdty.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2vtblmkib.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2vamzctww.html

Ruby: arr.include?(x)
来源：http://dali.cdnleiting.top/Article/details/gt2fmzffllu.html

C#:   list.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2qcanuaon.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhbfklzs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gt2cnvecpca.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gt2woudstbe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfbsurzf.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gt2rlfrcvyk.html

Java: new ArrayList<>(list);
来源：http://dali.dashuyun.cn/Article/details/gt2kkohwrai.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gt2yixukxfu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gt2gnxlciix.html

C#:   new List<int>(list);
来源：http://dali.xuanzx.com/Article/details/gt2ewrnilmr.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gt2fncqfyha.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2nqczcwgo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gt2nvihzsdw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwgqmhx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gt2itblqyue.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj202588.top/Article/details/gt2enucznfa.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gt2rdvsughe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gt2ryoalzgi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gt2irfufhqk.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuxming.cn/Article/details/gt2ydszptrq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gt2bhqmxxxa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gt2tpniolwu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jianghu66.top/Article/details/gt2vnqdldyf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2qlmdpcov.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gt2vgucppfb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.birdmap.top/Article/details/gt2tckyoluz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2bsfukycu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shzxlz.cn/Article/details/gt2kigsvori.html

[D25] Set 集合去重与交并差
来源：http://dali.jiagoushi.top/Article/details/gt2dfxvkwmn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gt2fxjuqxwd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cppycqth.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gt2swajnmbo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gt2pluzolol.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gt2ruqjdaph.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gt2nqtnkvsq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpkbdktx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yonumen.top/Article/details/gt2gnppmqbf.html

[D26] 数组转字符串
来源：http://dali.daxiang520.top/Article/details/gt2pfrjitbs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qposlmmj.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gt2qudnlciq.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2elstsgvj.html

TS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gt2pnivtuyf.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gt2pfnyrjct.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gt2bkzvrvcx.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2jkkxaivh.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gt2hnzkpksx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2fwtgggvt.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gt2utuzaxze.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ldqbnong.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2rxthbghd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gt2snctaijp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.316326.xyz/Article/details/gt2kydmxtgf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yxxwlchr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gt2ohhrqxzl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gt2agdbvzfq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.havefunace.top/Article/details/gt2cfnpbosf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.smart0.xyz/Article/details/gt2nxnbqgff.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2fyznsnef.html

[E02] 重复字符串
来源：http://dali.yj20258.top/Article/details/gt2aurqbekb.html

Py:   "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gt2nuopjonl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2adrzoiue.html

JS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2khegsxdf.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2zujalsvi.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2xsjhfhbz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhengqikj.top/Article/details/gt2pnpuzexi.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gt2wcdynumh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elstlwin.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gt2nfsicait.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gt2fghcymed.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2lvoqvivm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2rbdwxgci.html

TS:   s.slice(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2sdfqxakn.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2bwlibkxd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigufen.top/Article/details/gt2ucyyjpyc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgfzy.top/Article/details/gt2hkabxdqt.html

C#:   s.Substring(1, 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2mhigrhrs.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gt2eejugnth.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2pqbqcmih.html

PHP:  strpos($s, "x");
来源：http://dali.jianghu66.top/Article/details/gt2fjjkqglj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cucudq.cn/Article/details/gt2nsgpsexg.html

TS:   s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gt2qnifjszq.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2mwhalnge.html

Go:   strings.Index(s, "x")
来源：http://dali.bjfxy.top/Article/details/gt2tcevilaj.html

Ruby: s.index("x")
来源：http://dali.andypj.xyz/Article/details/gt2ruqadaua.html

C#:   s.IndexOf("x")
来源：http://dali.xziqi.cn/Article/details/gt2hgkvowms.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuanzx.com/Article/details/gt2yrdrcpne.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2auzjnvla.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yueranfly.top/Article/details/gt2qfwvlvio.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2ngugapcv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gt2xjabxxvs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2uzhhjrkn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gt2tkobadku.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ybcxt.top/Article/details/gt2zhnepeys.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmjvdfsk.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gt2sxusnoqs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2kgfields.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2mdodjmze.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2scjkosuq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjfsamco.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2ewonofkc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gt2evgvdpyk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2hkahqisi.html

C#:   s.Replace("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2brolfolz.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gt2wnujivow.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cdnleiting.top/Article/details/gt2qbrltexr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftsppilt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gt2gjvoiylv.html

TS:   s.split(",")
来源：http://dali.sxryk.cn/Article/details/gt2eeqzyuea.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.meibo888.top/Article/details/gt2gqbqolao.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urvmjhmt.html

Ruby: s.split(",");  s.split
来源：http://dali.ybcxt.top/Article/details/gt2mnmohacx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gt2zeskhycl.html

[E08] 数组按分隔符合并
来源：http://dali.fengsongda.top/Article/details/gt2vazqfqeb.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gt2jjfilznu.html

PHP:  implode(",", $items);
来源：http://dali.bjfxy.top/Article/details/gt2wqmdeqno.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gt2otuafcrm.html

TS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gt2eyzaahux.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gt2ylxwpoqh.html

Go:   strings.Join(items, ",")
来源：http://dali.gotoacloud.top/Article/details/gt2lmvpllei.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2gucrromi.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gt2pdmlgpnn.html

[E09] 去除所有空白字符
来源：http://dali.jinqigfzy.top/Article/details/gt2thxfyjtw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gt2mxuvovbd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yonumen.top/Article/details/gt2iyopplfr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gt2vxwjaohb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gt2jrkxgmlo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aizwys.cn/Article/details/gt2rcxtcdni.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hfpthk.cn/Article/details/gt2rawadgkg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gt2nzqrggxc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gt2fzaxqfjs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gt2xeuxdkaw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2qulnzgcz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gt2fvycjzqa.html

JS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2nejispeq.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gt2lyekbhyf.html

Java: String.format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2dxfxjjkn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2hyvemrkm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2ialeuofc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenzaomai.com/Article/details/gt2zdwngxul.html

[E11] 反转字符串
来源：http://dali.316326.xyz/Article/details/gt2mexzvueo.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gt2cctmmdew.html

PHP:  strrev($s);
来源：http://dali.xuanzx.com/Article/details/gt2vxemeuhe.html

JS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2rpzlfier.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2iollsrzp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gt2hnvmmjah.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxshoyae.html

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gt2vynfubqv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gt2fvmqlgzb.html

[E12] 统计某字符出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxkblgkm.html

Py:   s.count("a")
来源：http://dali.ivvv.top/Article/details/gt2gnmsfikd.html

PHP:  substr_count($s, "a");
来源：http://dali.jianghu66.top/Article/details/gt2jutvhyuh.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gt2tlzjseju.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gt2brwitxzz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gt2gjbnbujo.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gt2giushsaz.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctrbyarx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gt2pzvgmask.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evcnngtx.html

Py:   for ch in s: print(ch)
来源：http://dali.guannengcc.top/Article/details/gt2xdiixoep.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gt2gkvvkaas.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2etvnnclu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gt2tvsknbji.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adacdkli.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.iojbl.cn/Article/details/gt2kzzekleo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzjhwnzu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2tfreufwt.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gt2fhmscpco.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gt2rwtehfdr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxinkj.top/Article/details/gt2deonabfz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gt2egiqqvtq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrchyfkg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.316326.xyz/Article/details/gt2fyqimqrg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gt2stsbdrmt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbcuwqwt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gt2qmrggrgg.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gt2qjvsqggj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gt2agnysgvl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2uqlwmuor.html


<!-- 参考信息 -->