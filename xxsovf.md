代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2segvyxdc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2xinufgfk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2efvltogs.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2drxsfqgo.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2nmqqshqd.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2boovemey.html

JS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efpsncnl.html

TS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gt2rfcysuff.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gt2zpkuvfnb.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2oxmahysw.html

Ruby: arr.length; arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wznrzoxj.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gt2ibbiqrao.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gt2yknnmroc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ydzc1.top/Article/details/gt2cxiayizm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2tfuuecim.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2jhpjstiu.html

TS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gt2wshgjtks.html

Java: list.subList(1, 4);
来源：http://dali.hnqzz.top/Article/details/gt2hidxyklo.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gt2ngqibkxo.html

Ruby: arr[1, 3]
来源：http://dali.nanxuanxn.top/Article/details/gt2bbhvbneo.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gt2lpznudmi.html

[D08] 合并两个数组
来源：http://dali.cashguo.top/Article/details/gt2mcwlmtiu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gt2wriemxbt.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gt2npqklkyc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shuidangran.top/Article/details/gt2xyhvjaaq.html

TS:   [...a, ...b];
来源：http://dali.iojbl.cn/Article/details/gt2gmcvyvms.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pycfn.com/Article/details/gt2qeeigyqc.html

Go:   append(a, b...)
来源：http://dali.smart0.xyz/Article/details/gt2tpukibrx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gogol.net.cn/Article/details/gt2uauyxddb.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2lslhvaof.html

[D09] 排序（升序）
来源：http://dali.daxiang520.top/Article/details/gt2djstvvej.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gt2qwylevth.html

PHP:  sort($arr);
来源：http://dali.xinyue.icu/Article/details/gt2mmdgktdh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.svipenyu.cn/Article/details/gt2yinxnxvc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gt2qomuirog.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqbeudem.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gt2iwqlkjud.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2ucvixgty.html

C#:   list.Sort();
来源：http://dali.wangdashe.top/Article/details/gt2vggoduay.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxuanxn.top/Article/details/gt2dojcwztg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigufen.top/Article/details/gt2xhuhozwd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gt2fszanpmx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gt2xgqosixi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gt2ycvvbtpn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gt2lqwwqoxs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gt2svijqhic.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gt2nsowtzis.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmpremqw.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gt2dkkwybsg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gt2ucouldqg.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258888.top/Article/details/gt2qjnrtypt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gt2wbxahkkm.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2pjklgkne.html

Java: Collections.reverse(list);
来源：http://dali.nwbrower.top/Article/details/gt2akesdkfg.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2ydqxdcla.html

Ruby: arr.reverse
来源：http://dali.daria6918.cn/Article/details/gt2xhdhvtrh.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gt2fnnonmvh.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gt2snupjkis.html

Py:   arr.index(x);  x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gt2iiyxciho.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2trbrpaib.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gt2mghwvhgl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2biweogzc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuanzhike.top/Article/details/gt2ydkzzlnt.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywppvgmq.html

Ruby: arr.index(x)
来源：http://dali.sxryk.cn/Article/details/gt2mlujcwec.html

C#:   list.IndexOf(x);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hrdmywbq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gt2wdqtirta.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2wawyiuqh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sujtnoxr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgauddrb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gt2xxdlzkmi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gt2hoswukqd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gt2wzktwbog.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2acfenlbp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2oohminag.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gt2qttyqqty.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gt2zrbmpixz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2bwgvvhet.html

JS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2wyyslpab.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2zlgwwoxv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2sjhnqbmq.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gt2gmqtzqwi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2auttqkgu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2ngxgcfve.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gt2jruihibh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gt2pydfbrkn.html

PHP:  array_unique($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2deizjrqe.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2amxmndrb.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gt2kgcdqinx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gt2nvsadocw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gt2ttyjifbu.html

Ruby: arr.uniq
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohnxnisg.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2csyqcbmb.html

[D16] 求和与平均值
来源：http://dali.ehwqpu.com/Article/details/gt2oyxnaamf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2jguxfxav.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2gqwdqgox.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tldtqoad.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2svpkdnpc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.birdmap.top/Article/details/gt2uecnulgq.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gt2vzlztnnu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gt2tayjtmlm.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gt2biarfwjb.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gt2mbhggqwn.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gt2tirrqpnf.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2sijxpbwt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hysaishi.cn/Article/details/gt2tmkwqoeg.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gt2velgwurm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gt2oyegstni.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2mmpxprei.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gt2jkfweswo.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vscxhwfm.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gt2vsvisvvm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gt2wpvinozk.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gt2mxoltils.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gt2pbejsegq.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnenesen.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2wvxhltzh.html

Go:   // 手写双层循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjidxjyq.html

Ruby: nested.flatten
来源：http://dali.mhx1999.top/Article/details/gt2dmucxjni.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gt2dpzxcqwx.html

[D19] 按字段分组
来源：http://dali.haohaochexian.top/Article/details/gt2hgijwbbz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gt2zfxkalqg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gt2wfryehyd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gt2eusjcbjn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pycfn.com/Article/details/gt2tcpfnuos.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnqzz.top/Article/details/gt2tjochozp.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gt2kixzagyr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gt2oeijltlf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2yyizguvd.html

[D20] 统计每个元素出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gt2gitwbzlk.html

Py:   Counter(arr)
来源：http://dali.bjfxy.top/Article/details/gt2yoofczzd.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vertusbe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gt2prheldlz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gt2vbrrfmtp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gt2sleorunc.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gt2fvssetlh.html

Ruby: arr.tally
来源：http://dali.haohaochexian.top/Article/details/gt2phefnqid.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhengqikj.top/Article/details/gt2ofpqilih.html

[D21] 判断是否包含某元素
来源：http://dali.jlsjyb.cn/Article/details/gt2bpqexvys.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qkguqycj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnqzz.top/Article/details/gt2shxaevxg.html

JS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2fejbbbuj.html

TS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gt2ciskcbwl.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2qbocfbgy.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2clmvabqu.html

Ruby: arr.include?(x)
来源：http://dali.yvedp.cn/Article/details/gt2wuccfvle.html

C#:   list.Contains(x)
来源：http://dali.yongpay.top/Article/details/gt2ccewiaro.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gt2cgdmlsac.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yongpay.top/Article/details/gt2vfmcczrk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gt2eymsoztz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yongpay.top/Article/details/gt2leycdqic.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gt2rztstsne.html

Java: new ArrayList<>(list);
来源：http://dali.sufxvd.cn/Article/details/gt2diciniqx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxinkj.top/Article/details/gt2cbzwimay.html

Ruby: arr.dup;  arr.clone
来源：http://dali.haohaochexian.top/Article/details/gt2cdjwplgv.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gt2pfkpgqmu.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gt2ttdrqlhv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gt2gmrskxhr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2elcqqcio.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gt2sdhrhwbs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2uqixpeha.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gt2zthqskvy.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gt2hgxuhlvu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trkogsud.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gt2bajnkrzd.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqqrkttd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhntimym.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gt2rohyhzpo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjqalxym.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2mymklmgq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.9152youxi.cn/Article/details/gt2pjjlixim.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cogtyoay.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2xaozhqpx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gt2ihywyogg.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gt2kmavtxam.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gt2uotwsuwl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gzhubu.top/Article/details/gt2jjvqdlmw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvxvzzle.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gt2wvhcwwob.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qqkzhyao.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jianghu66.top/Article/details/gt2taytadmk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2gjsiudyd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aibaodan.cn/Article/details/gt2cjsobtzz.html

[D26] 数组转字符串
来源：http://dali.shuidangran.top/Article/details/gt2prciyhxm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gt2kfgddibp.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gt2wwrbfvku.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2oukevswp.html

TS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2owapsqjt.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2wzstctcw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.havefunace.top/Article/details/gt2jakgwuru.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2jgkhlbxv.html

C#:   string.Join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gt2jsmrekbv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2duhohpch.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgezhthj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmppovlg.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2qfcxojhv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gt2cttusyoq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dianchejie.cn/Article/details/gt2ziflgyra.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2phofxdhq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gt2iwqfcefp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gt2ffizbokk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2clppchju.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigufen.top/Article/details/gt2zoggswnn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2okikqeio.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2uqfpipru.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gt2vdaarqad.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2iveavfuv.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svyyfpjv.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gt2hzhtycpu.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdfvczre.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fengsongda.top/Article/details/gt2usvaujzy.html

Ruby: "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gt2wnrmjoak.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gt2bnzwujss.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gt2uwqrnalm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymnetrwc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2cwejeiaf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajgvyijq.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2vtmcinpw.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2kmznzixc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shuidangran.top/Article/details/gt2pbyijbyy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqfjlxwo.html

C#:   s.Substring(1, 3)
来源：http://dali.hywenlv.cn/Article/details/gt2gxhlvqst.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gt2texxhiyo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcfskanq.html

PHP:  strpos($s, "x");
来源：http://dali.0kj1m.cn/Article/details/gt2xfplxtmq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.smart0.xyz/Article/details/gt2urnktitf.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gt2bbfbetdu.html

Java: s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gt2yzykyhmv.html

Go:   strings.Index(s, "x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzckikjy.html

Ruby: s.index("x")
来源：http://dali.fengsongda.top/Article/details/gt2fqjnzebg.html

C#:   s.IndexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gt2vgvdxehm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nwbrower.top/Article/details/gt2fbhhrfcv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2myunolwd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gt2gxqqnwrx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2ekobfywm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gt2yzivmswk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eiktydpt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cdnleiting.top/Article/details/gt2wbfxggqq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2spwgvpso.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2gpppprbq.html

[E06] 替换子串
来源：http://dali.hysaishi.cn/Article/details/gt2bsvtxwac.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gt2dmxmwbvr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xinyue.icu/Article/details/gt2plnmvzxr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hskufnmm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2vbwbngxd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2uyiwujed.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gt2dvnwovbq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwrdipsw.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2kewppdqf.html

[E07] 按分隔符拆分
来源：http://dali.guowangkeji.top/Article/details/gt2edwuefos.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hywenlv.cn/Article/details/gt2xjhiiqol.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2utkyruxr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tian-w.cn/Article/details/gt2ogubltep.html

TS:   s.split(",")
来源：http://dali.wangdashe.top/Article/details/gt2cugcxtzl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yanxiufei.cn/Article/details/gt2tfxogzpd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pukcbxkp.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gt2mgydpwjb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tanke756.top/Article/details/gt2lhpsxmlg.html

[E08] 数组按分隔符合并
来源：http://dali.sysykeji.top/Article/details/gt2hgjxdfil.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gt2bvrgxvaf.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gt2snrrhagz.html

JS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2djuaaddj.html

TS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2hlrgwbpl.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gt2usnohmll.html

Go:   strings.Join(items, ",")
来源：http://dali.yueranfly.top/Article/details/gt2kkxlottr.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2zcccfzyo.html

C#:   string.Join(",", items)
来源：http://dali.pycfn.com/Article/details/gt2yemorbhw.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gt2nimfgcwa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gt2jvbljpms.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2gfexiifi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gt2wslnnwjp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gt2rjrlngvu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gt2wedwqyil.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gt2rqpgcbto.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuxming.cn/Article/details/gt2ydtakaik.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aizwys.cn/Article/details/gt2fusfveae.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gt2soqzvzng.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2ulblemzp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gt2aybfpgzd.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qinpbqsy.html

TS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2vshubkxf.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwimpxtk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gt2wzaffjhy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2xljhiwjs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plkflqau.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gt2bhpoomjb.html

Py:   s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gt2hqncwcwl.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gt2rwqkxqdk.html

JS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipjfaneo.html

TS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2nnwoqipb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gt2htmztpxp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fzhhl.top/Article/details/gt2swbjnfun.html

Ruby: s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2gnplsych.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gt2zwacofbp.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gt2rbtzhsch.html

Py:   s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2znhqrzqv.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gt2dabtfygj.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2qlggchub.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2irgqmnjh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gt2vmrnfwst.html


<!-- 参考信息 -->