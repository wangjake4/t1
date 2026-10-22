代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2sykukkzk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gt2modyldxl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gt2uxvkuyfl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gt2huqnsnbo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2wtximtmx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2qgdhlgha.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gt2oqdgyzut.html

[D06] 数组长度
来源：http://dali.bjfxy.top/Article/details/gt2qoyvdeuh.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2sgnkyzxb.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2dizchgfo.html

JS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gt2gzhxgwyw.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifmfdfxo.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gt2fddeopin.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2vyotqgbi.html

Ruby: arr.length; arr.size
来源：http://dali.shuidangran.top/Article/details/gt2xmnptfzm.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gt2mlamntfb.html

[D07] 切片 / 取子数组
来源：http://dali.sufxvd.cn/Article/details/gt2hnqwsych.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.bjfxy.top/Article/details/gt2asijtyoc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gt2ybtotnlf.html

JS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cozoytsm.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2qlpnghzp.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2rgzylieb.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gt2fqcgqeuc.html

Ruby: arr[1, 3]
来源：http://dali.hnqzz.top/Article/details/gt2gqlmgtcf.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gt2kvvfstmo.html

[D08] 合并两个数组
来源：http://dali.sweek.top/Article/details/gt2osjkxybd.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangdashe.top/Article/details/gt2awyifjmn.html

PHP:  array_merge($a, $b);
来源：http://dali.gaohongyu789.top/Article/details/gt2sjheojpn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gt2ljtumhhx.html

TS:   [...a, ...b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2dboxtocu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gt2numhljmv.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gt2grcinusr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ivvv.top/Article/details/gt2sgisguds.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybyofbuk.html

[D09] 排序（升序）
来源：http://dali.jiagoushi.top/Article/details/gt2spnbgdnr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gt2misodjri.html

PHP:  sort($arr);
来源：http://dali.yuxming.cn/Article/details/gt2tqtgosvt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.316326.xyz/Article/details/gt2wrpadadr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gt2vhscgkfr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tanke756.top/Article/details/gt2ejcrinfl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2wkyovvtd.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhmrqmlc.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gt2yowoxqsk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gt2jikdhfxq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gt2mfpukngb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2yqcbsiwi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gt2stluokob.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gt2hqgfunlf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gt2okhsrpsa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sufxvd.cn/Article/details/gt2ngfmzehn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gt2lfrqtbhp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nwbrower.top/Article/details/gt2eniryvhr.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gt2hztqokgp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnqzz.top/Article/details/gt2ljpibtgn.html

PHP:  array_reverse($arr);
来源：http://dali.ivvv.top/Article/details/gt2ibjyczbh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xziqi.cn/Article/details/gt2lrxinmgd.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfvtgttp.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2unrpefmq.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gt2ziwjaroz.html

Ruby: arr.reverse
来源：http://dali.tanke756.top/Article/details/gt2xoajjpqa.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elalvygm.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gt2edkdeqdf.html

Py:   arr.index(x);  x in arr
来源：http://dali.nwbrower.top/Article/details/gt2jknautnd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2pqdhnwua.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gt2njqonsvl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2obeoecki.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gt2bjgazsjp.html

Go:   slices.Index(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2biceggpd.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2urcotwun.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gt2iosragxb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daria6918.cn/Article/details/gt2ahagbdea.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gt2gaeorgrd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2hjmeefte.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klzzqfxt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2uixkbzzd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gt2iksmvwfx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gt2xscmyjnu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gt2izctlbaj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2hvjrkjex.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gt2pyovysbx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gt2ylmgcmbe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2lbwjieen.html

JS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gt2bhfayvfw.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gt2fmqxlxtu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zykphafq.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gt2kpogprop.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2obldkseg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2mfzkboad.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gt2vxzjuskz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gt2bidahlsx.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2eiujshhl.html

JS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gt2kkjgjflt.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gt2atpfmzhr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gt2qxvacsbh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gt2aomcbxkh.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdlzbxbt.html

C#:   list.Distinct().ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2ckcwjpww.html

[D16] 求和与平均值
来源：http://dali.gogol.net.cn/Article/details/gt2prtzvdtm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shuidangran.top/Article/details/gt2qqgylawk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2asfnihbz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gt2izowkdsq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2vjcrvpdi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gt2ibetmvyh.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gt2dfmdqofu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gt2efrkxpxh.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgydgiua.html

[D17] 最大值与最小值
来源：http://dali.hfpthk.cn/Article/details/gt2pxokgiuw.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlembftg.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2pbhnxwgm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gt2qgebapri.html

TS:   Math.max(...arr);
来源：http://dali.fengsongda.top/Article/details/gt2zzwunnjt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gt2fcjbbcjx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2jwquwbrz.html

Ruby: arr.max;  arr.min
来源：http://dali.zhixingplan.top/Article/details/gt2cnqkhfuc.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gt2nmzbnqrh.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2jljloliw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gt2mpuwrfof.html

PHP:  array_merge(...$nested);
来源：http://dali.yangfankeji.com/Article/details/gt2ejcxgvjs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gt2qsutwlzs.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gt2pvgufqrg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2wsincuml.html

Go:   // 手写双层循环
来源：http://dali.yanxiufei.cn/Article/details/gt2dptuxcro.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gt2fcsvpatc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2tsxqfxkj.html

[D19] 按字段分组
来源：http://dali.havefunace.top/Article/details/gt2bsvspasz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pycfn.com/Article/details/gt2zcukdddf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljczomly.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gt2fuvluxjm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvwbgaks.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenlongwang.top/Article/details/gt2lxyintdw.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mtyunvca.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuetiantiany.cn/Article/details/gt2oaxdaarm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fzhhl.top/Article/details/gt2aettewyn.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gt2mweddvfh.html

Py:   Counter(arr)
来源：http://dali.sysykeji.top/Article/details/gt2mrxzmrjm.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gt2hepxipkq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gt2eroxmtso.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gt2mcjpxuiw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cdnleiting.top/Article/details/gt2wdxabnpa.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gt2njfeascg.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2dpndsrkn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gotoacloud.top/Article/details/gt2lupmspbk.html

[D21] 判断是否包含某元素
来源：http://dali.jianghu66.top/Article/details/gt2hemsupnq.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gt2uzsdruhc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guannengcc.top/Article/details/gt2djkorytx.html

JS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2mytmoipt.html

TS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2zzqklbkd.html

Java: list.contains(x)
来源：http://dali.chenlongwang.top/Article/details/gt2sjdcejay.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2mncbzbqb.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gt2gmtdvjff.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gt2dtdwivfm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenlongwang.top/Article/details/gt2egmbuywl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gt2lsnweisj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gt2xhtxlkot.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258888.top/Article/details/gt2airjfyso.html

TS:   [...arr];
来源：http://dali.sxryk.cn/Article/details/gt2cjyftdib.html

Java: new ArrayList<>(list);
来源：http://dali.yonumen.top/Article/details/gt2eegybebj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txewprhn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gt2fcdypobd.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogrpcpdw.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdjtoddx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gt2yukhhxkz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2kgvwodry.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2jgnaasze.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2lkccmkhx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gt2ejdhdbkd.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gt2octsxqyn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fzhhl.top/Article/details/gt2ptcunopu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gt2ohvovdhf.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gt2mvpwaphf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jyoumei.cn/Article/details/gt2tiwomacz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gt2lhuohmyd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2bvxmrdqo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2xszhetwj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gt2pwyktsgt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dashuyun.cn/Article/details/gt2ltzagyeu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gt2cmkgvvqj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gt2njdstpqt.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gt2oafylhyi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gt2ybnwovud.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gt2mlthyhzw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ojtlefyh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkvuwglm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2wgojovqz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zycfv.cn/Article/details/gt2msmblixp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2xgafygqc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gt2byrfgaqs.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcmfgqsa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2dbzkqxgn.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gt2dbdcxhpr.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgmmzvx.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2mvyhgbnq.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjwsnica.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gt2yuulumuy.html

Ruby: arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gt2dkmwaozl.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gt2szszrnfy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uspndkix.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gt2bvcfjwol.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2aacjbawm.html

[E01] 拼接字符串
来源：http://dali.yueranfly.top/Article/details/gt2iqnixaxv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdikpuiy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2aukqlkyx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhjcjuew.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gt2sqjmhwmz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gt2kbsompqm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gt2hehhsrqs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.svipenyu.cn/Article/details/gt2wlhxenzr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2esdwcftu.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohftieom.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gt2mzvloomt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.meibo888.top/Article/details/gt2qocauqaq.html

JS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2ihyyesqm.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2uynihzgf.html

Java: "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gt2vgmborrm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gzhubu.top/Article/details/gt2zmdomsgs.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gt2krqibdla.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjxnzgko.html

[E03] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gt2slhvpxga.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258888.top/Article/details/gt2wgcnncvc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2bdizeppm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2jcdokxoc.html

TS:   s.slice(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2vwwrxrbq.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxxmavxy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dashuyun.cn/Article/details/gt2rhqhwnnf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gt2grmttuky.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gupqksdz.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gt2nbacjipi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gt2llfzgbuk.html

PHP:  strpos($s, "x");
来源：http://dali.sxryk.cn/Article/details/gt2ggocedka.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cqqwz.cn/Article/details/gt2avwshuvu.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2mfpzkmwy.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2sbbaricu.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2eskrilmt.html

Ruby: s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gt2mgwtxddw.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2mvicmnbr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fengsongda.top/Article/details/gt2kynxwbxn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2qgfouvxv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fzhhl.top/Article/details/gt2qfwzuxjw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2kkolaupa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gt2oudjtffw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gt2miadrpmw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gt2kfotrigt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuanzx.com/Article/details/gt2hliilahy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2ygqlwrhl.html

[E06] 替换子串
来源：http://dali.snrcjt.cn/Article/details/gt2attrouyz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gt2wgdbtnnk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhengqikj.top/Article/details/gt2pljlujhj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2tbayceuf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2qhgccamw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2wdxmtmga.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2luznwzcd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2gzycgxnb.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rwcagtja.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gt2gaqcrxhj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xinyue.icu/Article/details/gt2aapskmun.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2ivukegxk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ybcxt.top/Article/details/gt2omuoztqy.html

TS:   s.split(",")
来源：http://dali.daria6918.cn/Article/details/gt2kfnnwnch.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsamtamv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2luakiupz.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gt2twvxdzkv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zdqjudy.top/Article/details/gt2iddlomxv.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gt2zyycxrkt.html

Py:   ",".join(items)
来源：http://dali.c1oappe.top/Article/details/gt2cjtspjdn.html

PHP:  implode(",", $items);
来源：http://dali.smart0.xyz/Article/details/gt2cwwkranu.html

JS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gt2jrdyzoku.html

TS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gt2zbqbkxqe.html

Java: String.join(",", items)
来源：http://dali.havefunace.top/Article/details/gt2zgbcjekn.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gt2maqnscuf.html

Ruby: items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2rgzesfeu.html

C#:   string.Join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gt2xzggdugs.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gt2yuxniopb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gt2pzgbjymo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daria6918.cn/Article/details/gt2sesgbzsl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gt2ctobgklu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gt2dhczqnod.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gt2kkuuhwjj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gt2bqswptqo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nwbrower.top/Article/details/gt2mdlixbvx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gt2ycjafgaq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cqqwz.cn/Article/details/gt2cjsewcrj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2duzbmsma.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fihfkixc.html

JS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zkucadjc.html

TS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2zgzaegyp.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2ydkjipia.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2aqfbrqxs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gt2ckrhvpst.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gt2elpfqvvk.html

[E11] 反转字符串
来源：http://dali.tian-w.cn/Article/details/gt2tqezpblw.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gt2qdoefxbd.html

PHP:  strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gt2akqlakho.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bphlxdrx.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2lufuardm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sufxvd.cn/Article/details/gt2mueylnee.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shzxlz.cn/Article/details/gt2zpsnpvnd.html

Ruby: s.reverse
来源：http://dali.hnqzz.top/Article/details/gt2mqyibtbw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gt2jaztruxh.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2fdvfnxuj.html

Py:   s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gt2skozqqei.html


<!-- 参考信息 -->