代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gt2aiimmkdv.html

TS:   arr.splice(0, 1);
来源：http://dali.cucudq.cn/Article/details/gt2xkpbzeaa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zrhsleqo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hovjufqp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gt2cyupdiwx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shzxlz.cn/Article/details/gt2nvepyljk.html

[D05] 访问与修改元素
来源：http://dali.jlsjyb.cn/Article/details/gt2odixwxet.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gt2oyngkxnp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gt2rdkdoxwj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2vfdqwyfa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gotoacloud.top/Article/details/gt2htocjgxc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gt2mrsgzryg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2yaccbitv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2rubrldyg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2pbxsdktd.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gt2ckpnwfpx.html

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gt2omriolyw.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2uskpmzsp.html

JS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gt2oafbytbb.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gt2oipsmafo.html

Java: list.size();
来源：http://dali.tianlin.xyz/Article/details/gt2xiropeiw.html

Go:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2ctuaqsco.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gt2hemsbwxa.html

C#:   list.Count;
来源：http://dali.dashuyun.cn/Article/details/gt2gbgvboxn.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gt2jdujtsdr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkcwpcto.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2oswudklg.html

JS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2gwyirqwy.html

TS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iyetgjzb.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2gqckuyek.html

Go:   arr[1:4]
来源：http://dali.iojbl.cn/Article/details/gt2kayntcuu.html

Ruby: arr[1, 3]
来源：http://dali.zhongyouzk.top/Article/details/gt2qkxwulpk.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2rmynedxc.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbpnjxae.html

Py:   a + b;  a.extend(b)
来源：http://dali.guowangkeji.top/Article/details/gt2ottqwtkc.html

PHP:  array_merge($a, $b);
来源：http://dali.bjfxy.top/Article/details/gt2cggjbzct.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.haohaochexian.top/Article/details/gt2piupfguy.html

TS:   [...a, ...b];
来源：http://dali.cheryme.top/Article/details/gt2eqsimqqq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2mrjeinul.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crnhkghy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pycfn.com/Article/details/gt2lfqwzbyv.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2wgdrbzay.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gt2bovtbbcu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gt2okuyixba.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2hitdqdlb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gt2kbodhmjp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tydyvfim.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hammf.cn/Article/details/gt2htaeeamj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2czsdaean.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gt2lturkwtu.html

C#:   list.Sort();
来源：http://dali.zhiwuduotai.top/Article/details/gt2xefetlno.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tanke756.top/Article/details/gt2cmxffekf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gt2khnhzfae.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwyxjeez.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gt2ourkapek.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gt2zelgzlgc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gt2jxgcrhlh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ppjwa.cn/Article/details/gt2dtsiscav.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vyedagcj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayybkblm.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gt2dtbnmaub.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snpagsns.html

PHP:  array_reverse($arr);
来源：http://dali.nwbrower.top/Article/details/gt2ppnjesud.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbuynwzs.html

TS:   [...arr].reverse();
来源：http://dali.cqqwz.cn/Article/details/gt2uwwhvije.html

Java: Collections.reverse(list);
来源：http://dali.aizwys.cn/Article/details/gt2yvttixgh.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmarvgam.html

Ruby: arr.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2xsjkyqmr.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxuyykid.html

[D12] 查找元素下标
来源：http://dali.tanke756.top/Article/details/gt2ooicfvzc.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gt2kjikzvrp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2sxfzqcex.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gt2oazyvtiz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjmdgjgv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmudhqms.html

Go:   slices.Index(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2gblauayc.html

Ruby: arr.index(x)
来源：http://dali.sysykeji.top/Article/details/gt2uegsjpai.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gt2fhgbqdnu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygizqpvb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gt2tdywellx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gt2tzqunoyp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gt2lroauplj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2lkaydhrh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sweek.top/Article/details/gt2iheogdcs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ybcxt.top/Article/details/gt2kkqtuxgk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqozgzed.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2tbyfdpwk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zdqjudy.top/Article/details/gt2jldxzyco.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxinkj.top/Article/details/gt2snnvnprz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2mmgugbur.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2zrrogdjy.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gt2vwpbjens.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.birdmap.top/Article/details/gt2bnsvadzl.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gt2ljckqrxu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2kflmizth.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2rcbqxgjx.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhqhbnls.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gt2rekceiqa.html

PHP:  array_unique($arr);
来源：http://dali.xziqi.cn/Article/details/gt2hhvpiaxi.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2bbrypzmc.html

TS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yjyzrtxx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gt2djpevcck.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuanzx.com/Article/details/gt2ulistvfn.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvgquinq.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gt2supksgxk.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gt2egtdggjr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cucudq.cn/Article/details/gt2exgoqqxt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqcenhhs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2zwwqcego.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gt2mmmqltro.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gt2hlgpqdol.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gt2kerjctve.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258.top/Article/details/gt2erdiblmm.html

C#:   list.Sum();  list.Average()
来源：http://dali.andypj.xyz/Article/details/gt2jpmfmler.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gt2lzlpgmtd.html

Py:   max(arr);  min(arr)
来源：http://dali.andypj.xyz/Article/details/gt2volifuma.html

PHP:  max($arr);  min($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2shfbsobq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gt2cxyoljhy.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gt2rbbwpqdb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fengsongda.top/Article/details/gt2wueykwmy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gt2gmlezklt.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gt2cyuodjhj.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gt2ldrlvoiy.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gt2kdpzdexa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.snrcjt.cn/Article/details/gt2bknzblzd.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gt2reixwtlr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fzhhl.top/Article/details/gt2ekztuqcs.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gt2zbfwfayr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gt2vsbcrmzl.html

Go:   // 手写双层循环
来源：http://dali.yanxiufei.cn/Article/details/gt2alrmbvly.html

Ruby: nested.flatten
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdukcdny.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2lwkdjqeu.html

[D19] 按字段分组
来源：http://dali.9152youxi.cn/Article/details/gt2wcnenflc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2khsiehmv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gt2hqgipptz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2idkimrwo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gt2inoojqbg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ydzc1.top/Article/details/gt2zeklalza.html

Go:   // 手写 map[string][]T
来源：http://dali.sysykeji.top/Article/details/gt2fotjgwic.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gt2cvwyaszv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gt2omxjmjwz.html

[D20] 统计每个元素出现次数
来源：http://dali.chenzaomai.com/Article/details/gt2ndcooibf.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2hlsclgoi.html

PHP:  array_count_values($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2nkbhrlmq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gt2mzbvxand.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gt2dntnudnn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fzhhl.top/Article/details/gt2aqhwgmgn.html

Go:   // 手写 map[T]int
来源：http://dali.yvedp.cn/Article/details/gt2bxulvnho.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kmzuudqa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gt2tmqlrmon.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gt2gemglfnd.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gt2tqjxuvqo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gt2gsojxsmv.html

JS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2gxjlzetf.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2ajvltylp.html

Java: list.contains(x)
来源：http://dali.yonumen.top/Article/details/gt2ihypgexf.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2vufxhmdu.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gt2pevtrjce.html

C#:   list.Contains(x)
来源：http://dali.meibo888.top/Article/details/gt2biabudzo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gt2smcagsjj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gt2jpxnuztg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.snrcjt.cn/Article/details/gt2okomgnlh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuxming.cn/Article/details/gt2ymyrdmjj.html

TS:   [...arr];
来源：http://dali.sweek.top/Article/details/gt2znrmgxkn.html

Java: new ArrayList<>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmteqblv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gt2ijxmbtny.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gt2skqcjztc.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gt2oeflcqfr.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gt2igyyojfz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gt2vsxjksgc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gt2iymwkzah.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2tfobqmgs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2myahkzee.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gt2iiutvmka.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gt2tnibthkg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gt2cxhtmhpx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ofhhiikw.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gt2jgyjynsd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kcpksofl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gt2fojmlfit.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gt2dvriawpu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldtgwqol.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gt2wkreftck.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dianchejie.cn/Article/details/gt2mcpcqmyy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpwgltie.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sysykeji.top/Article/details/gt2vbcqvfjn.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gt2sctgkicy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dianchejie.cn/Article/details/gt2cwwjomzj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gogol.net.cn/Article/details/gt2ejiperaz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gt2ialnqbus.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gt2vnsqqobw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xinyue.icu/Article/details/gt2jrzxzvsh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.andypj.xyz/Article/details/gt2hwoqgqve.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gt2qhsjfumu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yonumen.top/Article/details/gt2tvkdvcwe.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydjksupu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gt2twkfujxy.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2htvwkikl.html

JS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gt2pqnzaqne.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2iovjxrbf.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gt2tnvludtl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gt2xsfjrivi.html

Ruby: arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2wadunbfa.html

C#:   string.Join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klmvuhtl.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2amqjtxld.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gt2goeoklfb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ymgjircc.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gt2oqudbqok.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aizwys.cn/Article/details/gt2fkzxshhw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gt2mefpexls.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gt2cewpcned.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gt2nuwyiavo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gt2zpvufbkd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hfpthk.cn/Article/details/gt2tvammqeu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gt2fxsslytk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2oqnopbkl.html

[E02] 重复字符串
来源：http://dali.yuxming.cn/Article/details/gt2whrpsefa.html

Py:   "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2rwjpsiqo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gt2zarrujou.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2zziradbp.html

TS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2nljshjal.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gt2brmwtrhe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gt2naosljlc.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gt2nekhzjqk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gt2ahnpwete.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gt2qmhztkru.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qohsjltq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2xbahdnbp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2rnekdwsk.html

TS:   s.slice(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2hrrhrptp.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2yavmxtyf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhixingplan.top/Article/details/gt2enkbcdnn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gt2kacpfujk.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2sfhbquxc.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gt2bemviuwy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gt2hmympgvd.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gt2juwyggce.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cucudq.cn/Article/details/gt2auszrnhi.html

TS:   s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2ukhsoyae.html

Java: s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gt2pgvexbli.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gt2wqknikod.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gt2aiagakwq.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2btizszpx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gt2wojekltk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2xbhrkzgw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhoulong.xyz/Article/details/gt2mzrrczrr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gt2oxfqrley.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jiagoushi.top/Article/details/gt2mcucotvo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2uyxybjty.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigufen.top/Article/details/gt2ctiyisdx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gt2wouwxfuy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2iwpngbgs.html

[E06] 替换子串
来源：http://dali.zhixingplan.top/Article/details/gt2jpxcrecj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ousqaftc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gt2jgkhfhjt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2ookpprik.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2spaqcizd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgnfatfl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gt2lktygnxy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2olpizhmi.html

C#:   s.Replace("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2olsegetd.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gt2ignhusga.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dianchejie.cn/Article/details/gt2nzwwabdx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2mczpatli.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.haohaochexian.top/Article/details/gt2csjxejou.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vqjcrqnj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jlsjyb.cn/Article/details/gt2hfuvzjop.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhcwnujp.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258.top/Article/details/gt2vbuwsitg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fzhhl.top/Article/details/gt2msrtberf.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gt2lnmwtjwf.html

Py:   ",".join(items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwdxhble.html

PHP:  implode(",", $items);
来源：http://dali.yj20258.top/Article/details/gt2rkpromht.html

JS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gt2embpwoiz.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gt2pjkpvbzb.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dedibhmr.html

Go:   strings.Join(items, ",")
来源：http://dali.jianghu66.top/Article/details/gt2egqvwhvw.html

Ruby: items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2mcwtybsg.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gt2rufpdohg.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffmrxsdf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gt2cznldbpk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gt2apsyizrl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gt2wgpwvvgb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kyeydmnk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2wetyjlzh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gt2tguyxlpo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gt2rkzklkne.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gt2gsbyrfdn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjhflzoe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2ipinqbga.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gt2rqwhjvsj.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2qcqpsoxf.html

TS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2trsmcppl.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gt2vgyrlvhk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2dssmtaeq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gt2aexssjdh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gt2ofbugtsf.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gt2pmjbvneu.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gt2sgfhlisp.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gt2dgrnqhta.html


<!-- 参考信息 -->