代发 wailian999

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aibaodan.cn/Article/details/gtjrbwtqln.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.316326.xyz/Article/details/gtcfoiofgz.html

[D05] 访问与修改元素
来源：http://dali.cqqwz.cn/Article/details/gtowugkbnf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtlwoywvyp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtrxruddfi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtirqtuvdp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gttwvqqrfk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gtjefhqjol.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gttilrlior.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gteeiuujsu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtojiyipqg.html

[D06] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtmtfpfxpx.html

Py:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtpmbqjnmi.html

PHP:  count($arr);
来源：http://dali.ydzc1.top/Article/details/gtiygzbvss.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtaqlhrqkv.html

TS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaufuztp.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtlciolgpy.html

Go:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtfaykyhwb.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgufosnz.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gtmeuohndw.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gtrkxlmmsw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.c1oappe.top/Article/details/gtbwubndtt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgvfuhim.html

JS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtndczxilx.html

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtevrrlkcu.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtwqojgtna.html

Go:   arr[1:4]
来源：http://dali.fengsongda.top/Article/details/gtlkaucuym.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtuujjkfpi.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gthepovwiq.html

[D08] 合并两个数组
来源：http://dali.sufxvd.cn/Article/details/gtyxzibuzu.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gtdpvgphwo.html

PHP:  array_merge($a, $b);
来源：http://dali.yanxiufei.cn/Article/details/gtwqsxtlep.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jlsjyb.cn/Article/details/gttdzacvyc.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gtxxnttgri.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yangfankeji.com/Article/details/gtypmhvvfs.html

Go:   append(a, b...)
来源：http://dali.redwolf501.top/Article/details/gtlxadsgpq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gtvghmjnch.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtvmaqpvcf.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gtsyobqknk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtftowstjt.html

PHP:  sort($arr);
来源：http://dali.yongpay.top/Article/details/gtzaqygunc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xylfe.cn/Article/details/gtvqwctlft.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guannengcc.top/Article/details/gtcgkggnxr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shzxlz.cn/Article/details/gtgibzchgs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gthlinshnx.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtiotyrqhw.html

C#:   list.Sort();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuldfgxf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfszexzp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pycfn.com/Article/details/gtxykytyeq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtvmpojgjz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtlzarlhdn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtklyvlgly.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gtmjgzmllv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.feifeiyinyue.top/Article/details/gthojicnyi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gtdooacxos.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gtufnseoma.html

[D11] 反转数组
来源：http://dali.hongshengwenyu.top/Article/details/gtirvspcbq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.kuanghao11.cn/Article/details/gtiydoiqzi.html

PHP:  array_reverse($arr);
来源：http://dali.hywenlv.cn/Article/details/gtpkkznhar.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.iojbl.cn/Article/details/gtfjugpiku.html

TS:   [...arr].reverse();
来源：http://dali.yuxming.cn/Article/details/gtdhqcjwqh.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gtghkcromr.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gtrqvdwwvy.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gtkgilprdm.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gtfhlwfrfz.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gttscqmwzt.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gtqhjywhwl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gtoaxehgfi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtxkfjyyfp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtyrmvctrx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.c1oappe.top/Article/details/gtobfskogi.html

Go:   slices.Index(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtqfxwpdmc.html

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gtqhvftsli.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gtipzhywtx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gtakecelyx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gtyijvymgn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gtwtevvpww.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtoqnirrlv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtmerlwdxx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gtelsjbvcg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gtqbjbdvbl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtxsywdirg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sxryk.cn/Article/details/gtllsymvbb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gtfdflehab.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gtgybybwap.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.smart0.xyz/Article/details/gtzjbrstwd.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gtwbpzrhvd.html

TS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtwytmcfvo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gtnwtjxcza.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtyabfdsio.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdchwpwtt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtbgkxnnxg.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gtynfxrhve.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gtyaahyedz.html

PHP:  array_unique($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtipmxkvxb.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gthectlxwv.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtgzhjwwhr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gttpbbzjht.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tanke756.top/Article/details/gtirpeoasa.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gtlrmyazcb.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gtbaqpuukb.html

[D16] 求和与平均值
来源：http://dali.hfpthk.cn/Article/details/gtuiqyranv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtbpdbieum.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xylfe.cn/Article/details/gtzdwqxsbw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtciiaksnp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gterywpycz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gtmynujfwr.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtertqdopw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gtvmowemas.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gtcknzzgrt.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gtesxfujzd.html

Py:   max(arr);  min(arr)
来源：http://dali.andypj.xyz/Article/details/gtwjyhgdpu.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gtzxyuueso.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.9152youxi.cn/Article/details/gtpwiardwu.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gtvmyftfdo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtokrlycot.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gtphozqgfk.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gtmrpanykk.html

C#:   list.Max();  list.Min()
来源：http://dali.aizwys.cn/Article/details/gtrrqyihod.html

[D18] 扁平化嵌套数组
来源：http://dali.pycfn.com/Article/details/gtqaqlmpzc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cdnleiting.top/Article/details/gtwkhmtfdq.html

PHP:  array_merge(...$nested);
来源：http://dali.cashguo.top/Article/details/gtzrdsufpi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gtpsogzsvr.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gtrsrrpmse.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gtngponmdi.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gtttyfhifj.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gtxmiorgte.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gtvmstwytl.html

[D19] 按字段分组
来源：http://dali.aizwys.cn/Article/details/gtywezqjaz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gtaypuizaa.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtienbaefa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovrlgqkv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gtopidcpqm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gtixjwgtai.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gtqxhfmwuu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenjidiqi.icu/Article/details/gtswynoheo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gtuazjwrae.html

[D20] 统计每个元素出现次数
来源：http://dali.haohaochexian.top/Article/details/gtjnmrsdfo.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gtrtqgkkpg.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gtjbdhnmyl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gtuvyffwyp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gturosgtha.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gtmpwpehvm.html

Go:   // 手写 map[T]int
来源：http://dali.cucudq.cn/Article/details/gtzjfdqnaa.html

Ruby: arr.tally
来源：http://dali.haohaochexian.top/Article/details/gtzkcjxiyj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gtfpivluxd.html

[D21] 判断是否包含某元素
来源：http://dali.shangyingyoupin.top/Article/details/gtodpscgzz.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyayivsa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.kuanghao11.cn/Article/details/gttwjdjoiu.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtbdegzpnk.html

TS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtpzpxazgp.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gtanwuhqmq.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtiplmzejr.html

Ruby: arr.include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gtqznoekbp.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gtjjhsffyy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shangyingyoupin.top/Article/details/gtqnuteadb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gtmgjqtfem.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gtmuwcscgi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtgduaymxl.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gtxngxbpnh.html

Java: new ArrayList<>(list);
来源：http://dali.nwbrower.top/Article/details/gtvtyvlzss.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuxming.cn/Article/details/gtimjqrgvn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gtzuiorrts.html

C#:   new List<int>(list);
来源：http://dali.xuanzx.com/Article/details/gtyihlppna.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkmdtvpe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtkbaiybqw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shuidangran.top/Article/details/gtdzwddcwk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxutawhl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtnorpbcvp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gtaevltjln.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gtgpsqbtvs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gtpdnefjvp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gtnqqaxtjd.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gtiysxosxg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gtqgzknmuf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gtoonsxrmb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gtbflgwmmp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.316326.xyz/Article/details/gtszgjvvgp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhkexmmz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuxming.cn/Article/details/gtwxiotdwh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gtkriezkfw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gtxfdcirjz.html

[D25] Set 集合去重与交并差
来源：http://dali.xinyue.icu/Article/details/gtsxghrrgp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gtetidndkx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fengsongda.top/Article/details/gtyofyhclp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnxiangtu.top/Article/details/gtxbewtcdm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gtjxptncfq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gtwnnktprm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jyoumei.cn/Article/details/gtdfnqraxt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gtwlszcyeh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.smart0.xyz/Article/details/gtkyumoxkl.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gtexjeyngm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtdrzrhuze.html

PHP:  implode(", ", $arr);
来源：http://dali.gotoacloud.top/Article/details/gtaiukuheg.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gthoixfroh.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gthpjrtupi.html

Java: String.join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gtkxrgrwsi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtbslqiner.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqfdbpjn.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtahqgcklh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtevjxgkev.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gtwfkzahst.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtttofwxnh.html

[E01] 拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtaiqcarya.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhoulong.xyz/Article/details/gtmvbkshbt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtamvbybgj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtcdiyaisy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtlvspwdtx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sweek.top/Article/details/gtbkqndqkj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.316326.xyz/Article/details/gtpnohbctj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxecvrxkr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtivymxuka.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gtoiotobhx.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gteyckgdkh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gtkrfrpnrt.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtypzxbuok.html

TS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtpiztfrok.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtysavvous.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nwbrower.top/Article/details/gtnfovhhnx.html

Ruby: "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gtrlkonpoy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.kuanghao11.cn/Article/details/gtmmfxkgar.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gtsrgehtpq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gtzrpcstfb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gthpbfrcfp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtbrkptehu.html

TS:   s.slice(1, 4)
来源：http://dali.sweek.top/Article/details/gtttkjuotl.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfrruygi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtfciyxyiu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.smart0.xyz/Article/details/gtriszeixu.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gtrbcfttxq.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gtqoeyvvhm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gtthcmvdov.html

PHP:  strpos($s, "x");
来源：http://dali.9152youxi.cn/Article/details/gtrclddzjb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jlsjyb.cn/Article/details/gtnxgdodun.html

TS:   s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtvycmdobh.html

Java: s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtpqtqaomy.html

Go:   strings.Index(s, "x")
来源：http://dali.yueranfly.top/Article/details/gtgtwccxcy.html

Ruby: s.index("x")
来源：http://dali.birdmap.top/Article/details/gtyxtwfgig.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpmewyom.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigfzy.top/Article/details/gtejdiqqps.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gtwcuknjqw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtimimvenk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gtdnjabvcy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gteftnwqej.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gttpnfbzmj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenlongwang.top/Article/details/gtmqgpsowy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gtzbilqoan.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gttenfqgwu.html

[E06] 替换子串
来源：http://dali.ybcxt.top/Article/details/gtsoghwxzf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtcmfhjlyi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gtffrpajqy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtknzogggf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmocaxmse.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtgihakfyz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyvksywq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.birdmap.top/Article/details/gtcjmqlsac.html

C#:   s.Replace("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyavmmin.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gtjgcafoqt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sxryk.cn/Article/details/gtgkqcpbvr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gtocvaiadn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gtmpdvxnlq.html

TS:   s.split(",")
来源：http://dali.vqdsnc.cn/Article/details/gtrxllviyf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gtwwkkxhyl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sweek.top/Article/details/gtexjampyk.html

Ruby: s.split(",");  s.split
来源：http://dali.chenzaomai.com/Article/details/gtuzxjpdad.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gaohongyu789.top/Article/details/gtsfcliomo.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gtxfbxooaq.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gtvjsfntab.html

PHP:  implode(",", $items);
来源：http://dali.tianlin.xyz/Article/details/gtrtvajavz.html

JS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gtgryoqqtg.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtqyrprnrs.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtonyptpyy.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucyukiqk.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtsnftvolx.html

C#:   string.Join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtoijqpepf.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gtlckflqor.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gtfknwpibx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtikdjdbzu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtphzzmoss.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtakoafybe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtxuwmunnf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hongshengwenyu.top/Article/details/gtjscdevvv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ydzc1.top/Article/details/gtnndmmakw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyftkurj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.meibo888.top/Article/details/gtpuauufvr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tanke756.top/Article/details/gtmczbnkyf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xylfe.cn/Article/details/gtujrbjzsa.html

JS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtqawthhjs.html

TS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtesufdzhc.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtzcurbfsr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtblvxzjab.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtctgscjhp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gtcgrgtgjx.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gtjyyqmoag.html

Py:   s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtaovtzcpc.html

PHP:  strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtzcjxzoho.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gttkamyrxz.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gttvngrvss.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gtbxypmjir.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gttntrdiwa.html


<!-- 参考信息 -->