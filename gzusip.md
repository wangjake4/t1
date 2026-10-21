代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gtatyatwpm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gtaizqlnln.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gtwnndwgjf.html

JS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtffpzcltq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtxwxnnkiv.html

Java: list.subList(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtsrwamngw.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gtxpcgqswx.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gtcvaszbwu.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthentbdoh.html

[D08] 合并两个数组
来源：http://dali.jyoumei.cn/Article/details/gtptysqjbi.html

Py:   a + b;  a.extend(b)
来源：http://dali.cucudq.cn/Article/details/gtcyzmdjji.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtcfqqkuqs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gtrugokvka.html

TS:   [...a, ...b];
来源：http://dali.bjfxy.top/Article/details/gtemfzxcky.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrokofbh.html

Go:   append(a, b...)
来源：http://dali.guowangkeji.top/Article/details/gtkzydshoq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.svipenyu.cn/Article/details/gtljlfnckf.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gtyqcdwfny.html

[D09] 排序（升序）
来源：http://dali.gotoacloud.top/Article/details/gtftvwqfdl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtakmfqzsj.html

PHP:  sort($arr);
来源：http://dali.birdmap.top/Article/details/gtwirgceum.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gtsefcmvuq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gtjbfmmzdz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gtbquaoann.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtkuawsher.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtigsrndmd.html

C#:   list.Sort();
来源：http://dali.feifeiyinyue.top/Article/details/gtsoaeizhf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.316326.xyz/Article/details/gtfsjpumha.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tianlin.xyz/Article/details/gtfcwpnkic.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtqgilngfj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gtawmflcyf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtpaakliwp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipafirtp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gtpeogucfb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gtukylvylv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhengqikj.top/Article/details/gtjsqkiibp.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gtofhpitxp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gtvehdmgfk.html

PHP:  array_reverse($arr);
来源：http://dali.ybcxt.top/Article/details/gtdrqngnxe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ybcxt.top/Article/details/gtolulzjxd.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtfunbwbog.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gtxuutiovy.html

Go:   slices.Reverse(arr)
来源：http://dali.yongpay.top/Article/details/gtcsrxvhvq.html

Ruby: arr.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtymifgwav.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gtizwdqwbu.html

[D12] 查找元素下标
来源：http://dali.yvedp.cn/Article/details/gtrkvqlscr.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gtjrylyzsv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.andypj.xyz/Article/details/gtucvrqzhy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtgbaipqrk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtnqemyzey.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gtfyejstui.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtlisgfrki.html

Ruby: arr.index(x)
来源：http://dali.c1oappe.top/Article/details/gtbgulkzpl.html

C#:   list.IndexOf(x);
来源：http://dali.hnxiangtu.top/Article/details/gtixudovyy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj202588.top/Article/details/gtknvtmfgp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gtyjxnlifb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gthkhiuysl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtyggvnncy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gthrrstlxr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hysaishi.cn/Article/details/gtgpnmlrbg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gtitchoplu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gtoiamzinu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtgdeeagbi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gtepiqmslh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gtbogsnkns.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtjmbrhfbj.html

JS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtuiatvlkv.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtlloqbhkm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigufen.top/Article/details/gtpjfmwhju.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gthhgrvsjb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtxptbzpto.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtfftztlfc.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldadndfe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gttfblrmgu.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtndvxgfvh.html

JS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtuyrmuhbn.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtwbfahgnf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gtixcwzyuu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.vqdsnc.cn/Article/details/gtnewugpuh.html

Ruby: arr.uniq
来源：http://dali.kuanghao11.cn/Article/details/gtxomxmyjd.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gttyhxzyzy.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gtmwrwlgxw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtszgfzehx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gthlwcevuw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtdmpnnkvk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtszgkscfy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fzhhl.top/Article/details/gtuzrfmbtu.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gtfpnjsqmf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gtzunjawcf.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gtpwirjqjr.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gtujmjkmaf.html

Py:   max(arr);  min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtcnqvinsj.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gtusiovwpb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.kuanghao11.cn/Article/details/gtzckjldrx.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gteoxqoakg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gtsotmhcew.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtobadunhw.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gtycmpwllk.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gtjbxazffs.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gtforriwno.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cashguo.top/Article/details/gtfyevjwnf.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gtjqrigywf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxuanxn.top/Article/details/gthjwourgy.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogwqnkmk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cheryme.top/Article/details/gtrdgtpptj.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtasgpzdmc.html

Ruby: nested.flatten
来源：http://dali.guannengcc.top/Article/details/gtrrmlmchd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtvqweqikq.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gtvriuyxxz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gtxmdeauxe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gtdmvjpuuv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gtsyvoicjq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpitmtsw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gtezzlxnev.html

Go:   // 手写 map[string][]T
来源：http://dali.fzhhl.top/Article/details/gtsaenkxdg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gtiquskkqg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.birdmap.top/Article/details/gtsjxaijvy.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gtxsydeufj.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtrmzpfsep.html

PHP:  array_count_values($arr);
来源：http://dali.yangfankeji.com/Article/details/gthuryyugw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxhgoifc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtjwprczdy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.feifeiyinyue.top/Article/details/gtygrvgggb.html

Go:   // 手写 map[T]int
来源：http://dali.hnqzz.top/Article/details/gtqywskoke.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gtollsqonw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqfmncir.html

[D21] 判断是否包含某元素
来源：http://dali.c1oappe.top/Article/details/gtbemvgubt.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gtcvzwaphs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtuvuexqcr.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gthprwrfef.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtagulotqh.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtkceecckb.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtyzmnxuzy.html

Ruby: arr.include?(x)
来源：http://dali.cucudq.cn/Article/details/gtvmvwngpk.html

C#:   list.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtjbfsfkge.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtnwwxcslk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhengqikj.top/Article/details/gtqethyqqi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gtlsjmmiod.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jyoumei.cn/Article/details/gtcenpfetw.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gtioujwzkk.html

Java: new ArrayList<>(list);
来源：http://dali.dianchejie.cn/Article/details/gttllmkzsl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xinyue.icu/Article/details/gtknnismze.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nwbrower.top/Article/details/gtdzcsvvvq.html

C#:   new List<int>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxquxxlbx.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gtauibirmp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtubdbkdbz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtvwavffaf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtiuhjjqcx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtkzunmvtc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jyoumei.cn/Article/details/gtvivomhzw.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtnkevobpo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gtimszjlbu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gtdzpvenhy.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gtakkqxvjo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gtmodimezf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqodabei.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gthqazawdl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtnpmyeqjd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyzmfocx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gttbwggtcr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gtxtuizjyu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gtnwbzledk.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtbyxnnlka.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtsgjozymc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gtkdnxtshb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gtofqeuqpv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jiagoushi.top/Article/details/gttbgvvcrw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yonumen.top/Article/details/gtswrkpnxz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cashguo.top/Article/details/gtbdfqadmd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dashuyun.cn/Article/details/gtucwnonno.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gtqxjctujc.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gttjocbbmx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cdnleiting.top/Article/details/gtjvshkrzy.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtygrbdldk.html

JS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtzjlrbwet.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtfhmbponf.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtexcsoubu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gtvmvnqmnd.html

Ruby: arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtqpsootfb.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtoevgtusz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpohivxpe.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gtqjdbatfh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgsxjewhw.html

[E01] 拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtjaiznruu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gtkjrwdope.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gtyjzcdmsz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtqbsgybpe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtsbohzjva.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gtpksegxuj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gtzmhlvrxx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fzhhl.top/Article/details/gtreukmovt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtnndrjzbw.html

[E02] 重复字符串
来源：http://dali.hysaishi.cn/Article/details/gtawcxbkwp.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwwomhix.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gtindaatbd.html

JS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtdrhhsnhl.html

TS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtngyqnomi.html

Java: "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtuupbuocs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtcmdtwwsb.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gticdrrvfd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtzhzzymvd.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtmevyhwvp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gtpdrrjjio.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtaebcgfkv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtgkzkndpb.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtndzfjmap.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtawhvgacy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gtjkytdbwp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ppjwa.cn/Article/details/gtuqlrxtgk.html

C#:   s.Substring(1, 3)
来源：http://dali.guannengcc.top/Article/details/gtmoeehtbh.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gtimfqhuxw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtnxyiyclx.html

PHP:  strpos($s, "x");
来源：http://dali.hfpthk.cn/Article/details/gtmnehuiee.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhengqikj.top/Article/details/gtthqdbeok.html

TS:   s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtsdzmgoxm.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtajhnyyoe.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gtyamzyzbe.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtrqdpmhna.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtvhtulcas.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gtusesrmct.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.316326.xyz/Article/details/gtqlgaoqtj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhengqikj.top/Article/details/gtdleqmtdd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtwnihcblx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.c1oappe.top/Article/details/gtdfouekcv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtcrglctqm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gtyxfepjcq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrfjrofo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtbwbagpax.html

[E06] 替换子串
来源：http://dali.fengsongda.top/Article/details/gtfungwofp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtrzilrklu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hfpthk.cn/Article/details/gtsjkvfyat.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtexwzsiqj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtxwgfqnca.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtwopzvzrj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gtfldqlhib.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gttlpmvpmv.html

C#:   s.Replace("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtjzlgpfka.html

[E07] 按分隔符拆分
来源：http://dali.hammf.cn/Article/details/gtijcfonom.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.316326.xyz/Article/details/gtpjfsuwvv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtitjetmry.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daxiang520.top/Article/details/gtqhcvabom.html

TS:   s.split(",")
来源：http://dali.sweek.top/Article/details/gtqgfsrchd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gtqjharvzz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gtswmvvqyd.html

Ruby: s.split(",");  s.split
来源：http://dali.shangyingyoupin.top/Article/details/gtuhiargju.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gttpyaexlv.html

[E08] 数组按分隔符合并
来源：http://dali.yvedp.cn/Article/details/gtvvfierxt.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gtwsabbssv.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gtcavexlnt.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmiftzov.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtxqidpoze.html

Java: String.join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtrnaxjpgi.html

Go:   strings.Join(items, ",")
来源：http://dali.yuxming.cn/Article/details/gtdhoieuho.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtwqaraqnu.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtedmnvalg.html

[E09] 去除所有空白字符
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrobasfmf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gtyworygdn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.andypj.xyz/Article/details/gtawwfwwwl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtwnmvdtlt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtlqrhrrre.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtuaqgxday.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jyoumei.cn/Article/details/gtgtwskuea.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtpcuciaql.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gtkcxhvjid.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtcrukilzf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gtxjwbibpy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaaceqeb.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtrueoktcr.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtemshkgms.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtdxjgjuww.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtvdlvcknz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtktmilsko.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gtpsmaidfg.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gtcoifhcue.html

Py:   s[::-1]
来源：http://dali.sweek.top/Article/details/gtwpbmclcf.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtsahovgsx.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gticznbtgi.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtercltxma.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guannengcc.top/Article/details/gtwqpeueiw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtzgwjtfhs.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtjfoesptl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtecmooski.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gtorpexgvr.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtvgkjwoyl.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gtsmakdnld.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtileituqq.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gtlhlrfmyd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aizwys.cn/Article/details/gtaomboubf.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gtmwxdcegn.html

Ruby: s.count("a")
来源：http://dali.pycfn.com/Article/details/gtnhtgrxqs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gtwgeusujb.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gtvygrgief.html

Py:   for ch in s: print(ch)
来源：http://dali.hammf.cn/Article/details/gtdcppzywj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gtwaimkspm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtmudpycjz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtjpmqhzva.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkximzye.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gtzlbetxdt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtsshndzlf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gtsabnkebd.html


<!-- 参考信息 -->