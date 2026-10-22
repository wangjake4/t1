代发 wailian999

Py:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2nfiuzozh.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2lkwuqxbb.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gt2nutrnlaa.html

TS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gt2cykmdlxy.html

Java: list.size();
来源：http://dali.tian-w.cn/Article/details/gt2owuzvyzk.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qlzxqlzr.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2penzcbtf.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gt2yawyxmss.html

[D07] 切片 / 取子数组
来源：http://dali.shuidangran.top/Article/details/gt2epaqbkvg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gt2wpijovqt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2uesmakor.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gt2bajmdemg.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2notsedni.html

Java: list.subList(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2zulbptxa.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gt2mmxmctem.html

Ruby: arr[1, 3]
来源：http://dali.birdmap.top/Article/details/gt2bwkutnrd.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2nidlowfk.html

[D08] 合并两个数组
来源：http://dali.hysaishi.cn/Article/details/gt2qmcrnubz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2dlpegfwb.html

PHP:  array_merge($a, $b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnrvdfto.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qpcurirp.html

TS:   [...a, ...b];
来源：http://dali.yangfankeji.com/Article/details/gt2uohhgppq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2caxivbso.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gt2kbqkrefp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gt2styitpoi.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gt2rktfixcg.html

[D09] 排序（升序）
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmegzamy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2alekhwsx.html

PHP:  sort($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2zxhtpash.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.316326.xyz/Article/details/gt2vjlwjvld.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gt2crnvawva.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.smart0.xyz/Article/details/gt2glomqrln.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gt2qjzlwlfl.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gt2ddmpugiz.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gt2jswiismk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gt2weryodsu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gt2hiqcfqvh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gt2oslnzbfe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gt2vxkfytcz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gt2yntxzsxz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gt2jwkrexjp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shuidangran.top/Article/details/gt2xfqkgucw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuanzx.com/Article/details/gt2ghysirbi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ydzc1.top/Article/details/gt2vhlflvqr.html

[D11] 反转数组
来源：http://dali.aizwys.cn/Article/details/gt2zcsmynfo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gzhubu.top/Article/details/gt2haigoxsi.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gt2wnwehkkp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.iojbl.cn/Article/details/gt2roppujif.html

TS:   [...arr].reverse();
来源：http://dali.shuidangran.top/Article/details/gt2arieqbsd.html

Java: Collections.reverse(list);
来源：http://dali.jinqigufen.top/Article/details/gt2vkvntthg.html

Go:   slices.Reverse(arr)
来源：http://dali.tanke756.top/Article/details/gt2xypavweb.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gt2rxthznoh.html

C#:   list.Reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxxrmosg.html

[D12] 查找元素下标
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxjwxukr.html

Py:   arr.index(x);  x in arr
来源：http://dali.hfpthk.cn/Article/details/gt2eukabbsk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gt2ahhfbjyq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gt2sujbpljd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2mxvcqmcc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gt2khlanvaz.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2orrivezf.html

Ruby: arr.index(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2axtmawjz.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gt2fvlpfqca.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtkhsrod.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.redwolf501.top/Article/details/gt2fguolbma.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gt2iutaaqan.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gt2msmdinft.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2ttczzclm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daxiang520.top/Article/details/gt2hvxraeid.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gt2lmkvqrau.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenzaomai.com/Article/details/gt2udrcttnf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2aiwsxyyb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gt2pxmilhjf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gt2vdibonai.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.iojbl.cn/Article/details/gt2wyyszvnv.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gt2xoyfknol.html

TS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gt2wtzzwkgv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gt2owveoaun.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gt2wevahxlp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tanke756.top/Article/details/gt2ixqxblbq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atapqmjk.html

[D15] 去重
来源：http://dali.tian-w.cn/Article/details/gt2xalffpme.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2tzrhfuyo.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2apuzqkmd.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gt2cdyoywng.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2favwckqo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gt2oeakmbua.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gt2lyprkhaf.html

Ruby: arr.uniq
来源：http://dali.jinqigfzy.top/Article/details/gt2ggyphghn.html

C#:   list.Distinct().ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2mxskexxr.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gt2dvnqhmar.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2hdasfpxs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2mofnshqz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbpnfeaj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gt2eydxnstl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.smart0.xyz/Article/details/gt2xdeopryv.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gt2orsvxvnc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2wwkishfk.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gt2tuxgfrdn.html

[D17] 最大值与最小值
来源：http://dali.ivvv.top/Article/details/gt2qrwshzsi.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxwgjfbl.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gt2aqikdiih.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gt2tromfhxn.html

TS:   Math.max(...arr);
来源：http://dali.sysykeji.top/Article/details/gt2uhtmdyds.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aizwys.cn/Article/details/gt2tsinnvfr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2hqbwxzli.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2binxwiil.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gt2nhaiimgv.html

[D18] 扁平化嵌套数组
来源：http://dali.xuanzx.com/Article/details/gt2opjopnsz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daria6918.cn/Article/details/gt2molsqdyb.html

PHP:  array_merge(...$nested);
来源：http://dali.jlsjyb.cn/Article/details/gt2gokvhqha.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gt2zzsxpizt.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibiprskk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xziqi.cn/Article/details/gt2gojyofpv.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gt2zhujmdtd.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gt2dufbkane.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2cyxdarfl.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gt2hvjbdnau.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xinyue.icu/Article/details/gt2jsjjtvsx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gt2rrasrmer.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gt2jlrzizqz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gt2lsfgsdjq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.meibo888.top/Article/details/gt2whxplmkc.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gt2wqgfilcp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yvedp.cn/Article/details/gt2cojpygpo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gt2bwensgkh.html

[D20] 统计每个元素出现次数
来源：http://dali.svipenyu.cn/Article/details/gt2paastzll.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2kyqnleon.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gt2qyywewbz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gt2azfhiadn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gt2uhqkmamk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yueranfly.top/Article/details/gt2eejgtxbg.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gt2pagkeqza.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhfygnaq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gt2kttxioar.html

[D21] 判断是否包含某元素
来源：http://dali.guowangkeji.top/Article/details/gt2jacxkjqe.html

Py:   x in arr
来源：http://dali.nanxinkj.top/Article/details/gt2dfqwnauq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tanke756.top/Article/details/gt2zzrcogxq.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2zqyehmiz.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2vkgjbkgh.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2brrclpjf.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2yfymrjle.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2oogflssd.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gt2vxfxryaf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.quarkkingdee.top/Article/details/gt2shjheybb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cykygtgh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnqzz.top/Article/details/gt2qigtvgsn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gt2hzmxmmfq.html

TS:   [...arr];
来源：http://dali.ivvv.top/Article/details/gt2uxqandpv.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2sfgwitfb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gt2hkvcqxay.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gt2lzvaqccj.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gt2ebgsjodc.html

[D23] reduce 累积计算
来源：http://dali.pycfn.com/Article/details/gt2bwsurwth.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gt2pxcqflcf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2kaonuoeo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2vuctjwqu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2rmbufgzc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jyoumei.cn/Article/details/gt2pbsxdwkm.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gt2uzigcrbt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gt2mgjfhlwh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gt2zqpumpsr.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gt2zakcvido.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2doeemcsz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2swcgsyin.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gt2prexuqku.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2prjdewcj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nwbrower.top/Article/details/gt2lewfwjhq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gt2ccowljng.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gt2aapytert.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gt2elvbxzlo.html

[D25] Set 集合去重与交并差
来源：http://dali.pengpengdd.cyou/Article/details/gt2znotoptm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gt2nezrayvv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gt2plzhuiaa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijrpgrdd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gt2iidogkya.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gt2kyzazymg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zycfv.cn/Article/details/gt2xkysxudt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuanzx.com/Article/details/gt2vhuavdgi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yongpay.top/Article/details/gt2ysbqpacv.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gt2vuhqucci.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shuidangran.top/Article/details/gt2krjrzcma.html

PHP:  implode(", ", $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2mjeahggb.html

JS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2rznwpytd.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2nxhosppy.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcmqrkch.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvcxukim.html

Ruby: arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gt2wquwbfug.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gt2rejkomih.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2zipndsdl.html

E. 字符串处理
来源：http://dali.c1oappe.top/Article/details/gt2szjnteeh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2okuyspnc.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2vjxgmtup.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ppjwa.cn/Article/details/gt2ujhukbnk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdemezd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gt2gjofoelg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2khlliogw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gt2nkxqufvq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.bjfxy.top/Article/details/gt2zwmzzhkq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gt2kpkkdozd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2kazqltnq.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gt2deltvebn.html

Py:   "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gt2tvbasdpc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yvedp.cn/Article/details/gt2cgpwaxvv.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2cklakwio.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2sbgszyxx.html

Java: "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2sxscvepn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gt2vwzigzdh.html

Ruby: "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gt2extwafag.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elwyypta.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gt2znqcbtws.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.c1oappe.top/Article/details/gt2zreghqxi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2kdlmoegs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2ktpxszko.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2ptjazqyw.html

Java: s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2quhtytam.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gt2ypycurbj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gogol.net.cn/Article/details/gt2mhbjjwrw.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2sabilaxt.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gt2imppncry.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzsfiqjo.html

PHP:  strpos($s, "x");
来源：http://dali.daxiang520.top/Article/details/gt2vhbgqnon.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fzhhl.top/Article/details/gt2vpsidcby.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2etmpexcu.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gt2gzjbdqrx.html

Go:   strings.Index(s, "x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2obemvyhb.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gt2ycvfwycb.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2bjkkcils.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gt2irdletrp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gt2entoyacj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.meibo888.top/Article/details/gt2eaojdmpf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tapuhvbr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gt2atrkmbbp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gt2azblhlyu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xziqi.cn/Article/details/gt2mritnpiy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfpogxou.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vyhkobvl.html

[E06] 替换子串
来源：http://dali.andypj.xyz/Article/details/gt2biktouek.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gt2yxszgfih.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gt2lwmoptok.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2usilmytj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2aujvybfw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2cnecqubf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gt2fztsnrjn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2rxzvzqgr.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2yataxkfo.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gt2ipummbho.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hfpthk.cn/Article/details/gt2gptgczbq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2jhtcjlyz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gt2oodmnxko.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gt2loamntjj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gt2zzocmzny.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.mhx1999.top/Article/details/gt2myfnechr.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dlzjgmen.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gt2jzbtsste.html

[E08] 数组按分隔符合并
来源：http://dali.xuanzx.com/Article/details/gt2xdxhxbau.html

Py:   ",".join(items)
来源：http://dali.yj20258.top/Article/details/gt2qfngtegx.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gt2fbjsunlh.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoufhao.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2qnzioldo.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gt2wsbdapwn.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxxrwjlp.html

Ruby: items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2xnxfmnoo.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gt2dypxmdmy.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gt2sstmxqhu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjiagdid.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fzhhl.top/Article/details/gt2ccdipjxt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2oqtbksco.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gt2sqzhopqm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gt2eyzdjsms.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ybcxt.top/Article/details/gt2xluvtykr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ydzc1.top/Article/details/gt2ohytwkgl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gt2adxxfiry.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gt2xwjnvwyr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2exjnfkch.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgufenzy.top/Article/details/gt2zzlruwkp.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2azymxkkr.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2akefktnp.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2iszdnzby.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2hkqvrvkc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2wcssktkp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlrdkdjg.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gt2hphefhjw.html

Py:   s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gt2qtzgzhqe.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gt2hhphmjuk.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2xpzmzthx.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2mzrwolhn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gt2kstsbhoh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gt2jjxwunbn.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gt2jwhhycgo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gt2kutwtsbo.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2dcwanqqp.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gt2jbajjssn.html

PHP:  substr_count($s, "a");
来源：http://dali.jlsjyb.cn/Article/details/gt2kdxyeiez.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gt2atmzpssc.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gt2vlqmdugh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jlsjyb.cn/Article/details/gt2obaoemmo.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gt2dlksocos.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfiqfxrt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gt2nrpwpzau.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gt2fmvombtk.html


<!-- 参考信息 -->