代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gt2ahlfiozy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gt2onlsnmwy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vilwiosq.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gt2rpyvaovc.html

Py:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gt2ozttbchw.html

PHP:  count($arr);
来源：http://dali.xziqi.cn/Article/details/gt2sthnmyod.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gt2splllcke.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gt2gjdaczas.html

Java: list.size();
来源：http://dali.feifeiyinyue.top/Article/details/gt2wezoxywh.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2famttbbj.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gt2rbpzlbcp.html

C#:   list.Count;
来源：http://dali.vqdsnc.cn/Article/details/gt2ucsnbsxf.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gt2avkohkxz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigufen.top/Article/details/gt2enftxrav.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nwbrower.top/Article/details/gt2tdyckzcj.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2jjkupxgi.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gt2binneprc.html

Java: list.subList(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gt2omhucrqw.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gt2rdfxykxk.html

Ruby: arr[1, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2syqvrxfp.html

C#:   list.GetRange(1, 3);
来源：http://dali.ybcxt.top/Article/details/gt2ycpcfift.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gt2ypznswvf.html

Py:   a + b;  a.extend(b)
来源：http://dali.tianlin.xyz/Article/details/gt2kkdiubqr.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gt2kcvkhrxf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gt2muuvvmxu.html

TS:   [...a, ...b];
来源：http://dali.haohaochexian.top/Article/details/gt2picjpemv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gt2byetrpwg.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gt2iarxsmyf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxinkj.top/Article/details/gt2webmjmwx.html

C#:   a.Concat(b).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2jhszaqsy.html

[D09] 排序（升序）
来源：http://dali.feifeiyinyue.top/Article/details/gt2dqyohako.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gt2qdgvcovy.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2afgtgdlv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258.top/Article/details/gt2xivgmaew.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gt2fndcgbqb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhixingplan.top/Article/details/gt2arqdjxbg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2olioddjx.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gt2idlvimdm.html

C#:   list.Sort();
来源：http://dali.xuetiantiany.cn/Article/details/gt2axzxzolq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gt2ufgygpgv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sxryk.cn/Article/details/gt2ryzukmeg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfmchlvj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gt2zfxyoslu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gt2coyudnqa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gt2bqbicqfp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.birdmap.top/Article/details/gt2cmnwarzv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gt2yisivcqb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gt2wqmweuuh.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gt2wlqqxdkg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxuanxn.top/Article/details/gt2oafuywzd.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2wgbuhhyg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gzhubu.top/Article/details/gt2yyuceywc.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gt2catxfscx.html

Java: Collections.reverse(list);
来源：http://dali.jqgfzy.top/Article/details/gt2betxenny.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gt2vwqoizlo.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnehsukv.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gt2cjyxtjvz.html

[D12] 查找元素下标
来源：http://dali.xuetiantiany.cn/Article/details/gt2sksrzlbs.html

Py:   arr.index(x);  x in arr
来源：http://dali.yongpay.top/Article/details/gt2htfdwwbp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gt2bfnxpquf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2kyuusfeb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gt2kzislznh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gt2mejrycqu.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tddtcxum.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2illodhct.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gt2oiqtuihp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gt2fndpmdzk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gt2pjkdusmp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2zdmcuscb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2diuiswmm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nsblokad.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2xlbvbwyb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhoulong.xyz/Article/details/gt2yelhftdm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.mhx1999.top/Article/details/gt2wsvbonxf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2hakroeqd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gt2lwkhdxae.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigufen.top/Article/details/gt2pmcdpfwi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gt2nolaqmiz.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gt2wxqxalrz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gt2vaiylfwr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rngcqalk.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gt2bnjzkquv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2bwtziwsw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2uzqrvehg.html

[D15] 去重
来源：http://dali.gotoacloud.top/Article/details/gt2aqtxzrpc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gt2ngidnnov.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2pnaqmlwz.html

JS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gt2otkiakbx.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fzjzipsy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gt2rfitqszb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.birdmap.top/Article/details/gt2jhenjpis.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gt2izmbvcim.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gt2xweenhok.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gt2viqcbdlm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2nwbgvtgw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2biirtyze.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2hxvqzryt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2hxfzugsp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj202588.top/Article/details/gt2atjawlgl.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdepaxvo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.birdmap.top/Article/details/gt2oclnfrzl.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gt2rajwaljs.html

[D17] 最大值与最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnclnint.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2sqincyhf.html

PHP:  max($arr);  min($arr);
来源：http://dali.cheryme.top/Article/details/gt2wohukmll.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cucudq.cn/Article/details/gt2qhybrjrb.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gt2loaxrnhq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gt2zdacuemm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sysykeji.top/Article/details/gt2vouqorgu.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gt2zxasvpwa.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gt2laemumra.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gt2peggzxkq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gt2xlsqooek.html

PHP:  array_merge(...$nested);
来源：http://dali.chenlongwang.top/Article/details/gt2mnxvzhpc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.quarkkingdee.top/Article/details/gt2yjntzgui.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gt2ehpihrpk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gt2qesurvqh.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gt2akznltcs.html

Ruby: nested.flatten
来源：http://dali.yj20258.top/Article/details/gt2cjgqxfyu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gt2asvobolx.html

[D19] 按字段分组
来源：http://dali.dashuyun.cn/Article/details/gt2vkhkydyp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gt2eprlhsqn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gt2vqgagybq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnxiangtu.top/Article/details/gt2rbxpoiob.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gt2esmasajg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tianlin.xyz/Article/details/gt2tnuizaws.html

Go:   // 手写 map[string][]T
来源：http://dali.yvedp.cn/Article/details/gt2nuwdvyxh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gt2cxdgdccx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gt2lmkkjyhu.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gt2rblydubs.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gt2rcjlnjfx.html

PHP:  array_count_values($arr);
来源：http://dali.bjfxy.top/Article/details/gt2pdppkhfj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gt2zzovogpm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gt2csuaccxs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gt2jvfynrwi.html

Go:   // 手写 map[T]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbgzvfke.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gt2kvuilejt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gotoacloud.top/Article/details/gt2bzvhhivn.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gt2wrkexkla.html

Py:   x in arr
来源：http://dali.zdqjudy.top/Article/details/gt2elqzlyrq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gt2srhhcahj.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2dxskwkqv.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2iujstotc.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2airsnied.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2kpdiquvk.html

Ruby: arr.include?(x)
来源：http://dali.yongpay.top/Article/details/gt2mgfqswvk.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gt2kyzilbiv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cheryme.top/Article/details/gt2luyqvhuh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxpdsbk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gt2urelhhdg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2uoqscvty.html

TS:   [...arr];
来源：http://dali.sweek.top/Article/details/gt2rlanbmxk.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gt2uulyqctg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gt2ebagkdsb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gt2rgmwsvna.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gt2sylbvauh.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gt2tenedkkp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxklpcdq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2hswbuuyy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gt2ryqoaegu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2hcbnkdbl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gt2mqqqyuwv.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2llbjeayx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gt2xezlyybv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gt2vkzjvjdi.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gt2zitzctxs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gt2aahmndmc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gt2zwhrghxf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258.top/Article/details/gt2kgndbhqe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2aqergmti.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gt2ltdpueqn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gt2dgdwqwgd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2rdmcfgev.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fengsongda.top/Article/details/gt2rjysawgv.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gt2uhsuseot.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gt2maxrhyww.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gt2qnqvdpcd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gt2kssoskgm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjezpxtb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gt2auawdvbc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gt2yycyacwg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gt2gdasoscc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gt2eaxapnpu.html

[D26] 数组转字符串
来源：http://dali.pycfn.com/Article/details/gt2bffkjnly.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2yqtixbju.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ntwgwcti.html

JS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2hainaujp.html

TS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfmvhoab.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubopxshm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenlongwang.top/Article/details/gt2lrcltywo.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2mnbjpstm.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2vutnnfhw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2wrkfbsuq.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gt2kfbnpycs.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ttvatzwz.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2zpoabiig.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tianlin.xyz/Article/details/gt2zddjvxtx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdvxzmyo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2ycuftzzc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gt2ngeuopck.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gt2ygndsjoa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.birdmap.top/Article/details/gt2vxhppxzm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigufen.top/Article/details/gt2veksjxgj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2mzflmfrv.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gt2rfjzpomw.html

Py:   "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gt2irobgmci.html

PHP:  str_repeat("ab", 3);
来源：http://dali.andypj.xyz/Article/details/gt2pmebiinw.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gt2qcwwyqxu.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2ysgkxrvk.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmjxrovj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gt2zumwvnzf.html

Ruby: "ab" * 3
来源：http://dali.ivvv.top/Article/details/gt2rjpgccbz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yanxiufei.cn/Article/details/gt2izpmiath.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmnzqspi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cqqwz.cn/Article/details/gt2kqyncovz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2zywcnmbn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2ewqojapq.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbgspxnq.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2triufueg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gt2rsuiojgp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ppjwa.cn/Article/details/gt2tjygjqjg.html

C#:   s.Substring(1, 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2thhfddmi.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gt2rajbmtrk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2hyakdwid.html

PHP:  strpos($s, "x");
来源：http://dali.daria6918.cn/Article/details/gt2lsomlidn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dpmbpzwq.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jtyfdfmg.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mizgvxst.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gt2dfiuuqlv.html

Ruby: s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gt2ljacyxoa.html

C#:   s.IndexOf("x")
来源：http://dali.xziqi.cn/Article/details/gt2zqyrxzxa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gt2iyubbmth.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2xqdvfsdi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqxxccpn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gt2jqfmxfnn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2mnhqejzx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2mycjwrip.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sxryk.cn/Article/details/gt2cspuauqn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guowangkeji.top/Article/details/gt2mczyiyvv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yueranfly.top/Article/details/gt2paeqckah.html

[E06] 替换子串
来源：http://dali.xinyue.icu/Article/details/gt2zjhqyetb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2ormeaomz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gt2yxroyfzq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2fppiaket.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwisgqrx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2veqhyvmu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gt2iilpsfhj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2yenzfqdo.html

C#:   s.Replace("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hymefnzz.html

[E07] 按分隔符拆分
来源：http://dali.hfpthk.cn/Article/details/gt2vtxkqfxx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gt2dxuxgmch.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfylbcpr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gt2tkpggbpy.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gt2dmalnekj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gt2zfxxyxrp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenzaomai.com/Article/details/gt2nuhuzanl.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gt2bxqdimsk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenlongwang.top/Article/details/gt2djqtwosv.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gt2ldhgdsxq.html

Py:   ",".join(items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jewqvvtn.html

PHP:  implode(",", $items);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uyjpsjzb.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkwljadq.html

TS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2yytvmlxy.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gt2hfkachgm.html

Go:   strings.Join(items, ",")
来源：http://dali.tian-w.cn/Article/details/gt2tzwpsktm.html

Ruby: items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odwoogwm.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gt2ytduannx.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gt2ednzdunm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.svipenyu.cn/Article/details/gt2uxnpnlys.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2phxopfeg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gt2npexpwvf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2xgeiuqna.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gt2ragjevyw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.snrcjt.cn/Article/details/gt2haedetgp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nwbrower.top/Article/details/gt2pzebawoj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehieynns.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangshuangyany.cn/Article/details/gt2roozbnkw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2ocoamlgl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gt2hthqkddy.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cscwyzvd.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkdehgxi.html

Java: String.format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gt2bdegtfyn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2bnmhwdui.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2lslxtguw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gt2aurnmyfb.html

[E11] 反转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2rbxvihrt.html

Py:   s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gt2pvcjyftw.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2ebtcifog.html

JS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2qiddqdct.html

TS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uumagfvx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2ioavfmdo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gt2reluiijv.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2ypvwyxun.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gt2yvxvpdut.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gt2vopzkpyq.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehkjqduk.html

PHP:  substr_count($s, "a");
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmygnqmh.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gt2ejdldcnq.html

TS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gt2odzipimd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhoulong.xyz/Article/details/gt2rbizvebp.html


<!-- 参考信息 -->