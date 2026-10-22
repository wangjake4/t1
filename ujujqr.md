代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.aibaodan.cn/Article/details/gthlnfptcm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gtquioyowa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtobxxefea.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtdoqtkwll.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtklllgdpf.html

Java: list.subList(1, 4);
来源：http://dali.yongpay.top/Article/details/gtzzkfnxwm.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gtnyzkxoxq.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gttomcgapt.html

C#:   list.GetRange(1, 3);
来源：http://dali.ivvv.top/Article/details/gtkylibgzu.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gtrhoruktf.html

Py:   a + b;  a.extend(b)
来源：http://dali.dianchejie.cn/Article/details/gtsuogequm.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gtdxorlxcs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gtdqgiblla.html

TS:   [...a, ...b];
来源：http://dali.c1oappe.top/Article/details/gtyoizobie.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yonumen.top/Article/details/gtfjuubpkl.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttoykpswm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jlsjyb.cn/Article/details/gthevpiizz.html

C#:   a.Concat(b).ToList()
来源：http://dali.xinyue.icu/Article/details/gtrylckkok.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtcirqlrsa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtrkaxlauo.html

PHP:  sort($arr);
来源：http://dali.gotoacloud.top/Article/details/gtqdejdzko.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gtbhrxndbh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gtlwbvirsr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gtuiboikvw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtpaxmeapx.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gtcaewaazw.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gtqxekkbqi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtwhvuejmt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gtkrymtcks.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtqimzfbfi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gthoxeulju.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gtomvlrglc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gtmmxzbpdb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.redwolf501.top/Article/details/gtinxwajkx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ivvv.top/Article/details/gtmfuheicx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuanzhike.top/Article/details/gtuxemdqtm.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gtwykxmdzz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gtgkmcihub.html

PHP:  array_reverse($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzdsntzx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xziqi.cn/Article/details/gtcvwfiyaq.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gtluhhbhmg.html

Java: Collections.reverse(list);
来源：http://dali.yueranfly.top/Article/details/gthnnkikyf.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gtjftiwrai.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gtwfkcisec.html

C#:   list.Reverse();
来源：http://dali.guannengcc.top/Article/details/gtajjktewx.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gtnpwpmmxa.html

Py:   arr.index(x);  x in arr
来源：http://dali.sysykeji.top/Article/details/gtllxkwegd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtqfqicyvm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtmgyehymm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtrbjafbau.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gthrebtjvq.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gtnnoxjsju.html

Ruby: arr.index(x)
来源：http://dali.zhongyouzk.top/Article/details/gtrhmaotfk.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpusozmqb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gtlvzycyqr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gzhubu.top/Article/details/gtwjemisdl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gtbljlvrdm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtitkwrddi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gthxatgzvd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtaswdtdlx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gthccoxadu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gtfggrxvew.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.c1oappe.top/Article/details/gtjtmannwd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dashuyun.cn/Article/details/gtyhfskjdc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigufen.top/Article/details/gtzolomnmi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtbfcntltw.html

JS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gtzrtglyve.html

TS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtefqdahfr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.birdmap.top/Article/details/gtnsdcwjru.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gtqfyausts.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtxdvcyorb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.havefunace.top/Article/details/gtzvcywyjy.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gtmsthamid.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtgmpvmztb.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gtfjuqalgv.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtqosgbhpq.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtcarmaino.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gtzlrpafxq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gtlblwxqof.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gtwmmljffq.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gtjxbllllo.html

[D16] 求和与平均值
来源：http://dali.yuanzhike.top/Article/details/gthfzpevlu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtrlnrfcks.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtppigaoms.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtvleoalyp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtyqupieky.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gtssxyodib.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtgzweaehq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.iojbl.cn/Article/details/gtrtghfkwu.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gtiwqcystw.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gtsxzdkznv.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gtkpvtpqry.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gthkzfibpi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdnzhyvx.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtzqvqwtgm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gttrcxzspc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gtmxyvzvfw.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gtfqrginye.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtdnqbncae.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtukysynor.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gtwrpoeuvg.html

PHP:  array_merge(...$nested);
来源：http://dali.shzxlz.cn/Article/details/gtsnotwdvp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258.top/Article/details/gteseubseg.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gtfctsgvmi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtocjdfsti.html

Go:   // 手写双层循环
来源：http://dali.aizwys.cn/Article/details/gtofzzfeuo.html

Ruby: nested.flatten
来源：http://dali.xinyue.icu/Article/details/gtkelidmdg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtybmlhjpt.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gtkplbshjm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gtvvdbrqfy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gtnxachrhi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gtoptvjjzy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtpblypsnz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gtooiqqbih.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gtpxdkwxhx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtcwdvuxan.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuetiantiany.cn/Article/details/gtoqloetjx.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gtybmlpbbe.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gtgrkvehhp.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gtzjmjulti.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtlbrgbmqa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtbdbmhaiw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gtpfraxebm.html

Go:   // 手写 map[T]int
来源：http://dali.xuanzx.com/Article/details/gtseuuxpko.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gtvptbazcl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gtovmdsucg.html

[D21] 判断是否包含某元素
来源：http://dali.yuanzhike.top/Article/details/gtwkxthvwa.html

Py:   x in arr
来源：http://dali.9152youxi.cn/Article/details/gtvrsxibbl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtnyybvkpv.html

JS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtdspvsrmi.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtbzvgnfyg.html

Java: list.contains(x)
来源：http://dali.jiagoushi.top/Article/details/gthkfxrvpe.html

Go:   slices.Contains(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtfiphpygh.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gthajuijge.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtyukpckcv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gtfiubungn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gtswuoeuwa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gtkiexcmqp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ydzc1.top/Article/details/gtozgeheyx.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gtcicwxvnc.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigfzy.top/Article/details/gtskvpvivd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtqykaxyco.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gtnbcspafu.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gtivnjffsf.html

[D23] reduce 累积计算
来源：http://dali.zycfv.cn/Article/details/gtjbrjsuat.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gtzpyyytkt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.316326.xyz/Article/details/gttdqhldnf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtzngurlcf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtlotvdwzh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenlongwang.top/Article/details/gtpqgdmdhn.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gtfcnxklcd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.havefunace.top/Article/details/gtroodbeod.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gtdsbhsfhb.html

[D24] 字典 / Map 基本操作
来源：http://dali.fengsongda.top/Article/details/gtgjsfiext.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.quarkkingdee.top/Article/details/gtpmarpsmt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gtfpzpgyfl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtdhkdqljj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtdzfjhvef.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtrdjbiosk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtruzyzmfi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gtissbftnr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pycfn.com/Article/details/gtalxyhlpk.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gtezqcykrb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fengsongda.top/Article/details/gtwyyjdxhe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xziqi.cn/Article/details/gthjgixtem.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gtxjsbhmmc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gtxhwerald.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtrkznubth.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sweek.top/Article/details/gtseclugrv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gtclicfnbe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cheryme.top/Article/details/gtqaqhmvpn.html

[D26] 数组转字符串
来源：http://dali.ehwqpu.com/Article/details/gtbddwplup.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gtyjxpdagd.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gtuyhvujhf.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgrztzed.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtcwnrfzld.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlguwyymh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gtjmalylpc.html

Ruby: arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtytvoutqp.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtkruijcql.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtiqzzjcjx.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsyjsplb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtpruyrxhf.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtfuvnrmgp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gzhubu.top/Article/details/gtwzveecao.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gtfbgoykag.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtofvqomrl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtojehadkp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhengqikj.top/Article/details/gtdaxvdpwj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gtinrtbylg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ivvv.top/Article/details/gtauyiytng.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtykcthplh.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gthklacoim.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnqekeel.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gtmkboyztb.html

JS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gttnijzlds.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtpawovims.html

Java: "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtcqyebwnr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hysaishi.cn/Article/details/gtepgjfoxs.html

Ruby: "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtxfixjthx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gtxyvxwlxk.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtnevhqduj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guowangkeji.top/Article/details/gtainmcwmp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsjjpiiw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtesnoklmb.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gtfpiynqjl.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtaptuuish.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtmnwmaazf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gzhubu.top/Article/details/gtybjqjoos.html

C#:   s.Substring(1, 3)
来源：http://dali.snrcjt.cn/Article/details/gtvwyvbico.html

[E04] 查找子串位置
来源：http://dali.gogol.net.cn/Article/details/gteaciwwew.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtlwdfkgbo.html

PHP:  strpos($s, "x");
来源：http://dali.dianchejie.cn/Article/details/gtllvxtzvc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.0kj1m.cn/Article/details/gttndlupxw.html

TS:   s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnknfcxse.html

Java: s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtcduqdrlw.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gtdtwqffrv.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtqdllrgeq.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgkivsax.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jiagoushi.top/Article/details/gtjlcgjjqx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gtjnzlxvhs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258888.top/Article/details/gtkkqowyjg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtdtpedpxt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuxming.cn/Article/details/gttcxrxuyv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtnladysph.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ydzc1.top/Article/details/gtwqdkahee.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ppjwa.cn/Article/details/gtjjtxlikx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtcuhipxxf.html

[E06] 替换子串
来源：http://dali.hfpthk.cn/Article/details/gtljpzcqzp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtmxwuhhpa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gtsnavzkif.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjqowczr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtcxlxdmgr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtiqcmsuav.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtqozpsmzw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gthpnfkqmw.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkzczlmh.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gtpndeispm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258888.top/Article/details/gtnootpizq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnlgqslj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yonumen.top/Article/details/gtaazfdosr.html

TS:   s.split(",")
来源：http://dali.zdqjudy.top/Article/details/gtdxlrdvpb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxinkj.top/Article/details/gtsezoimsk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gtcwotjjvi.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gtnlggnhqe.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuanzhike.top/Article/details/gtctchdbln.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gtqaiqnwkx.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gteyeawvez.html

PHP:  implode(",", $items);
来源：http://dali.zhoulong.xyz/Article/details/gtrmkgmals.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtierkklbi.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtpyvgkjbg.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbeacofkg.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gtswivjrpi.html

Ruby: items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtwlwipbsa.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtxyvkctma.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gtgpalmtms.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gtiozagwxy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtyyczrqlv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtefhbwdib.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtdzrieqbc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtyojjgmax.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhengqikj.top/Article/details/gtmncddpkq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gtlvdbbegy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hammf.cn/Article/details/gtdejwkplz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hfpthk.cn/Article/details/gtkqshvqtj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gthmcxpqdp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtncdymxlz.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtphswmrac.html

TS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtdcsnjwnc.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtlxuraakf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtvffswcvg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtnxsgglpy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gtrgmablis.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gtaugkuuvj.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjessmuc.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtyynuhqgf.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtlzlysmpg.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtztbmvsux.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtqpqsbhjz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhixingplan.top/Article/details/gtyxivbflg.html

Ruby: s.reverse
来源：http://dali.mhx1999.top/Article/details/gtitijshtz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtfmdajzyf.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gtfbhuyofs.html

Py:   s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtwjabfozv.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gtbevhskii.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmubxrehd.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtrkmqbyog.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gtistwqxyx.html

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gtbniungvi.html

Ruby: s.count("a")
来源：http://dali.smart0.xyz/Article/details/gteochxlmy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cashguo.top/Article/details/gtikyehxfc.html

[E13] 逐字符遍历
来源：http://dali.yuanzhike.top/Article/details/gtvrqsjqqm.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gthgwqmcsg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtbxsvvaqq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtawjyznuw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonbfnlky.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtolkutzfi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yueranfly.top/Article/details/gtsllbiplo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gtkoqnywxm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hammf.cn/Article/details/gtmszgqanv.html


<!-- 参考信息 -->