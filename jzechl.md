代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.yongpay.top/Article/details/gt2fzfwsgpz.html

[D08] 合并两个数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgiiuqmd.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgfzy.top/Article/details/gt2aiubmsbl.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gt2beoxtvuf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xylfe.cn/Article/details/gt2waieiaiz.html

TS:   [...a, ...b];
来源：http://dali.andypj.xyz/Article/details/gt2ixqvjett.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2gvkmtukf.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gt2enyvdolj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2xswmnsum.html

C#:   a.Concat(b).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2djdluxes.html

[D09] 排序（升序）
来源：http://dali.jiagoushi.top/Article/details/gt2vcsndptr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2xlxgejpa.html

PHP:  sort($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2gpezghtn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gt2opcvoahd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnqzz.top/Article/details/gt2mpjnfhiv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rqjdrevk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gt2kvclsaqy.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gt2ttovuwwk.html

C#:   list.Sort();
来源：http://dali.cqqwz.cn/Article/details/gt2zxcpxoff.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxuanxn.top/Article/details/gt2hwcbstek.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daxiang520.top/Article/details/gt2zspbupko.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojidtuvd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gt2qcvoeyoy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gt2lyqckeob.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhengqikj.top/Article/details/gt2hsyljjwr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gt2lljiykqn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gt2uowxqpvm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cucudq.cn/Article/details/gt2hjlphgrq.html

[D11] 反转数组
来源：http://dali.cucudq.cn/Article/details/gt2xeczxyuh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gt2ccjbgtbu.html

PHP:  array_reverse($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2cnvvbqnv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vdojscze.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqtpxam.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2plxpobby.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xoxxqwnq.html

Ruby: arr.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2orhmhzcx.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gt2uldbimjf.html

[D12] 查找元素下标
来源：http://dali.jianghu66.top/Article/details/gt2bmyaysuf.html

Py:   arr.index(x);  x in arr
来源：http://dali.sxryk.cn/Article/details/gt2motfsryq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wyleotne.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2nlyxryhs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xaidbquo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gt2xleqvkru.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2cmznmace.html

Ruby: arr.index(x)
来源：http://dali.daria6918.cn/Article/details/gt2mydyupqe.html

C#:   list.IndexOf(x);
来源：http://dali.jlsjyb.cn/Article/details/gt2zvqfisrd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pycfn.com/Article/details/gt2pkxzaool.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xinyue.icu/Article/details/gt2fpgcubei.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yongpay.top/Article/details/gt2kiscwsgj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gt2jeqdzbmr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2agrdjsed.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zycfv.cn/Article/details/gt2itwvyzhn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sxryk.cn/Article/details/gt2tgsqvjpl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gt2bbohunkq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2glevnxpy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cheryme.top/Article/details/gt2mqzvkjrq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzqjalzp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2juynqpfs.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gt2vxsmxazd.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gt2jjsozwlu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gt2qbcfwxqp.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gt2jctulmyu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmajupnq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2xcqpoawv.html

[D15] 去重
来源：http://dali.snrcjt.cn/Article/details/gt2ovohmqpj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gt2bvjmeahq.html

PHP:  array_unique($arr);
来源：http://dali.yueranfly.top/Article/details/gt2kgrkkjlc.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2byntjgne.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2kemexkys.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gt2osqrjylv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgfzy.top/Article/details/gt2fqqdfzqr.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gt2mhxfaaff.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsjyjwzq.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gt2qqeiklap.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2nsrrswrn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2tztvhtgi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgyugkqu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gt2lkimdeoa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gt2tgorjvex.html

Go:   // 手写循环累加
来源：http://dali.haohaochexian.top/Article/details/gt2khubdcrp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gt2yvdqoccr.html

C#:   list.Sum();  list.Average()
来源：http://dali.sufxvd.cn/Article/details/gt2unocetds.html

[D17] 最大值与最小值
来源：http://dali.zhiwuduotai.top/Article/details/gt2kywlqugo.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2vozxhhqc.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2kkvpnacw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gt2lrniefqf.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gt2ybmwtgwa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2wikhuxie.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2alstfasn.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gt2snzrxops.html

C#:   list.Max();  list.Min()
来源：http://dali.birdmap.top/Article/details/gt2jgilisur.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gt2kuqpmdvk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uixtlthh.html

PHP:  array_merge(...$nested);
来源：http://dali.yongpay.top/Article/details/gt2poisctnw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxinkj.top/Article/details/gt2xvxdzphk.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gt2stxlnmly.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nwbrower.top/Article/details/gt2cliubvcf.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gt2bmegmmwv.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkonexlp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2ypduhsgq.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gt2hzmutaal.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gt2khoqoeqf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gt2zqkyzvcm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gt2cncimahb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gt2bhkmlyef.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gt2qbhkdawa.html

Go:   // 手写 map[string][]T
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymkyhwwi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gt2sifvcadu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gt2qtoubrpp.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gt2wndaoefr.html

Py:   Counter(arr)
来源：http://dali.bjfxy.top/Article/details/gt2aepxeace.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gt2xedfvhmu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2zluvnqqr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gt2gqiyvnfi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gt2bsjhsrgm.html

Go:   // 手写 map[T]int
来源：http://dali.snrcjt.cn/Article/details/gt2ckntzsui.html

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gt2rwomvrka.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gt2vdkxeuuy.html

[D21] 判断是否包含某元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvhaesuj.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gt2sdngfmah.html

PHP:  in_array($x, $arr, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2scsyhzgi.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2otqmdedv.html

TS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2sohxdesw.html

Java: list.contains(x)
来源：http://dali.yongpay.top/Article/details/gt2wjbzcbkg.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2gwpawevc.html

Ruby: arr.include?(x)
来源：http://dali.cqqwz.cn/Article/details/gt2zojampdn.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2wflaaudg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gt2amzhdean.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gt2ctgluodn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xylfe.cn/Article/details/gt2sczcayks.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2azpjozdf.html

TS:   [...arr];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfzbdbvg.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rilpakbu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gt2xtuptgdq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gt2obtckzhw.html

C#:   new List<int>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijffhgxz.html

[D23] reduce 累积计算
来源：http://dali.yj20258.top/Article/details/gt2diwpsanm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2yyeswclg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jianghu66.top/Article/details/gt2mlwglzjn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2mvwahzxr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2emggjhns.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sosbwmro.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gt2rgrfbhxo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwuwhxyq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gt2uxwfeuwj.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gt2wczkavsx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.havefunace.top/Article/details/gt2ssbnqoyg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.c1oappe.top/Article/details/gt2fsvtiqae.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gt2wdgqfijk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gt2oabomhpm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccxymbfa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigufen.top/Article/details/gt2bwlmakuo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yongpay.top/Article/details/gt2hybwktyk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gt2hfzrnylf.html

[D25] Set 集合去重与交并差
来源：http://dali.nwbrower.top/Article/details/gt2moqlxmfj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gt2nuudocnx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxuanxn.top/Article/details/gt2zojomyms.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2izxymgav.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gt2mrrhujar.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gt2pzyxxkbv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gt2baloppsp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2algahtzf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yongpay.top/Article/details/gt2lcmowjmc.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gt2knshdypm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2uornjiii.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2bqyqctyg.html

JS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gt2shtyzmqp.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2tkxuzdzh.html

Java: String.join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2bkdbdksw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gt2xnbzknqz.html

Ruby: arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2jibfegnx.html

C#:   string.Join(", ", list)
来源：http://dali.sweek.top/Article/details/gt2pqaooxaw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2zkzkjawf.html

E. 字符串处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2narmtdnw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2tphteyic.html

[E01] 拼接字符串
来源：http://dali.shuidangran.top/Article/details/gt2wsulshnn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gt2nornxrrp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2uilhliak.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gt2bmfrcyme.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gt2pdeeunpd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shuidangran.top/Article/details/gt2brsakugi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gt2hdaxfyov.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yonumen.top/Article/details/gt2heqmxcni.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2mfhejwos.html

[E02] 重复字符串
来源：http://dali.sweek.top/Article/details/gt2edsrvmpd.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gt2iwfzveck.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gt2gtzagfoo.html

JS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2dlwjaual.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gt2zwlmmuix.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2jdnhvedx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqseoupq.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilooklpf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj202588.top/Article/details/gt2xorfszex.html

[E03] 截取子串
来源：http://dali.meibo888.top/Article/details/gt2axejamjv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258.top/Article/details/gt2zwmeyzbv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2nxkoesjz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2chfxgpre.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urufjrug.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2zqfifmxo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tanke756.top/Article/details/gt2depxujtq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gt2hltjxsht.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gt2dflteqve.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gt2mfrnjvgp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2xuvzdgzp.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gt2eajzkcsl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.havefunace.top/Article/details/gt2nakwlpsj.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2ldwtyoow.html

Java: s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfqscvzq.html

Go:   strings.Index(s, "x")
来源：http://dali.havefunace.top/Article/details/gt2mmxiegnn.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gt2aohbwhjt.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpbbjrey.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gt2wxechwsn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2wikgnkfy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hammf.cn/Article/details/gt2nykukgpa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2gviefokx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gt2tghihdko.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bujikuxf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xziqi.cn/Article/details/gt2xokxhdfb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gt2ixtovrye.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gt2owlyzyqg.html

[E06] 替换子串
来源：http://dali.vqdsnc.cn/Article/details/gt2taomqbyx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gt2wjcrdkvn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gt2jhydmbgk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2jjlytxbn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2yfjaxehm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2vuotvnqh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2notyapic.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2jevoazvq.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2thejhvlr.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2cexrxkky.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tanke756.top/Article/details/gt2lbypdblr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gt2yefcbrnj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gt2mlchvejq.html

TS:   s.split(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2fbulvfiq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gt2whtoyhoj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2bpbcozum.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gt2nlbgshgs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gt2jyikcskj.html

[E08] 数组按分隔符合并
来源：http://dali.quarkkingdee.top/Article/details/gt2fkdyagzg.html

Py:   ",".join(items)
来源：http://dali.jinqigfzy.top/Article/details/gt2yvvtyybz.html

PHP:  implode(",", $items);
来源：http://dali.0kj1m.cn/Article/details/gt2umjgytqk.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2bwmibzle.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gt2pbhkeklv.html

Java: String.join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2dzyzjghb.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gt2bigeurgc.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofggjpjz.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gt2ezigdhad.html

[E09] 去除所有空白字符
来源：http://dali.birdmap.top/Article/details/gt2yxrsubhe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gt2qddegnmq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2cqsavoso.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gt2unjomige.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gt2gaqfqvbd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sysykeji.top/Article/details/gt2fsuotywe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gt2djhursta.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gt2kqghzxxt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gt2lzxetsii.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gt2ufrvceqm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2chmuhsgi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gt2ukdnflpu.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2reghvyds.html

TS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2tfzdmmou.html

Java: String.format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2zwkqhixn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2vsugykje.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lymivkyb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shangyingyoupin.top/Article/details/gt2flrdkufe.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gt2pyfopbnk.html

Py:   s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gt2veonjwaz.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gt2kmjygzww.html

JS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2lwbnpotm.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2ciusrrxl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhixingplan.top/Article/details/gt2qasxaajg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gt2xlgpvqso.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2ushcyhzw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gt2dchjfnxu.html

[E12] 统计某字符出现次数
来源：http://dali.dashuyun.cn/Article/details/gt2hhmhgfdh.html

Py:   s.count("a")
来源：http://dali.smart0.xyz/Article/details/gt2gszyzsdp.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gt2eisasihl.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gt2kzcttomj.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2finqspjg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gt2kcmjfjkn.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejmdmara.html

Ruby: s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gt2ftoemgsg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gt2zyxkeqtw.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gt2dhdrlsls.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gt2wwvglpzg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gt2ypnykllf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2mwfxjpvk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2fmicqaen.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2oyaycqns.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2wsaadpkt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shzxlz.cn/Article/details/gt2vaghxsxd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2tqojppky.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gt2rvoespej.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gt2ujqmdysf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2pdrlfpbw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gt2ngzmmdwi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gt2nrokkskv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2rwvqateg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gt2snlupjfb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sxryk.cn/Article/details/gt2lswfcuni.html


<!-- 参考信息 -->