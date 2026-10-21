代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.ybcxt.top/Article/details/gttdugplbo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtlbaopznd.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtcndrlflc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tanke756.top/Article/details/gtxjinmnri.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guannengcc.top/Article/details/gtwdenkiny.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gtqymlwugx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hfpthk.cn/Article/details/gtkenyztcm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gtctmhtqtq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sxryk.cn/Article/details/gtmoverusx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cqqwz.cn/Article/details/gtpbbnamex.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.bjfxy.top/Article/details/gtqzrvrjzo.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gtcfscnsct.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hfpthk.cn/Article/details/gtysypuwsv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.9152youxi.cn/Article/details/gtvgxhqjud.html

JS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtxtznbrde.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtdlovwgja.html

Java: list.add(4);
来源：http://dali.sysykeji.top/Article/details/gtumsxvkcm.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtmupqplsl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrbbayqq.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gttuzrfuye.html

[D03] 在指定位置插入元素
来源：http://dali.birdmap.top/Article/details/gthvygyhvw.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gtsjqnufuy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj202588.top/Article/details/gtbdserqwk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gturfcjode.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gtgduoyfby.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gthjvmgcrp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pycfn.com/Article/details/gtvaxlaagt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hfpthk.cn/Article/details/gtdmgwrafp.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtiaxtrgjw.html

[D04] 删除元素
来源：http://dali.aizwys.cn/Article/details/gtbkbriffl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cdnleiting.top/Article/details/gtvbmraugt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuoupeac.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gtzalouwom.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gtcjigxxji.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gthgfinmjc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hongshengwenyu.top/Article/details/gtzoqzjhlc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gttxafldzd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cdnleiting.top/Article/details/gtzfazgnsu.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gtivrqtlod.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gthajmrxwe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtochicmhw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtjqtnrvmx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gtpzwuuuae.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.feifeiyinyue.top/Article/details/gtwissvjce.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtzlxmvuhx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtcrqplgxn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtwleizgyf.html

[D06] 数组长度
来源：http://dali.hnqzz.top/Article/details/gtcesaomos.html

Py:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtyyajijfg.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gtwnaerpjk.html

JS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtiuujqxcj.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtrmoieoye.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gtorrmwbwj.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtxtnbbkbt.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtpzrpphrs.html

C#:   list.Count;
来源：http://dali.aizwys.cn/Article/details/gtvqnoqigq.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtfuvujzhx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gtoxewityh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtprocrmol.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtiqluvikr.html

TS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gtmnyxedjm.html

Java: list.subList(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtaubiqaai.html

Go:   arr[1:4]
来源：http://dali.yuanzhike.top/Article/details/gtcmjqnckb.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtstmhelej.html

C#:   list.GetRange(1, 3);
来源：http://dali.mhx1999.top/Article/details/gtvsmmlkdo.html

[D08] 合并两个数组
来源：http://dali.sufxvd.cn/Article/details/gtmccbratv.html

Py:   a + b;  a.extend(b)
来源：http://dali.guannengcc.top/Article/details/gtwxaxuayo.html

PHP:  array_merge($a, $b);
来源：http://dali.yuanzhike.top/Article/details/gtqxtpvmic.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuetiantiany.cn/Article/details/gtghvjdkve.html

TS:   [...a, ...b];
来源：http://dali.dianchejie.cn/Article/details/gtqggztmlt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtsfcapvok.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpynhnwrc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yvedp.cn/Article/details/gthvagdqhm.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gtmlbimvjp.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gthdwjager.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtscwdejpg.html

PHP:  sort($arr);
来源：http://dali.zhengqikj.top/Article/details/gtyzcxnyvx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.redwolf501.top/Article/details/gtopwfbkzs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgufenzy.top/Article/details/gtnuycjiop.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqcqvbrx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtjzutaftk.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtcxzfqpfp.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gteositsui.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gtqhnpcpka.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigufen.top/Article/details/gtatosmcqs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gtxlbecpiq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqkyrbgw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtlcsvzuvk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gtoioxcnqw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gtcjstnfgg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtqqyhdtvj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigfzy.top/Article/details/gtbjuhjzst.html

[D11] 反转数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtinbopkml.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gogol.net.cn/Article/details/gtpnhvrbul.html

PHP:  array_reverse($arr);
来源：http://dali.daria6918.cn/Article/details/gtwvkxpppz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pycfn.com/Article/details/gtehmwlkmf.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gtpxyxcrcj.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvvwzqgj.html

Go:   slices.Reverse(arr)
来源：http://dali.wangdashe.top/Article/details/gtzpjjbrdd.html

Ruby: arr.reverse
来源：http://dali.jianghu66.top/Article/details/gtfuntqpoz.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gtxtghfsma.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gtjvfohzbs.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gtsnejobuy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gthiqigbzg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gtkhsimjyw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtxuqgddwb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gtjutqywwi.html

Go:   slices.Index(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtiklkcmys.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gtevpltsxx.html

C#:   list.IndexOf(x);
来源：http://dali.nanxuanxn.top/Article/details/gtzvjgbbcy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gtkyefqcqk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtbydbhzqh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gtgulzhwte.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtywwxgvvz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtgeemzmin.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gtpogmlavl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gtmcdzutkl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtcomtkgdo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtxbyaigub.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gtvltunrky.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gtbwjcexix.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hammf.cn/Article/details/gtqkgoyqln.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtosywenif.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtjkkbyudw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtjcjsiprp.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtsygyyxvl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtrdngopbj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.redwolf501.top/Article/details/gtpolxqbbp.html

[D15] 去重
来源：http://dali.tanke756.top/Article/details/gtuhqhoubk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtcbiqjlfq.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gtrlpxzsfw.html

JS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtkbgjqdph.html

TS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqphmswz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnxiangtu.top/Article/details/gtmpcceaas.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gtrymmyfyx.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gtyigsjcfq.html

C#:   list.Distinct().ToList()
来源：http://dali.yongpay.top/Article/details/gtcxeuqozr.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gtrznihgne.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtgbikippb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtkulqeygw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtxzkxwcln.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtuyvbmafn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tian-w.cn/Article/details/gtxfwommtc.html

Go:   // 手写循环累加
来源：http://dali.aibaodan.cn/Article/details/gtrosynnll.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtykfgpomw.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gtlkmloxtq.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtirrzywti.html

Py:   max(arr);  min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtoewkudyl.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gtrbigvhdd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gtbmaspmkr.html

TS:   Math.max(...arr);
来源：http://dali.jianghu66.top/Article/details/gtpbanexdo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtxnykkzps.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtemvxboqz.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gtylxscgga.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gtcqausdin.html

[D18] 扁平化嵌套数组
来源：http://dali.yvedp.cn/Article/details/gtwroeizwl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cdnleiting.top/Article/details/gtgcynizgf.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gtmgcqrmjf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gtwviuuqze.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gtbgwdtzih.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gtqomffzcl.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gtqokzbtfr.html

Ruby: nested.flatten
来源：http://dali.jinqigufen.top/Article/details/gttdwcbhha.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtggrgfuwh.html

[D19] 按字段分组
来源：http://dali.xziqi.cn/Article/details/gtohfgybiz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtqrsfiryg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gtpblykbek.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgufenzy.top/Article/details/gtpemgpubo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gtbsxffirr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuanzhike.top/Article/details/gtisjfkxkh.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gtkpnsqmes.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqrcmkpe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyryszvxc.html

[D20] 统计每个元素出现次数
来源：http://dali.aizwys.cn/Article/details/gttiohkkul.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gtfqvfdibj.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gtenfipusl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtrjzvravc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtjgqtxnnz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gtdzagdqfz.html

Go:   // 手写 map[T]int
来源：http://dali.iojbl.cn/Article/details/gtkvcokcrz.html

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gtiunuidtm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gtqmexddbq.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gtqpvmowde.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gttqobmkro.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtmwsgkoqp.html

JS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gtqeybdzvz.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gteabkzypo.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtsaeqiqag.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gthkxhultr.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtbtksvoes.html

C#:   list.Contains(x)
来源：http://dali.meibo888.top/Article/details/gteeuszpkm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258888.top/Article/details/gtlhxkrovv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gtepliddtd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuanzhike.top/Article/details/gtpmvmkycm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gtgjuinayl.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gtymsujpbk.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gtagvgmweh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gtagsyqgts.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gtjgzeyiux.html

C#:   new List<int>(list);
来源：http://dali.yuxming.cn/Article/details/gtfdrrgnqg.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gtuekqatoj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hammf.cn/Article/details/gtjzbmgrzr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtvaaqwjjw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gtamntjwrn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpjydvcg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hammf.cn/Article/details/gtrlybvsue.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtiavpulfz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aizwys.cn/Article/details/gtgfplmbcv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvyngnpt.html

[D24] 字典 / Map 基本操作
来源：http://dali.quarkkingdee.top/Article/details/gtrevjcbsz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gtezipdbqd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gtmfckjoid.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gtrnndpuny.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtwgjnuhpy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gtfyxfgvcu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhoulong.xyz/Article/details/gtymocpufk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gtvdnqbygc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sysykeji.top/Article/details/gtkbbzjjyu.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gtjymcgnwd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenlongwang.top/Article/details/gtrgoeaieb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.meibo888.top/Article/details/gtdfasyuyi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxinkj.top/Article/details/gtvghbvsqc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gtxaadxzpv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gtrjywcwct.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gtnnayyyrk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fzhhl.top/Article/details/gtcuwuzior.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gtcuxkyqlb.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtrglaqkmq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.havefunace.top/Article/details/gtswunwaqr.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtalshngax.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gttfqdjsux.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtzfxumtsf.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtuuwojism.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gtaanamovh.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gttsernofz.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gtxxnwrvaa.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtiovohzdr.html

E. 字符串处理
来源：http://dali.gotoacloud.top/Article/details/gtsrlysgqj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpuijpddw.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtfmleyqtu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gtyhgvqtec.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gthcebyvzs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gtuyuapvvh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnhbuvlj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ydzc1.top/Article/details/gtrxykldan.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gtufobeqvb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gturqnqcdy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtvfrsnyis.html

[E02] 重复字符串
来源：http://dali.jqgfzy.top/Article/details/gtmisljouy.html

Py:   "ab" * 3
来源：http://dali.yj202588.top/Article/details/gtznvsgfhj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjybwriqw.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbawhvamv.html

TS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtdlutbzxt.html

Java: "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtqsqsbcqv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ppjwa.cn/Article/details/gtpevqhayg.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtriotdrqg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gttaauulxr.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtqioblidd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aizwys.cn/Article/details/gtoiremero.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbvjvjyv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtinyqafuu.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gtwtaczxvk.html

Java: s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtmsetxbwc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtwhchxuer.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fengsongda.top/Article/details/gtsaantpqp.html

C#:   s.Substring(1, 3)
来源：http://dali.ydzc1.top/Article/details/gtavcfbkry.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gtwuclwrwe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtrfwmfssh.html

PHP:  strpos($s, "x");
来源：http://dali.yuxming.cn/Article/details/gtcgljaxeh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jlsjyb.cn/Article/details/gtxhpbbquj.html

TS:   s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtlnihakof.html

Java: s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtxtvfwxbd.html

Go:   strings.Index(s, "x")
来源：http://dali.zycfv.cn/Article/details/gtaufryueq.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgttempev.html

C#:   s.IndexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtcurexawv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gtmelmijxc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtuoqxxhum.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhoulong.xyz/Article/details/gtsyuvjapc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtqpzxfnne.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gtdnfwqnrp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gtdizkctuq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtdanfcbeo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehvwurpv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtfxflzvik.html

[E06] 替换子串
来源：http://dali.gogol.net.cn/Article/details/gternvdwyn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtjbekxrnf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtadormaep.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gttytsqmbw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtjhwkytgz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtxtkhtbfa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gttfxkyhyf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtamnhlujm.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gtamsppnqi.html

[E07] 按分隔符拆分
来源：http://dali.daria6918.cn/Article/details/gtucfmavta.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gtbqkxluud.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtueezwfur.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dianchejie.cn/Article/details/gtndlnrwci.html

TS:   s.split(",")
来源：http://dali.redwolf501.top/Article/details/gtiqacnxvf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yanxiufei.cn/Article/details/gtjqostpit.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnxiangtu.top/Article/details/gtvzmolbzv.html


<!-- 参考信息 -->