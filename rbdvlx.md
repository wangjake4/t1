代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gt2atzyysmp.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gt2yahtnsad.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sysykeji.top/Article/details/gt2octgclsg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gt2twviujph.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ybcxt.top/Article/details/gt2wflqjcpw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gt2ugukxktj.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gt2tnpgxfgl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gt2bleqcmjr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gt2tmddzglo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2rhsjqghp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gt2udhrnadx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gt2krhucjds.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgkiujnn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gt2xsdojomq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2seumajkl.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gt2saaitvyi.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2bpgwcwnj.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2atdtqaex.html

JS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gt2aqyicmdf.html

TS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gt2qjnnciui.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gt2hokrygok.html

Go:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gt2fdabldos.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2pmgejnkt.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gt2urpgsrip.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258.top/Article/details/gt2vopeudjm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gt2enjxmcdn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tanke756.top/Article/details/gt2vpuolpcu.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2ceqxbktp.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2epmbgsbe.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2bpeixalh.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gt2agwxlcmq.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gt2bratcgjc.html

C#:   list.GetRange(1, 3);
来源：http://dali.shuidangran.top/Article/details/gt2vylqrflc.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkztywvd.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258888.top/Article/details/gt2ztsuypyz.html

PHP:  array_merge($a, $b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azbjthen.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjhvxnmn.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gt2mnbpjili.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gt2qqjldcju.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gt2lefgildg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pycfn.com/Article/details/gt2ywerauqk.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2zkbjovtx.html

[D09] 排序（升序）
来源：http://dali.yj202588.top/Article/details/gt2shihzrpi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gt2ypnuiqgj.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gt2hckbivga.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dianchejie.cn/Article/details/gt2agotvgqx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gt2tcmqyqvm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ppjwa.cn/Article/details/gt2vqxxauhj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2okulzpap.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gt2ifsghoqj.html

C#:   list.Sort();
来源：http://dali.kuanghao11.cn/Article/details/gt2aselcecq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuanzx.com/Article/details/gt2elfhspwh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ppjwa.cn/Article/details/gt2mmiovwry.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gt2jsufcxsx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gt2ubwmsuhk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gt2tqjtigds.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ivvv.top/Article/details/gt2tmxabgvr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gt2pkuluyto.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gt2lcjqtrad.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.smart0.xyz/Article/details/gt2mnibzvxl.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gt2avoqtdhd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnqzz.top/Article/details/gt2gjeadbji.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2bcswpkzh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gt2nokspals.html

TS:   [...arr].reverse();
来源：http://dali.fengsongda.top/Article/details/gt2eeqwjdgi.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gt2ienxvdgl.html

Go:   slices.Reverse(arr)
来源：http://dali.yongpay.top/Article/details/gt2hzshdqal.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gt2bcdbtldv.html

C#:   list.Reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gt2pnoeieac.html

[D12] 查找元素下标
来源：http://dali.yvedp.cn/Article/details/gt2qggnzhnd.html

Py:   arr.index(x);  x in arr
来源：http://dali.tanke756.top/Article/details/gt2syvovzif.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2oieztdyt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gt2gukyuouo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttcqheba.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gt2qjvvayat.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2ictglywl.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gt2ztfnnauy.html

C#:   list.IndexOf(x);
来源：http://dali.cucudq.cn/Article/details/gt2deyevnjl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gt2dsazgbnq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2ljdyrqqu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gt2tiaijzxc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2qsgkjych.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gt2iywyjhir.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cheryme.top/Article/details/gt2izncsanl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cdnleiting.top/Article/details/gt2xwxtmsvb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jyoumei.cn/Article/details/gt2fqcpsyyk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2sguxrsrl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cucudq.cn/Article/details/gt2kfitesfr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gt2dyjxylkg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ygfnhcul.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gt2huwyxkin.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gt2cdajwzjo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2pwnscqlg.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gt2amylzjee.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2dkmgwpfk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2jvyzoaqt.html

[D15] 去重
来源：http://dali.quarkkingdee.top/Article/details/gt2msvajfas.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gt2zvylqdgo.html

PHP:  array_unique($arr);
来源：http://dali.guannengcc.top/Article/details/gt2gmeiglgi.html

JS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2kbseypkf.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gt2kxfndowr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gt2qwepfixx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgiuopuf.html

Ruby: arr.uniq
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvitebbm.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gt2otyvreue.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gt2bvyfugdj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daxiang520.top/Article/details/gt2ywulvfia.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2ofqrnfwz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2ixwawuza.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gt2mblouorb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gt2zjyphsiw.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gt2hzowuqjc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shuidangran.top/Article/details/gt2gteedemq.html

C#:   list.Sum();  list.Average()
来源：http://dali.pycfn.com/Article/details/gt2fxqskele.html

[D17] 最大值与最小值
来源：http://dali.gzhubu.top/Article/details/gt2gbqedaru.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2udtxpotf.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gt2rniwtxfc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gt2syvzoxtg.html

TS:   Math.max(...arr);
来源：http://dali.nwbrower.top/Article/details/gt2eozrhlrd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gt2enlhocun.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gt2rfilvwhc.html

Ruby: arr.max;  arr.min
来源：http://dali.dashuyun.cn/Article/details/gt2ssqfkpoe.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gt2zabaddrd.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2buevtbtt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gt2fuazirfh.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzhduhgu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gt2btmqvyzn.html

TS:   nested.flat();
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrirshyl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gt2vcvbpudy.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gt2pegjmpjy.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gt2ntpviclq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ivvv.top/Article/details/gt2wimnykry.html

[D19] 按字段分组
来源：http://dali.aizwys.cn/Article/details/gt2cczudbbg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnqzz.top/Article/details/gt2fcerryrx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yonumen.top/Article/details/gt2lehmpixg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.bjfxy.top/Article/details/gt2froswxqz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2oitkxcfl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtnxynxc.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gt2fmkemmna.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgufenzy.top/Article/details/gt2awwcskrj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gt2dksfnycb.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gt2ohqxvsgh.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2omkbkiuy.html

PHP:  array_count_values($arr);
来源：http://dali.cashguo.top/Article/details/gt2jxnayprn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gt2jvzgxtxm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gt2xcjwtvgv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gt2mpxnxmqt.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gt2gljktqxp.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gt2buyntmmf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuanzhike.top/Article/details/gt2jwjvxcnb.html

[D21] 判断是否包含某元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnrycmdd.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gt2weskkiwk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gt2edtdsltb.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gt2cbhpuare.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2osieulow.html

Java: list.contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2kmdllgfm.html

Go:   slices.Contains(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2ahfjjoyc.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2srbqwowp.html

C#:   list.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gt2uovyzrhh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gt2eftslyxn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2zyjwcdxx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jianghu66.top/Article/details/gt2piryjilf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcfplrna.html

TS:   [...arr];
来源：http://dali.nanxuanxn.top/Article/details/gt2oeozgrhw.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2vklbizsk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnqzz.top/Article/details/gt2fydduoxy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gt2rlzzwcxi.html

C#:   new List<int>(list);
来源：http://dali.dianchejie.cn/Article/details/gt2ghobzhsk.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gt2qhqrcauf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tlqvryce.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2jqhfgrem.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2gdkxpkvr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gt2hcqytndj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.mhx1999.top/Article/details/gt2hmkypnfs.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gt2ndyyilhr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gt2xhhifffa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yangfankeji.com/Article/details/gt2hatketze.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gt2vqpfeinx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gt2mlmnbppb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aizwys.cn/Article/details/gt2rxadadzp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2cspgnyeg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2byuvvwbv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2izuikwyp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.birdmap.top/Article/details/gt2osbmldiv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ceouhlsy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldgthokq.html

[D25] Set 集合去重与交并差
来源：http://dali.xylfe.cn/Article/details/gt2klbdsrlz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gt2nrzxxvfo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gt2ndbmmoli.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gt2afkzvizr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigfzy.top/Article/details/gt2xtsbpeuz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gt2vaeoazcz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yanxiufei.cn/Article/details/gt2tvzzffbs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gt2ygahhgki.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gt2qhzcagfm.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2gvrnvqck.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2laondfrc.html

PHP:  implode(", ", $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2bqiozetj.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gt2amaenieg.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gt2cfftqkwc.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gt2tcsmrghy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gt2ynawdvig.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gt2njzevhzo.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2bbiykchb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2vlrkjbza.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gt2bhhhtarv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2bwwtkitd.html

[E01] 拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gt2myclqdhu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gt2yzufetwm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhengqikj.top/Article/details/gt2wushfksh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gt2flpgmcvr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2uxsyyjsk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gt2dlibfifh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnnvwzkp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbuodsvj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubbkpjfs.html

[E02] 重复字符串
来源：http://dali.tanke756.top/Article/details/gt2uceuualm.html

Py:   "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gt2iebtnmhh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gt2llieezzv.html

JS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gt2jnfozamo.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gt2dhnpzjzc.html

Java: "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gt2aeeudnoc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnjjutmw.html

Ruby: "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2labmbdmf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkqadsik.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2srvjgeli.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gt2occzocjh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2jsoviaki.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2nguaccbm.html

TS:   s.slice(1, 4)
来源：http://dali.xziqi.cn/Article/details/gt2ghgorkcu.html

Java: s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gt2bvyadwcj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuanzhike.top/Article/details/gt2fykchcqe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gt2sebuvkss.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gt2dbvbeaol.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdgewgvo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.c1oappe.top/Article/details/gt2sefjekec.html

PHP:  strpos($s, "x");
来源：http://dali.haohaochexian.top/Article/details/gt2vrftztgz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gt2oxphoakr.html

TS:   s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2pjgyrmpr.html

Java: s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gt2lzmtrisv.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gt2ltyrqksm.html

Ruby: s.index("x")
来源：http://dali.bjfxy.top/Article/details/gt2llretolc.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2bseykuiv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2zuccrtyr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gt2tbxmundz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gt2hawbisvf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojydjwah.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gt2emlmiqfu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gt2gafbcgbv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gt2qluqsfux.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gt2iwkjoycq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2uliqutvo.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gt2iwhtxtui.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gt2dqatitcm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlrvxysc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2qoudtaow.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2vhpiosrk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2lwsoqsql.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gt2clqgdgjj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2koeepsan.html

C#:   s.Replace("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2bnvxlhyj.html

[E07] 按分隔符拆分
来源：http://dali.hfpthk.cn/Article/details/gt2uczyzgps.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuanzx.com/Article/details/gt2pilplmtl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2hwwmggsa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gt2lbambhgs.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gt2hopwtyyi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxhbfzgm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2djqhrvks.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gt2rjswmzwx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gt2uuncfpgz.html

[E08] 数组按分隔符合并
来源：http://dali.dashuyun.cn/Article/details/gt2zbdszkqf.html

Py:   ",".join(items)
来源：http://dali.meibo888.top/Article/details/gt2apdozfwx.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gt2jyxvrcul.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gt2erxhgxnw.html

TS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gt2zljrlikz.html

Java: String.join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lilqjyxy.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gt2bkjvzeop.html

Ruby: items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gt2doerncmm.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gt2eevhchuf.html

[E09] 去除所有空白字符
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jgonppuu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aibaodan.cn/Article/details/gt2yoftbvrb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2xfovgvpb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2llhtpqig.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gt2hhrtxyxz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gt2moixgmje.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gt2ltffemnv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.iojbl.cn/Article/details/gt2pzhjzuby.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tanke756.top/Article/details/gt2dnganqmr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenjidiqi.icu/Article/details/gt2rwlgatrw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2ttaabbaa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxuanxn.top/Article/details/gt2flzrpbsi.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gt2ncvfqejs.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2qcrryhpu.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gt2gvxodlrz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2ikamywks.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlyogehf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pycfn.com/Article/details/gt2unysmkms.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2tzgfprcg.html

Py:   s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gt2atzhvzwd.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2abzbrfan.html


<!-- 参考信息 -->