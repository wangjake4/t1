代发 wailian999

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtctzheyft.html

PHP:  count($arr);
来源：http://dali.yongpay.top/Article/details/gtkdjsndqd.html

JS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtkigenass.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtlfrkovir.html

Java: list.size();
来源：http://dali.pycfn.com/Article/details/gtwblloxbr.html

Go:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gtujeoidkm.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gtticazoxw.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gtrhjiiqrs.html

[D07] 切片 / 取子数组
来源：http://dali.jyoumei.cn/Article/details/gtlwjzjuva.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gogol.net.cn/Article/details/gtyxwmrhke.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnqzz.top/Article/details/gtxjnaijpm.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtwrgvmyko.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtsfdbwcfk.html

Java: list.subList(1, 4);
来源：http://dali.yj202588.top/Article/details/gtqiqdhbyf.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gtxfijtqax.html

Ruby: arr[1, 3]
来源：http://dali.quarkkingdee.top/Article/details/gtkbbbshyj.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtcrxslwci.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gtpennkbwq.html

Py:   a + b;  a.extend(b)
来源：http://dali.andypj.xyz/Article/details/gtxyrppdts.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gtdwfllmfh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gtwwjdhqug.html

TS:   [...a, ...b];
来源：http://dali.andypj.xyz/Article/details/gtcelzlzud.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gtjtsftmpy.html

Go:   append(a, b...)
来源：http://dali.mhx1999.top/Article/details/gttqsjrvsh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fengsongda.top/Article/details/gtxsggxqjq.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtclbuggoz.html

[D09] 排序（升序）
来源：http://dali.pycfn.com/Article/details/gtqaqxhaux.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtgvjdgxsx.html

PHP:  sort($arr);
来源：http://dali.haohaochexian.top/Article/details/gtlfgrjrkw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gtgzlqzckx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdukaaua.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyjtkkvd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtpoucgcfd.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gtsbybakmg.html

C#:   list.Sort();
来源：http://dali.zhengqikj.top/Article/details/gtxdakdyet.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gtvnccnlwo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxinkj.top/Article/details/gtmdtoaaip.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gtprqhbggd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtupqjvdji.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gthgpugspt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gtkyzwprft.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gtzwwyxhon.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtbtwquldx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhongyouzk.top/Article/details/gtaokelfzh.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gtcxetzbrj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sxryk.cn/Article/details/gtpolkiycz.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gtjrngjomg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.9152youxi.cn/Article/details/gtahvxqrxi.html

TS:   [...arr].reverse();
来源：http://dali.cqqwz.cn/Article/details/gtmdiczktj.html

Java: Collections.reverse(list);
来源：http://dali.guowangkeji.top/Article/details/gtoetxojwr.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtpvzfjhyl.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gtykrspzft.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegugfejp.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gtcsusneqa.html

Py:   arr.index(x);  x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtoyojbyqz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gtyqtfradu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtoojkszui.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtmuyydqed.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dashuyun.cn/Article/details/gtwssxcgxi.html

Go:   slices.Index(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtdkzbsicr.html

Ruby: arr.index(x)
来源：http://dali.zhoulong.xyz/Article/details/gtvjxynakl.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gtjxqdtzoi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gtywhbqxys.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cdnleiting.top/Article/details/gtrzgedmkd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnsexfrm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gtsvurtqxy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtpamtcxme.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuanzhike.top/Article/details/gtneroyzvm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jlsjyb.cn/Article/details/gtavldhqos.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.kuanghao11.cn/Article/details/gthqiflifv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gtvtwuhhuu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gtlvjwspon.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cashguo.top/Article/details/gttkzemuqn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtpbrjmmbm.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gtubskdxbd.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gtnvgekxcx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gtlbtvmgyw.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gtksmdhisf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtwwstjhqb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpysgfsni.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gtohrrexgr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtxrendesv.html

PHP:  array_unique($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtbhqhvopi.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtwkonuxjp.html

TS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtmfqfrcjq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gterwptdql.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nwbrower.top/Article/details/gtfckbyldk.html

Ruby: arr.uniq
来源：http://dali.fzhhl.top/Article/details/gtinsidvpf.html

C#:   list.Distinct().ToList()
来源：http://dali.hfpthk.cn/Article/details/gtxnlejpxm.html

[D16] 求和与平均值
来源：http://dali.nanxuanxn.top/Article/details/gtrqlgdcas.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtpkofpiyv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtvlrdglnm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gtqvegoqju.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gttvsckumq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hfpthk.cn/Article/details/gtmqafehby.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gtsqruiuei.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ppjwa.cn/Article/details/gtnabjuekg.html

C#:   list.Sum();  list.Average()
来源：http://dali.havefunace.top/Article/details/gthspeiyis.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gtzhhsazdd.html

Py:   max(arr);  min(arr)
来源：http://dali.redwolf501.top/Article/details/gtyftzfyjp.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtlyiigqdo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gturabnfqc.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gtjcdrfwen.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangdashe.top/Article/details/gtreetmjok.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtuptxjeou.html

Ruby: arr.max;  arr.min
来源：http://dali.tianlin.xyz/Article/details/gtzwrwxnpr.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgufenzy.top/Article/details/gtypzidfss.html

[D18] 扁平化嵌套数组
来源：http://dali.yanxiufei.cn/Article/details/gtlvgxnqtr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gtfsaxmfpp.html

PHP:  array_merge(...$nested);
来源：http://dali.gaohongyu789.top/Article/details/gtwfenwtcm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yanxiufei.cn/Article/details/gtriqymgqu.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gtheguanug.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tianlin.xyz/Article/details/gtcbykvgci.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtwjljtlxz.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gtdloxfhuq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtycjjkfsn.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gtalzcjyrt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuanzhike.top/Article/details/gtywithuen.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gthbocbvhq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.meibo888.top/Article/details/gtvqjdjcal.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtidgmnnwj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gtqhmgledc.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gtqmqtnwca.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoajkwscv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.9152youxi.cn/Article/details/gtphfyojmr.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gtmehlgisq.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gtmyxnprer.html

PHP:  array_count_values($arr);
来源：http://dali.fengsongda.top/Article/details/gtyxgqcfbt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtyofmjhhv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gttxmnirsc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gtgjysordw.html

Go:   // 手写 map[T]int
来源：http://dali.aibaodan.cn/Article/details/gtzhmekxij.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gtpfuptdrx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gtjvwoxbxc.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gtqgtwaowv.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gtudazedmk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hammf.cn/Article/details/gtcuuxlwqo.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtheforkes.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gtxithmsav.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gtiqnesgba.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtywtdrxic.html

Ruby: arr.include?(x)
来源：http://dali.jiagoushi.top/Article/details/gtcykumwxo.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtpcsxdbvi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gtfcyxmcbk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gttzfsjwtm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gtwatvbrmc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gtgypasjde.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gtfxhxdrtk.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gtqgjdvxzl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gthdfivpfh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gtjxsstljp.html

C#:   new List<int>(list);
来源：http://dali.jinqigfzy.top/Article/details/gtbggrajyl.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtfrqshnay.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenlongwang.top/Article/details/gtkxgcitnc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gtjoqzmwtl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtiwgvczxz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtzxoqgkjf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gtwlbqhlsy.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gttavkguzm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gtghojzuet.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gtwihcjbja.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenjidiqi.icu/Article/details/gtoatmbkii.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gtjyvypxbb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtjfpqfpfi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtclfyjjti.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtpzdvpwrk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gtqgpkjbvt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtpkapnpnz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gtrbrztkhy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlkrcidu.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gtusdwvobb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gthayybdri.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dashuyun.cn/Article/details/gtfsvabnyt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gtnivnnwdt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.iojbl.cn/Article/details/gtmmpkoete.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gtnuqmsqpu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigufen.top/Article/details/gtkgxmyeub.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gtjadknhab.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtrvwvdgfm.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtotofisoc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jiagoushi.top/Article/details/gtrniqlzoe.html

PHP:  implode(", ", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtreclmaqt.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gteknqfqrw.html

TS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtpcvdiwyl.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtpcvnrwiq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sufxvd.cn/Article/details/gtwdtwhnsv.html

Ruby: arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtajhzwxcr.html

C#:   string.Join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtqubuwkqs.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpozashrb.html

E. 字符串处理
来源：http://dali.xuanzx.com/Article/details/gtiqwlbiqi.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtkipbdopm.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtshidoobr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gtnouymggg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gtqafjxkmh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtiksngzsh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuneedgor.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gtuemgftib.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yongpay.top/Article/details/gtyrbzsgvb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtywmtfvrr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtrybrslqf.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtpyowofjr.html

Py:   "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbupipue.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gtcvmlmmxb.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gthnayweao.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtknnvanpr.html

Java: "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtnbaabusv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtcsbcigjr.html

Ruby: "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtdrlxbovk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gtqhmlftuy.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtbixvyxzp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sxryk.cn/Article/details/gtbbnshdnc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtgxihvapu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtzhtstsmn.html

TS:   s.slice(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtihbwbppx.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtpdsleolk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gtklcxelnw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gogol.net.cn/Article/details/gtedlliuya.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gtzlvxjayp.html

[E04] 查找子串位置
来源：http://dali.cqqwz.cn/Article/details/gtwlnnrxmj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtuhxhuzlm.html

PHP:  strpos($s, "x");
来源：http://dali.tanke756.top/Article/details/gtwoszerxp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.kuanghao11.cn/Article/details/gtrajpidmk.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtjkuksqlh.html

Java: s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtztivgtkg.html

Go:   strings.Index(s, "x")
来源：http://dali.jlsjyb.cn/Article/details/gtuiytnnwn.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtsllzafew.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjjuizau.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxinkj.top/Article/details/gtmwucabuq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sysykeji.top/Article/details/gtzsricxrv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.kuanghao11.cn/Article/details/gtbwdaysnc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtprbnelai.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hywenlv.cn/Article/details/gtxhlbperl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtaeepsgul.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gtycwxiqvg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gtuvtrmhnb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtumcgwecq.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqivdgkv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtuyxinnxt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgufenzy.top/Article/details/gtccewkmci.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtjocrhgwb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtjellrtil.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtsolvajip.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gtbykgonrr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtknfemnxw.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gtnawuhxsf.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gtilaontxj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258888.top/Article/details/gtsynskjsb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtvyxapfnp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tianlin.xyz/Article/details/gtnoillzsl.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gtzbunotnw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gtyheqoexu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tianlin.xyz/Article/details/gtqyzufxbm.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gtmsozoqbj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj202588.top/Article/details/gticucgwpi.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gtgkrxbgng.html

Py:   ",".join(items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsgqpbnb.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gtsxcsqqmv.html

JS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnxyydhm.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gttcvyttjz.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtdjqebeso.html

Go:   strings.Join(items, ",")
来源：http://dali.zdqjudy.top/Article/details/gtpdcegmaz.html

Ruby: items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtrvgcdkao.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtccqhidzh.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gtdtfxwklk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gtlvrfriwc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtborfxwtv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gthjjuraqc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpalzghhy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtkxnufymi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hywenlv.cn/Article/details/gtzngvrosm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gtgjfjtecb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoggdkcnu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gthvruclvt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtbuhaazxs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gtjvegsdbd.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtlqnjgxlr.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtsxymatnl.html

Java: String.format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtddgsoaud.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtehoaiqbf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtrsxmewvl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gtvctdmcnt.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gtelpgroky.html

Py:   s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtfshnkgtg.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtdnuladja.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtnuncveed.html

TS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtcbzfbozh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gtbafbvjbv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gtqksoscvb.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gtmabvvsuu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtsaabrqer.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gthmybffha.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtcsjyfddn.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gtgyjidubn.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtvjfjlqof.html

TS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtifssjyyy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gtyfrptwvw.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gttbwppgfq.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtkzpujwev.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtvtfozmsg.html

[E13] 逐字符遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtdaxykdul.html


<!-- 参考信息 -->