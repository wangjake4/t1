代发 wailian999

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fengsongda.top/Article/details/gtwfghntkf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhiwuduotai.top/Article/details/gtcntokvew.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gtstipgxtr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtmxnjkjud.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtdjugdiga.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtwyydbgul.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gtjhualvwa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gtpmkzfnyj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gttnfgqpqk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtyjtnkdbh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtrrrqdcdv.html

[D06] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtcvtyekly.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnjslvuj.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gtihdphyqm.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtzyogawrk.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gtytdlxggm.html

Java: list.size();
来源：http://dali.dashuyun.cn/Article/details/gtilxrvagx.html

Go:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtuctkbbfd.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtqbuurdhj.html

C#:   list.Count;
来源：http://dali.zdqjudy.top/Article/details/gtawimwovy.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gtomoiyvve.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.snrcjt.cn/Article/details/gthcxzqktk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xziqi.cn/Article/details/gtirdddqtx.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtybsnprpf.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtlfnulduk.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtedhpzsne.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gtxvlgvpao.html

Ruby: arr[1, 3]
来源：http://dali.zycfv.cn/Article/details/gtjrghmbmz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtpcwtgcyx.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gtgvnvdnsu.html

Py:   a + b;  a.extend(b)
来源：http://dali.yanxiufei.cn/Article/details/gtbsftorwv.html

PHP:  array_merge($a, $b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjsbaqsy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.feifeiyinyue.top/Article/details/gtjdofztcu.html

TS:   [...a, ...b];
来源：http://dali.tian-w.cn/Article/details/gtgtzjbchx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gtlfpzbxkg.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gtvxwopfjz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hammf.cn/Article/details/gtdaxfswtv.html

C#:   a.Concat(b).ToList()
来源：http://dali.meibo888.top/Article/details/gtiylbbgzb.html

[D09] 排序（升序）
来源：http://dali.yuanzhike.top/Article/details/gthfsodnww.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtyetzxsmw.html

PHP:  sort($arr);
来源：http://dali.jyoumei.cn/Article/details/gtavbdzxgn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangshuangyany.cn/Article/details/gtnrakhypw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gtawrclubj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gtquyxqxfs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtdkobfpih.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtazhdbpdr.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gtmwxwkkpq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhiwuduotai.top/Article/details/gtqoyftfuj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gtyppnwzty.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtbzxfegoq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttocggkes.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtxtwbnucx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangdashe.top/Article/details/gtbjblzqrd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuetiantiany.cn/Article/details/gteqcbwmpu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yongpay.top/Article/details/gtmghsfgcg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gtuumkrblb.html

[D11] 反转数组
来源：http://dali.hongshengwenyu.top/Article/details/gtaagxoizy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxinkj.top/Article/details/gtsvmvrdux.html

PHP:  array_reverse($arr);
来源：http://dali.andypj.xyz/Article/details/gtbjrwfmsf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gttnnugxky.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gtdnuafwnx.html

Java: Collections.reverse(list);
来源：http://dali.wangdashe.top/Article/details/gthuserbse.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtqpjcnjvb.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gtqpijkrxu.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gtrxljlxxz.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gtmdhfvabj.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtqfxzxrqv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258888.top/Article/details/gtauotjlmw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtocvsduag.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtnexxvqhr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.redwolf501.top/Article/details/gtptqubpxt.html

Go:   slices.Index(arr, x)
来源：http://dali.sweek.top/Article/details/gtkftjdntf.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtmyolzxwn.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gthwoknrzt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhkqqhnn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtcdpsagzx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtczhakoxc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtispnmjog.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgoxolyx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ybcxt.top/Article/details/gtjryfuewy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gtjawqqsbe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigufen.top/Article/details/gtzruglxwm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gthsznxnbj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuxming.cn/Article/details/gtmfndmzko.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daria6918.cn/Article/details/gtxwrpvkhv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgarddov.html

JS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteulceuzg.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtthfrieuc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtcbigphke.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gttcxeiczw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtmthuelni.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtkjpuuvjb.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gtogmzgffg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtggysgkyn.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gtsymrqacr.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtentglftk.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtyruzbtjt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgufenzy.top/Article/details/gtvsocxsoa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gtogyyibrh.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gtfsyrcvcp.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gtvanzvfhn.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gteolypulq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtqdzcfikv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fzhhl.top/Article/details/gtdobdwtxl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtnfnnmill.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtghcpkfwj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj202588.top/Article/details/gtppohvjhv.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gttmmumakm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gtkmwjzuhn.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnxiangtu.top/Article/details/gtaucpyxch.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gtfkkspqhi.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwzohsqo.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gtnzxchtts.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gtwrvcoiwy.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtatttctlo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nwbrower.top/Article/details/gtelwfxwui.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gthfkijykm.html

Ruby: arr.max;  arr.min
来源：http://dali.zhixingplan.top/Article/details/gtomrknbwd.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gtsutrualt.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtslbkfalw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjvovttm.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gtqggzeqfp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzbangrr.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gtzpxwlgqy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nwbrower.top/Article/details/gtvitngjnv.html

Go:   // 手写双层循环
来源：http://dali.yanxiufei.cn/Article/details/gtjiphsrff.html

Ruby: nested.flatten
来源：http://dali.dashuyun.cn/Article/details/gthenquwzg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtkvbnfubn.html

[D19] 按字段分组
来源：http://dali.xinyue.icu/Article/details/gtgkxaghuf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gtouardiee.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gtwixduqqi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cashguo.top/Article/details/gtaxvlepuz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtguwrxils.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenlongwang.top/Article/details/gtpbevwcbi.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gturgdxtvu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gtrrtfjrju.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenlongwang.top/Article/details/gttzfcjktg.html

[D20] 统计每个元素出现次数
来源：http://dali.yvedp.cn/Article/details/gtzcgphmvj.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gtwpwbcivg.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtfzxprfji.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtkxeruryj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtpfhuxvhw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gtfcctticp.html

Go:   // 手写 map[T]int
来源：http://dali.wangdashe.top/Article/details/gtiuanhcra.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gtnzsewrkb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gtcrbcpzkm.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigfzy.top/Article/details/gteaeojvzv.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtvidleogx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtzgouxmlv.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtvzvmsogx.html

TS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtrzqzalzh.html

Java: list.contains(x)
来源：http://dali.birdmap.top/Article/details/gtrafwhjdb.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtovzhasvc.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtezselegi.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtnyrpmaoc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gttazgjmof.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gtdorqcbcm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gtnzxrfomz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gtzrdlpqhq.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gtonrhjmis.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gtbbxytbgs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sufxvd.cn/Article/details/gtvayeppvn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjunbahxb.html

C#:   new List<int>(list);
来源：http://dali.snrcjt.cn/Article/details/gtqlrbkkph.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gtbkgbilkp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangdashe.top/Article/details/gtpbepmspo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gtakrwieen.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtnchswvvg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtnywdfygt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gthuwuspic.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtqkvifrve.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqjhmfeh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthujrolmp.html

[D24] 字典 / Map 基本操作
来源：http://dali.aizwys.cn/Article/details/gtdmpprdny.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gthhldragq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnqzz.top/Article/details/gtswvbnrbf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gtvmwdgaau.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtfcmstggm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhengqikj.top/Article/details/gtlmdblslq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.iojbl.cn/Article/details/gtoiraleom.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigufen.top/Article/details/gtvnllxdwr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.vqdsnc.cn/Article/details/gtvamcyzkc.html

[D25] Set 集合去重与交并差
来源：http://dali.shuidangran.top/Article/details/gtjfakcnsq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenlongwang.top/Article/details/gtcfmyrrde.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fengsongda.top/Article/details/gtbkikyymx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hfpthk.cn/Article/details/gtlowgomac.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hysaishi.cn/Article/details/gtewoiirgj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gthrrcubkk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangdashe.top/Article/details/gtsoaxmdhk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gtfjihdiuk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtyikoxmcc.html

[D26] 数组转字符串
来源：http://dali.yonumen.top/Article/details/gtjofeqwwr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhengqikj.top/Article/details/gtcmmfllrq.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtxlhzuilg.html

JS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezypekyu.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtxnjxktry.html

Java: String.join(", ", list)
来源：http://dali.havefunace.top/Article/details/gthcbiwwug.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxuanxn.top/Article/details/gtuwcvxbiv.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlecvervv.html

C#:   string.Join(", ", list)
来源：http://dali.cashguo.top/Article/details/gtrblgpdxj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtcvrtehwv.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gtuxequdra.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtsurxcnar.html

[E01] 拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtshoaawiq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cucudq.cn/Article/details/gtozcaghsm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cucudq.cn/Article/details/gttnghjurh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtdoqcvtnn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdqkebdz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gotoacloud.top/Article/details/gtjpsogyas.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gtqjhmoavd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gtbmmhpmxl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtkgkehsik.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gtwfxfehrq.html

Py:   "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gtpevoiiwm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gtktcztuty.html

JS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtqfxxghps.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwskxwday.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtgowgwkpv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.andypj.xyz/Article/details/gtmcvcvayf.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtjcexwoot.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj202588.top/Article/details/gtfjsvmghf.html

[E03] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtzwxvcdeu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gtkaobowls.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gteafxifqg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtlkcbohqm.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gtsvluwcce.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtnqzqhbsg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guannengcc.top/Article/details/gtxhobqewu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gtrhejtitp.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gtzvcvqwdf.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gtskewwgoy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtljkvzrnq.html

PHP:  strpos($s, "x");
来源：http://dali.yonumen.top/Article/details/gtktihxvga.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gtesgmaptz.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtacttfksa.html

Java: s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtsbvayhgw.html

Go:   strings.Index(s, "x")
来源：http://dali.yj202588.top/Article/details/gtcxmwbwxz.html

Ruby: s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtzwpwnwhb.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtacnsksuu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.iojbl.cn/Article/details/gtaryncqtz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtxelrlilx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjqajzwx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gthnpultej.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gtyxmpacdb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtugcyujej.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgfzy.top/Article/details/gtqgbcezro.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtfjpbwnuv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtwyhdfrth.html

[E06] 替换子串
来源：http://dali.mhx1999.top/Article/details/gtyijlnhvf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gthkwdzfnq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gtaenqqzfw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtvbnkufzn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtrpaimqlz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gthkynpaxf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gthcekjwhz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtcmcyepbv.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtipezbruq.html

[E07] 按分隔符拆分
来源：http://dali.aibaodan.cn/Article/details/gtbxbvcbna.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtxgmkdkaf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtistqloqq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ybcxt.top/Article/details/gtirjqkzgy.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gtxvspwyve.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gtbazcfpcj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gtwpxqcemq.html

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gtygtvppkl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpajiyip.html

[E08] 数组按分隔符合并
来源：http://dali.shangyingyoupin.top/Article/details/gteyteudrh.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjrjymql.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gtxbsiimki.html

JS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtvqhnxkue.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtwiadvqlw.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gtmlqcuxtn.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gtaapvnkhy.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtbfcxegpa.html

C#:   string.Join(",", items)
来源：http://dali.cashguo.top/Article/details/gtcpgxczcw.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gtuownkubj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gtcjaqpnsr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gtulqhovej.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtcsbocdkd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gtvwtbrhqi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtrssgbgia.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fzhhl.top/Article/details/gteemwufwp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tian-w.cn/Article/details/gtbubrwsqn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtehrkfene.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gtguqhrcad.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtbogpprgc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gtsvjhfjmf.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gttywndyob.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkunhwbjg.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtnzwtmekg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtdcqiuhhg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtyacnjsjq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gtulnrztdk.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklrieync.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtezsuuvnw.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtokhtjetp.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtybzjsint.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtkqoipeyh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gtptvrimvv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtkmmaiztx.html


<!-- 参考信息 -->