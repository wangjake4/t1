代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.meibo888.top/Article/details/gt2prgexozr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gt2whmydahl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gt2gkhyztqb.html

JS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gt2gffgalgt.html

TS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gt2ijmamkqn.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2lvqafpcb.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gt2rlngavib.html

Ruby: arr[1, 3]
来源：http://dali.hysaishi.cn/Article/details/gt2lyhvqkrl.html

C#:   list.GetRange(1, 3);
来源：http://dali.cashguo.top/Article/details/gt2hvqbsszq.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gt2vbgzbaml.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gt2cobqruqi.html

PHP:  array_merge($a, $b);
来源：http://dali.dianchejie.cn/Article/details/gt2hwqhwwsu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pycfn.com/Article/details/gt2idaqaomz.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gt2gtwxgcnq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2cqctpjmj.html

Go:   append(a, b...)
来源：http://dali.cashguo.top/Article/details/gt2fprhethq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zdqjudy.top/Article/details/gt2cunjkyam.html

C#:   a.Concat(b).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2icfooszn.html

[D09] 排序（升序）
来源：http://dali.yueranfly.top/Article/details/gt2eoiycfmh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gt2bmkfkvwb.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gt2vfuaasyo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gt2rskmewuy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2dageoxes.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.quarkkingdee.top/Article/details/gt2xjjxnnlm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2lszucsvj.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gt2mmrfvpqf.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gt2jsiwgyah.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gt2dqgcsdwv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gt2ogqzxdhr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gt2fvgufoqn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gt2vfpmnist.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gt2xqgrigdu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gzhubu.top/Article/details/gt2kbwzrwfx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.mhx1999.top/Article/details/gt2wsyeissh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sweek.top/Article/details/gt2mcepuyno.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnxiangtu.top/Article/details/gt2qdrtocjj.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gt2smlgqiav.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gt2bzsbfgby.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkkpufad.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gt2ahassjsu.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gt2kyreagsq.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gt2sqkeonju.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqlbiavy.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gt2fmhzujad.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tneopvde.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gt2clonzxwk.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxuanxn.top/Article/details/gt2wlshjjru.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2emjwqxmk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gt2bdhwfytg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ismbjeea.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gt2yigklmux.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2bgnkplbh.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gt2tlyfavfr.html

C#:   list.IndexOf(x);
来源：http://dali.yvedp.cn/Article/details/gt2xjkxjwgv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.meibo888.top/Article/details/gt2tfolmcsn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2wouoluvq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258888.top/Article/details/gt2lxhryxoi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gt2isywgdfv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2gqepefmx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2uorxsudo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangdashe.top/Article/details/gt2jqdnnkgv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj202588.top/Article/details/gt2gchoyhvd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2ptnovfvi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxinkj.top/Article/details/gt2nctmowkn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gt2pkunbcnl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.smart0.xyz/Article/details/gt2oectbzeu.html

JS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gt2yehtidpp.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gt2eueeynne.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2bccxdyjo.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gt2jenqcogf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukzkbnds.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2tmpzjagm.html

[D15] 去重
来源：http://dali.shuidangran.top/Article/details/gt2mjypousf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gt2dqjhwiof.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2mqybyoze.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dspukgyw.html

TS:   [...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gt2oqgmbaoi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gt2qturawny.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gt2hisftcbn.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gt2lsrmyusz.html

C#:   list.Distinct().ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2brohzcvx.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wupjsudg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2xlajcwzt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2xlivehxe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2bfackpza.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlxazkpe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gt2urvqfcus.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gt2sxoqnbte.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ehwqpu.com/Article/details/gt2gsradijx.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhengqikj.top/Article/details/gt2ssyoleie.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gt2kqlmuyik.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gt2uimamcju.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2haiovyzw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gt2uoqoviyz.html

TS:   Math.max(...arr);
来源：http://dali.dianchejie.cn/Article/details/gt2jqjhdowb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gt2mapefquf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cashguo.top/Article/details/gt2svezcoli.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gt2tsuusmyt.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gt2izzshypz.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gt2otzlryca.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ybcxt.top/Article/details/gt2mumdfrna.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gt2sfndpzbh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gaohongyu789.top/Article/details/gt2wotlqssu.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gt2ivhcxjwg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufkgkfoq.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gt2qieofajf.html

Ruby: nested.flatten
来源：http://dali.smart0.xyz/Article/details/gt2jpcatnil.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ivvv.top/Article/details/gt2bgxsbkbc.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2izbfnfxp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgfzy.top/Article/details/gt2lpswscia.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gt2prteyzpf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gt2akvfyzpm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gt2xwfnzbpx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvhvjvmi.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigfzy.top/Article/details/gt2lkqhjqzr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gt2nlywbsmp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gt2tdnwufxk.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gt2fgbignup.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2nlvfqfoc.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gt2zqoagpis.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gt2jzarnwwq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gt2gohfnlpe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gt2fsftoxuo.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gt2sutifnkl.html

Ruby: arr.tally
来源：http://dali.dashuyun.cn/Article/details/gt2pstmhmpa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gt2kuvpsgik.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gt2akdszgwb.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gt2qvjvkhgr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj202588.top/Article/details/gt2rdcmljwn.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gt2jbajigus.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhahschq.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2opowifkg.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2sxnpydgb.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gt2uwjaxzlr.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gt2jajauwbz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ppjwa.cn/Article/details/gt2jddunclx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2zdbmjhro.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gt2djxkexps.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2hwjppypq.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gt2pewvrdiz.html

Java: new ArrayList<>(list);
来源：http://dali.yongpay.top/Article/details/gt2qcdkdpgg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yueranfly.top/Article/details/gt2ilyvckwl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuanzx.com/Article/details/gt2jjygjxbi.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gt2pultpwfi.html

[D23] reduce 累积计算
来源：http://dali.cucudq.cn/Article/details/gt2qnfjzzom.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2beionebm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cheryme.top/Article/details/gt2sghufskq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gt2zyawlkqq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gt2vcqeeoou.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gt2ngzlnqou.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gt2rsqopxmv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gt2howpjlzy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fzhhl.top/Article/details/gt2imqfadgj.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gt2peboolpc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2chcgqswb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gt2nmepwvhz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gt2dltsfzrg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2yempjnfw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gt2pfwhfnyf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gotoacloud.top/Article/details/gt2lacbiowg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gt2ndmevkjl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gt2udtywkxg.html

[D25] Set 集合去重与交并差
来源：http://dali.pengpengdd.cyou/Article/details/gt2wsgvkahs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gt2bzjicobn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gt2hxmaozyu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gt2auabburw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gt2xskomldr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jiagoushi.top/Article/details/gt2cfvsjyap.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gt2vyysyygd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gt2ewwsgjih.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gt2diswpezf.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gt2gkdmazjm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gt2vpkwwspo.html

PHP:  implode(", ", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2fgoymkkv.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2seudiomk.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gt2ajiqfgsl.html

Java: String.join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2venjhofk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcsaioaq.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2cnrxezdc.html

C#:   string.Join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2klayhtrq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2onkhtiyx.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gt2udbdnixz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2gsthrubw.html

[E01] 拼接字符串
来源：http://dali.iojbl.cn/Article/details/gt2fpwlrkxl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gt2aqehtnji.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.iojbl.cn/Article/details/gt2wyphbudq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gt2epevlwyf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2ywswnpdi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uyqviovz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2cpfulnjh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfesbwa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqatdwwm.html

[E02] 重复字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2ywuyuzin.html

Py:   "ab" * 3
来源：http://dali.cheryme.top/Article/details/gt2ruqyqjwx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2anbtpkqh.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bodmrbbb.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gt2jnbwqilc.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gt2wbdfsmsu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2uuzmushv.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gt2jlnrytnh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzvwsexd.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdxgsgmx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnxiangtu.top/Article/details/gt2dtuqrntn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2ibkknrer.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2ztxlrqxs.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2xkrqawjr.html

Java: s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2qaffxmgy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gt2fbnhzwme.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gt2pnxscjqx.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gt2vqrpsvad.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gt2xcpbnhxz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gt2dmkihhpt.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gt2fyyxeojf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guowangkeji.top/Article/details/gt2ocvmykvu.html

TS:   s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2pxmgftjo.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcofgaxp.html

Go:   strings.Index(s, "x")
来源：http://dali.mhx1999.top/Article/details/gt2ohfleigy.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2esurtjvp.html

C#:   s.IndexOf("x")
来源：http://dali.yvedp.cn/Article/details/gt2yqhdchld.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ivvv.top/Article/details/gt2tkwmofer.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2trifsdqa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhongyouzk.top/Article/details/gt2aukgbeiy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2kmafsrkg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hammf.cn/Article/details/gt2rqkvkfav.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2zoefzyeu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdlssfay.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2awtyunyd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2bvrvoknx.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gt2dppxsbde.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gt2wbqbgcvo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2syhccxbl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2ojixynyt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2ykyknrjo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gztbvnrn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gt2lyiruqqp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2wgrahqbg.html

C#:   s.Replace("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2xybeduce.html

[E07] 按分隔符拆分
来源：http://dali.jiagoushi.top/Article/details/gt2pfexpbzr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tanke756.top/Article/details/gt2kagcafzw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvsdixif.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.smart0.xyz/Article/details/gt2jrrcauke.html

TS:   s.split(",")
来源：http://dali.9152youxi.cn/Article/details/gt2xsixacxu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gt2tslbbtxg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wibrmsyb.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gt2yiwdhgud.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxinkj.top/Article/details/gt2nzdeubah.html

[E08] 数组按分隔符合并
来源：http://dali.gogol.net.cn/Article/details/gt2pdoruzhd.html

Py:   ",".join(items)
来源：http://dali.yuanzhike.top/Article/details/gt2gnfkbtfv.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gt2ypfypych.html

JS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2vrtbduzh.html

TS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gt2hlmexonw.html

Java: String.join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gt2huklmcsv.html

Go:   strings.Join(items, ",")
来源：http://dali.0kj1m.cn/Article/details/gt2ucsqfxeo.html

Ruby: items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubwinqxb.html

C#:   string.Join(",", items)
来源：http://dali.c1oappe.top/Article/details/gt2swrqfjac.html

[E09] 去除所有空白字符
来源：http://dali.vqdsnc.cn/Article/details/gt2ohnsainy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pycfn.com/Article/details/gt2cnufpwee.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gt2kghinapg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gt2rxleuaaa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gt2zkakuhww.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gt2mguwtknr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cheryme.top/Article/details/gt2wkwwqnzy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hysaishi.cn/Article/details/gt2jkbejzrd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2fargtubf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gt2opzwuzdy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2zongiptc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gt2vwswqrad.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gjsjqsph.html

TS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2pakayahj.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2bksqaumc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ubwglhoe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ueapgdho.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gt2splnhfrt.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gt2icqixjbb.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdfvnerl.html

PHP:  strrev($s);
来源：http://dali.yonumen.top/Article/details/gt2nprssmul.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2dihhuoar.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2bwgpubuw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ivvv.top/Article/details/gt2ijbwhlgq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gt2rdvvoaty.html

Ruby: s.reverse
来源：http://dali.havefunace.top/Article/details/gt2uduvefsf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzeqyjkf.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gt2ctgksuds.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2flcqstdn.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gt2dsciyynx.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2jlzoxbwe.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gt2fvgnnzrs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pengpengdd.cyou/Article/details/gt2oakvufrl.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gt2fbutnhzg.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gt2ibqijsvw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.316326.xyz/Article/details/gt2hvrhixkq.html

[E13] 逐字符遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmvuzzov.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gt2fhroawzo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mouecdfg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2jfmrydzs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2umwjaigf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2plziywti.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gt2myqxnfft.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gt2vcvagskl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2rqbrqabj.html


<!-- 参考信息 -->