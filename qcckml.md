代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gtuxueecnr.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gtlhdheakb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sxryk.cn/Article/details/gtczqrqixv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gtwipudvvt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ydzc1.top/Article/details/gtwzjcmxbh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gtjjcwcjqb.html

[D05] 访问与修改元素
来源：http://dali.bjfxy.top/Article/details/gtlbcqlant.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtxrcgaixj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtuudohybe.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtbfyhaxwb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yanxiufei.cn/Article/details/gtnwiumkjz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnxiangtu.top/Article/details/gtqgcndujg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtrfcyruyh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtimkjksaa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtbpjifxpa.html

[D06] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibuudpvi.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtapjcaauk.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gtzliyamfv.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtasautedj.html

TS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjefjxymm.html

Java: list.size();
来源：http://dali.gotoacloud.top/Article/details/gtipxkyvbw.html

Go:   len(arr)
来源：http://dali.yongpay.top/Article/details/gtrhdgwxvh.html

Ruby: arr.length; arr.size
来源：http://dali.xziqi.cn/Article/details/gtrmzjlenx.html

C#:   list.Count;
来源：http://dali.yongpay.top/Article/details/gtvkafukbo.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrklpyuzz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hysaishi.cn/Article/details/gtxuxxcsbq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtsuadkxjz.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtvsxgitja.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtjadidksj.html

Java: list.subList(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtmbjmgjcg.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gtymdheeny.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gtowyezxow.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtfztlfkqs.html

[D08] 合并两个数组
来源：http://dali.zdqjudy.top/Article/details/gtidutlxut.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gtvjixbwpx.html

PHP:  array_merge($a, $b);
来源：http://dali.chenlongwang.top/Article/details/gtvsbqkyqs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gtalbeicme.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gtwdesyrfn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gtxbkocfxk.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gttvjmotxf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaqcbuqa.html

C#:   a.Concat(b).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtyrmzrvcs.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssplqjsx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtuqvfjyjx.html

PHP:  sort($arr);
来源：http://dali.guowangkeji.top/Article/details/gteimntcdy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sweek.top/Article/details/gtnopqxpqy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tian-w.cn/Article/details/gtvzuaujjb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gtgdeduyxs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtpjnujgxc.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gtnwizfrqd.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gtxftdcwor.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hfpthk.cn/Article/details/gtaormgqhl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ivvv.top/Article/details/gtgcjaocwf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gtlhuuoeky.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gtbaxjrqty.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpipqepzm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gtynqujmgn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gtmpzmiruw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hammf.cn/Article/details/gttvhrfpwp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cheryme.top/Article/details/gtoamxuaxe.html

[D11] 反转数组
来源：http://dali.hnqzz.top/Article/details/gtnjfozlsy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gtedisfkps.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gtsqrwhryq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yvedp.cn/Article/details/gtscdwqcuz.html

TS:   [...arr].reverse();
来源：http://dali.birdmap.top/Article/details/gtwzbfmnye.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gtzcxgyqkr.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gtdubrydfk.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gtwksnwzey.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gtcnvnnkxw.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtniwxpurd.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj202588.top/Article/details/gtdakdlthe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtzaliqmbl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gtvucvtoau.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtpnpubnqb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gtudoxjmmr.html

Go:   slices.Index(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtjwwcaskv.html

Ruby: arr.index(x)
来源：http://dali.haohaochexian.top/Article/details/gtakubqsjg.html

C#:   list.IndexOf(x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxjngsfu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnxiangtu.top/Article/details/gthlwzepkx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gtxbczkdtv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnztuqcqs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtapseyjbc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtyicswutt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtktquxhds.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tian-w.cn/Article/details/gtfwuoziqb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyvclaud.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtolbqdxef.html

[D14] 映射转换（每个元素变形）
来源：http://dali.haohaochexian.top/Article/details/gtklxzfyan.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gtgbpiqcnn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtdgnwdsaq.html

JS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gtzcbkylbx.html

TS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gtsdzmbfhz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yvedp.cn/Article/details/gtzoorzzvi.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gtuieupthv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtceytsmdi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gtlinbrpci.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gtkyisajxv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gthvawhanf.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtzommihio.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtadwhomjx.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gttxhamaol.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.mhx1999.top/Article/details/gtnybzdeif.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gtrqsclkon.html

Ruby: arr.uniq
来源：http://dali.tian-w.cn/Article/details/gtewpbhhtu.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gtiytfqvmi.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gtenncsmbz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtmgzegqxm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtpzynvgck.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiknbyyr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gtxasilxnu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tianlin.xyz/Article/details/gtfgfkcwsr.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gtlxbsrnca.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aibaodan.cn/Article/details/gtvblufhcp.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gtuxmnnoqm.html

[D17] 最大值与最小值
来源：http://dali.jinqigufen.top/Article/details/gttvjfvava.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtiqjkfluy.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gtqwnwkefp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gtouajcnya.html

TS:   Math.max(...arr);
来源：http://dali.nwbrower.top/Article/details/gtjsiyjgcj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtraauwbnc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtaqmcmifv.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gtmmsgocht.html

C#:   list.Max();  list.Min()
来源：http://dali.iojbl.cn/Article/details/gtwjxmdhda.html

[D18] 扁平化嵌套数组
来源：http://dali.sufxvd.cn/Article/details/gtpdsbjfoc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gtkgbbfazz.html

PHP:  array_merge(...$nested);
来源：http://dali.redwolf501.top/Article/details/gtqhlskojk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtwpxvapea.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gtusnzzsnv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtijbwwjyj.html

Go:   // 手写双层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdvdmmxm.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gtgftwjvlu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gthcximfrn.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gtxytkgoju.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gtuvepmsfp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gtrkbmyock.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tanke756.top/Article/details/gtrvmwkqiq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gtjpxtdvho.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gtranuctre.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxuanxn.top/Article/details/gtzcujnzzb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxuanxn.top/Article/details/gtjsbfcbgg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cashguo.top/Article/details/gtvjqlmeio.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtciontert.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtzugiscff.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtxxpibdwv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtvhdmvhin.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtagopupyf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonfkiano.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gtahcysbxu.html

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gtbhzdoozu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gtdjukuicq.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gtufkmaqnk.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtoldjcitf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtofsrsovc.html

JS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtmncseujn.html

TS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtwvhjmvrz.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gtkhqdkvdk.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtnffbonlo.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gtmvzfeujz.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtccypaenu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gtglrpvpog.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gtnxrhurlt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gtrxdyeusf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtmecdqusg.html

TS:   [...arr];
来源：http://dali.feifeiyinyue.top/Article/details/gthictzdok.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpjiibgt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnqzz.top/Article/details/gthplqvmrm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.haohaochexian.top/Article/details/gtkllhcqbz.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gthjusvwol.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gtlwfqjjwy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.snrcjt.cn/Article/details/gtmfdogvlm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtivxyhjyj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmuueudh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtevdcgnfp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gtnlqrfdlz.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtromcrqfl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gtggvdragq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ivvv.top/Article/details/gtynwzzclj.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gtayspxhow.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gtghsislby.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nwbrower.top/Article/details/gtxbuebrjt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gthgvgjbse.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtpuffqynz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gtxwlqypiz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gtewspczpe.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gtlqosahdz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gtfwrjpdpi.html

[D25] Set 集合去重与交并差
来源：http://dali.zhoulong.xyz/Article/details/gtmpvrqgdm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gtinfslvza.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gttjdbrext.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.birdmap.top/Article/details/gtsrtvstkg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmxdamds.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtlohohkyf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jyoumei.cn/Article/details/gtqdegmcai.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gthqfykedj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxiwmyyrp.html

[D26] 数组转字符串
来源：http://dali.pycfn.com/Article/details/gtxzziszxe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gtghylwqra.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbxhldfv.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtgrtypwdf.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtqalsdonw.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtbseogjtl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtfwbbtauu.html

Ruby: arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtkorabcdi.html

C#:   string.Join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtelpjapzp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtsuocjoel.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtcprqoo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbmjdxdss.html

[E01] 拼接字符串
来源：http://dali.iojbl.cn/Article/details/gthbzrqfuu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jiagoushi.top/Article/details/gtyhfqebya.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gzhubu.top/Article/details/gtgqcjrnpx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gthtaufypq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gtdqeiawga.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cucudq.cn/Article/details/gttfwwuvmt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgufenzy.top/Article/details/gthorifaol.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gtaksoplzq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtelsdslct.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpglgrsr.html

Py:   "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gtlfvnbmft.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gtzulvzyot.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtmvljopmc.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtefhdiftt.html

Java: "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtqorerqab.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gtmntlqhje.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtpmijjpum.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gtaeefpyhu.html

[E03] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gteoxvinqr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gtqvnlyybc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtoebmfcgw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtqkdybfbb.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebegedrn.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtzskcfyll.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtzymitgdk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gttezdknvx.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowjsmbym.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gtfawvzetv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtezzjnnkd.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gtcgkevfxt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xziqi.cn/Article/details/gtekosgwvh.html

TS:   s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtjkwzybvj.html

Java: s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtyzgvtrki.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigfzy.top/Article/details/gtczdjwuru.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgvrkmix.html

C#:   s.IndexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytnwtstl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gttxaijgws.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.9152youxi.cn/Article/details/gtixmvmhvg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yongpay.top/Article/details/gthnfahhnl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtlhapnorc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtxconknut.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtqeskrltg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gtyppgyqmb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xylfe.cn/Article/details/gthjybopte.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtcvogkzmg.html

[E06] 替换子串
来源：http://dali.tian-w.cn/Article/details/gtvhygflfw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gtijlzjlxw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jyoumei.cn/Article/details/gtvwpuzmrk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtcwpospsr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtguulixch.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtoyhmsyaj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gtjqlrmzgl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtbgiigpuz.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gtbyowhppt.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gthlddssfh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhixingplan.top/Article/details/gtqcmbyjsh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtevetqref.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yueranfly.top/Article/details/gtleathkfw.html

TS:   s.split(",")
来源：http://dali.c1oappe.top/Article/details/gthowgblqo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gtiukrnpou.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gtrvusolfv.html

Ruby: s.split(",");  s.split
来源：http://dali.hnxiangtu.top/Article/details/gttpskvmmu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gtloeofcin.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gtszpifopr.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gtsvufdawj.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gtjzcnngbc.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtuwxaaecu.html

TS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtdrgxbqtb.html

Java: String.join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gtlrriulkl.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gtepbipobj.html

Ruby: items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtgxzoelmu.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gtmxvnxalk.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gtcftynqgz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gthrgilhsj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cucudq.cn/Article/details/gtancjilfz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtdnbhwyej.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtymskvosb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtxipjleng.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gtiibtohai.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gtgbpqdepp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtngpnjmhi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gtwpywtxqb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtexrusrte.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gtkgxdpmmr.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtewngmevn.html

TS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtkouggoyp.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtzaqtqewi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtmltpumvx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtucsamada.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gtqjaauzxf.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtpwxyfwps.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtydwevnjx.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtanasiqjy.html


<!-- 参考信息 -->