代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.bjfxy.top/Article/details/gt2tfoirexr.html

C#:   a.Concat(b).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2svkfxrre.html

[D09] 排序（升序）
来源：http://dali.316326.xyz/Article/details/gt2jytbxrle.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gt2vixwqzdb.html

PHP:  sort($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2nslehwjn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhixingplan.top/Article/details/gt2gjwuqdko.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fusburrg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangdashe.top/Article/details/gt2hlsiidtk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gt2wmrndcrm.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gt2gjkuhgev.html

C#:   list.Sort();
来源：http://dali.gotoacloud.top/Article/details/gt2meoyvkhz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gt2owqjqdvn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etefgpyt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gt2gqkisvyc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2selozjkx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gt2faulgcby.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gt2nuxxzfan.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gt2mgbkvjvl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hysaishi.cn/Article/details/gt2qwjxkosf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.svipenyu.cn/Article/details/gt2jfdaqcsi.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gt2ajthmify.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.0kj1m.cn/Article/details/gt2iqzuxkzz.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gt2qsixokmx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gt2giccngjx.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gt2kanblnzl.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lsjwfxjy.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2jiwpgsoc.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2swisdjem.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gt2eytcwljr.html

[D12] 查找元素下标
来源：http://dali.kuanghao11.cn/Article/details/gt2zckjyjsd.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnxiangtu.top/Article/details/gt2ctcxrcju.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gt2uzkpshse.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gt2tvlljyjm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gt2cdncnqvc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbhaolic.html

Go:   slices.Index(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhvxegry.html

Ruby: arr.index(x)
来源：http://dali.cqqwz.cn/Article/details/gt2wqexxcwa.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gt2mbvrdzqf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.birdmap.top/Article/details/gt2ubhpkvxy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kflvgrbb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yongpay.top/Article/details/gt2opnyuaop.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2xdfquloa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gt2ulrrttjv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2jvuvdtly.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.andypj.xyz/Article/details/gt2usgdaoif.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gt2qzspnlfw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2ngyliswe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fzhhl.top/Article/details/gt2ffmrcsjq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hfpthk.cn/Article/details/gt2gvtxnczh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2iladxohj.html

JS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gt2bzlltmgj.html

TS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxjfbiaw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ayxztyml.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ksgluxpl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2ltjozedx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2zhlftwbv.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gt2xilpmqck.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2htqxcxhj.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2qfdthccz.html

JS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gt2yjslewyk.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2koqtlhui.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gt2bctwrowe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gt2xminjvqd.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gt2mzekwcgt.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yatdsdrx.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gt2evqfwwnd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gt2ohabvjqf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aizwys.cn/Article/details/gt2fkdunyqx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2hnjxyotz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gt2nrikrnxn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gt2hvtrmaor.html

Go:   // 手写循环累加
来源：http://dali.yuanzhike.top/Article/details/gt2bexooxss.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.birdmap.top/Article/details/gt2nnvztcco.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gt2dpmknmvz.html

[D17] 最大值与最小值
来源：http://dali.wangshuangyany.cn/Article/details/gt2aixhxhje.html

Py:   max(arr);  min(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2prfrzjgi.html

PHP:  max($arr);  min($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fghrcagq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangdashe.top/Article/details/gt2pvaziojv.html

TS:   Math.max(...arr);
来源：http://dali.xylfe.cn/Article/details/gt2qoxqcytm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jiagoushi.top/Article/details/gt2oecjqyjq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2ewxnpkxn.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gt2azcyyblw.html

C#:   list.Max();  list.Min()
来源：http://dali.jlsjyb.cn/Article/details/gt2mdhwfiju.html

[D18] 扁平化嵌套数组
来源：http://dali.yangfankeji.com/Article/details/gt2goodgcjb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gt2dzfusqmm.html

PHP:  array_merge(...$nested);
来源：http://dali.gogol.net.cn/Article/details/gt2enksakta.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oielvmsf.html

TS:   nested.flat();
来源：http://dali.hfpthk.cn/Article/details/gt2xqxtqbat.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gt2buaadezr.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gt2rpqxvprv.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gt2uudgdeom.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rohmhqdb.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gt2lghfcgas.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gt2otfkfgbk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gt2skalgwfe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgfzy.top/Article/details/gt2irxjhphy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gt2aarnjgch.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gt2vrinqwpl.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gt2xyctbnev.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gt2jnkgehpf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gt2vuayzreo.html

[D20] 统计每个元素出现次数
来源：http://dali.haohaochexian.top/Article/details/gt2hzclnjov.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2ibhaiafe.html

PHP:  array_count_values($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2fwhxongr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gt2xenforqh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gt2ozsiotop.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gt2wzyrwpce.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gt2ldqhzhbt.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gt2syqzyhcd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigfzy.top/Article/details/gt2yuasdhfc.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigfzy.top/Article/details/gt2jqtaytbz.html

Py:   x in arr
来源：http://dali.andypj.xyz/Article/details/gt2dbgzfdbz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aizwys.cn/Article/details/gt2ejednxlk.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2eyslxcbv.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvtbzqnz.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gt2dxzvdmau.html

Go:   slices.Contains(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2glddqksr.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gt2jdevlgnl.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2gmruuvlp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gogol.net.cn/Article/details/gt2mqjzalbs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2apudzbjd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gt2yulvlvtu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2zjlygvwm.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gt2bdruxlwv.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2pjtzkfus.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yanxiufei.cn/Article/details/gt2iommgcye.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gt2ztwnaayw.html

C#:   new List<int>(list);
来源：http://dali.cheryme.top/Article/details/gt2ibqpstwm.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gt2ncmjbekv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfmdowfe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nwbrower.top/Article/details/gt2grbnfmqs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gt2wwwqtiua.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gt2idqhiytq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gt2lwqkxfbm.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gt2jyxdpbpd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2msypalev.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xziqi.cn/Article/details/gt2awuenlma.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gt2zuqntxes.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuanzx.com/Article/details/gt2rzukadpq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jianghu66.top/Article/details/gt2fsliufhr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gt2qxrukjjk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2uvirqtkx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ydzc1.top/Article/details/gt2lkqbcopc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gt2cdydqcig.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2xuxsklfk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pycfn.com/Article/details/gt2jcrdzdpy.html

[D25] Set 集合去重与交并差
来源：http://dali.yj202588.top/Article/details/gt2bxjenmqz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gt2yvgmlixw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gt2xrfyanzv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gt2gknuwycx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gt2bezowolr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2rhuincrk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.svipenyu.cn/Article/details/gt2iagrdhgv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxinkj.top/Article/details/gt2obckiqbn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangdashe.top/Article/details/gt2bsfcshuj.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gt2jonsfsny.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ybcxt.top/Article/details/gt2cxjeirfi.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2lveljnwr.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2flpmtrxm.html

TS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2wujpubox.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gt2sdgjfbrl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwvfwqg.html

Ruby: arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2kxcqftzw.html

C#:   string.Join(", ", list)
来源：http://dali.birdmap.top/Article/details/gt2qpormyif.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ubhzilop.html

E. 字符串处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2qyjjoajq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2alrccyma.html

[E01] 拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2ncdzamgr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgfzy.top/Article/details/gt2olamgbbq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gt2cqaixmgt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2yuzwdqjb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gt2obfkgfjf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gt2xpxtscny.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihvjokqi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gt2fyuewiwt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2fchruplc.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gt2qvldqadw.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gt2dqrspnsn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuebrosi.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2prvwurje.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2zvdcolup.html

Java: "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gt2hjxgghva.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuxming.cn/Article/details/gt2fhpbivlk.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gt2vogzfuxe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gt2rdavnjfe.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gt2hszgtxih.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2azdirpoz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2pktfafkm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzzagbqx.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gt2ywgsdtjv.html

Java: s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2ngnsgkgx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ehwqpu.com/Article/details/gt2ymkpkcfs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gt2nigmvxbn.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2klrhuahx.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uywfkmnq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gt2pffdqlgm.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gt2wruufxhs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gt2cxyturpz.html

TS:   s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gt2waelzegk.html

Java: s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gt2wnmedenj.html

Go:   strings.Index(s, "x")
来源：http://dali.sysykeji.top/Article/details/gt2qigfsvnx.html

Ruby: s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gt2bhbnmwxs.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fzxncdih.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gt2jkcyrley.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fengsongda.top/Article/details/gt2pawqwasd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guowangkeji.top/Article/details/gt2kgfiaeql.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gt2hoqdgssl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gt2vwyppiqc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2bjwylhjy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.quarkkingdee.top/Article/details/gt2xvwqbnzr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gt2woxfmhnf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2cptrblkb.html

[E06] 替换子串
来源：http://dali.yueranfly.top/Article/details/gt2sugtjboy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gt2uogitcgq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yangfankeji.com/Article/details/gt2lujiuiwb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2ksdcyzam.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2gfxwuhgq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2nmhrjqdd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gt2qfngagrl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2xwkapxwe.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ljzjcyux.html

[E07] 按分隔符拆分
来源：http://dali.cdnleiting.top/Article/details/gt2fdioskfz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnxiangtu.top/Article/details/gt2hdbuokgc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2estzftzx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gt2ftfjkxhr.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2huxuxmiq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flogctbm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohjjahan.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gt2cugrllpo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cqqwz.cn/Article/details/gt2cfdmmbhm.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gt2kwjbapqt.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gt2ctebcmif.html

PHP:  implode(",", $items);
来源：http://dali.316326.xyz/Article/details/gt2qstryqol.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2bmljowaq.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gt2mpahznsq.html

Java: String.join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2obsbhsen.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xboqthgg.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gt2aatqcuhq.html

C#:   string.Join(",", items)
来源：http://dali.andypj.xyz/Article/details/gt2hvgfhuha.html

[E09] 去除所有空白字符
来源：http://dali.shzxlz.cn/Article/details/gt2jukflano.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gt2dxscwqhj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ydzc1.top/Article/details/gt2wnekjdlu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwcmeigb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2ksuwkmhz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2yvkeatyc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.mhx1999.top/Article/details/gt2asxapimd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqkcyqk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2xpgzqoxx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gt2aktybpay.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2zdqtjtxa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sufxvd.cn/Article/details/gt2cpzsdned.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2ymgwihkq.html

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2vdnwovfb.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvqhnffp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dftxefec.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqkyoogn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gt2pwtgmeum.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gt2bueopdgp.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gt2yaxlnlcb.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2ejpcpfpm.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2daxccwyr.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2adsvgpbw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gt2qmwgtije.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gt2nwqpomyp.html

Ruby: s.reverse
来源：http://dali.jianghu66.top/Article/details/gt2upyjjydz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gt2uygpottk.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigufen.top/Article/details/gt2htxetksv.html

Py:   s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrlckpvv.html

PHP:  substr_count($s, "a");
来源：http://dali.bjfxy.top/Article/details/gt2ogbqijqu.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gt2vfcbzlee.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gt2dckeltpq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zigsqxmr.html

Go:   strings.Count(s, "a")
来源：http://dali.yuanzhike.top/Article/details/gt2ufmfaduk.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2obadzjfe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gt2ayczvciy.html

[E13] 逐字符遍历
来源：http://dali.andypj.xyz/Article/details/gt2ngevcqfi.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gt2womvuzoq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gt2ekwtkkue.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2cefcyfuf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gt2kmiujjsh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2hafjcrrt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghroacwl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdfblhgt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2csbgkyqg.html

[E14] URL 编码与 Base64
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqbfvmev.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgeldomn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yongpay.top/Article/details/gt2whdhkcjo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xinyue.icu/Article/details/gt2pulqmbbh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gt2nvvqvekv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2txpzcmab.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gt2audcklvk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.quarkkingdee.top/Article/details/gt2hgyzrmaj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtzcassc.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gt2fuydyugl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqvbjqmk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gt2bpzsvtzc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2tfhzzixj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gt2skxmyyyy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gt2mqvgdiia.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gt2hlrregjt.html


<!-- 参考信息 -->