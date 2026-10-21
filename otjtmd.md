代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtcmjtaplr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtmvsuekbl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtddromayf.html

[D06] 数组长度
来源：http://dali.hnqzz.top/Article/details/gtajuwqcht.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtamygmtdw.html

PHP:  count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtegytyqbi.html

JS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtvswlntnm.html

TS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtlhlbcrne.html

Java: list.size();
来源：http://dali.sufxvd.cn/Article/details/gtismvitbe.html

Go:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtbzsjoleq.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gttpkmwowq.html

C#:   list.Count;
来源：http://dali.haohaochexian.top/Article/details/gtvtorfiov.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gtcakuqecn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.smart0.xyz/Article/details/gtujmuudqc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gttheexzhk.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtpmpekpmg.html

TS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtwhhtleim.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtbevwqrhe.html

Go:   arr[1:4]
来源：http://dali.zdqjudy.top/Article/details/gtqwgerllc.html

Ruby: arr[1, 3]
来源：http://dali.redwolf501.top/Article/details/gtfftgqagg.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtbvbjzrmy.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gtqbycvzqu.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gtvyrvvxld.html

PHP:  array_merge($a, $b);
来源：http://dali.zhengqikj.top/Article/details/gtoyyrvbfo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgfzy.top/Article/details/gtwjutapkj.html

TS:   [...a, ...b];
来源：http://dali.chenzaomai.com/Article/details/gtgrzacbqk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shzxlz.cn/Article/details/gtbaspzjzl.html

Go:   append(a, b...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffalnnad.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gtllhtpvpr.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtbypsjiie.html

[D09] 排序（升序）
来源：http://dali.daxiang520.top/Article/details/gtaggikjsn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtdjlbmtxd.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtutgqjwfr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ppjwa.cn/Article/details/gtznqnjgve.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jlsjyb.cn/Article/details/gtuluywgmc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.meibo888.top/Article/details/gtvwijanms.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtrdynchsk.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gtmqdwsova.html

C#:   list.Sort();
来源：http://dali.feifeiyinyue.top/Article/details/gtjtcgaqve.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgchwypo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dianchejie.cn/Article/details/gtmmixehkl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtierdlctb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtyfggslou.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtzgnwzcje.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gtujqwyzqa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gtibjexnfl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daxiang520.top/Article/details/gtohejypvh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gthumnwvnk.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gtphmngdky.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixhshrkh.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gtjplpuwao.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gtqtpnlyiv.html

TS:   [...arr].reverse();
来源：http://dali.hnxiangtu.top/Article/details/gttskvowbv.html

Java: Collections.reverse(list);
来源：http://dali.fzhhl.top/Article/details/gtzzqmbprs.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigufen.top/Article/details/gtcwsbushb.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gtubzgjvgi.html

C#:   list.Reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gtaloeivdd.html

[D12] 查找元素下标
来源：http://dali.vqdsnc.cn/Article/details/gtxbfnkunr.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gtwuutitsi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tianlin.xyz/Article/details/gttbxrcpmr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gteamgtuex.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtscyfcorg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gtcxtsniyw.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gtnlfifbvp.html

Ruby: arr.index(x)
来源：http://dali.wangdashe.top/Article/details/gtyssybpbs.html

C#:   list.IndexOf(x);
来源：http://dali.yanxiufei.cn/Article/details/gtikvrurdi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gtducqjdoi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtygunbmos.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtunawunra.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtkoqjtzce.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtzdhvikbf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gtkuxiyyjh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gtdagtoesc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnxiangtu.top/Article/details/gtzucepyyo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gtjflkgtqy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gtsrenykiz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtddlfsrjo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtrgesuoqe.html

JS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtdnoxdhxr.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtrnbmkcuu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtpiyzrncb.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtppbcnelu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtakquhwrs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gtokjdvqvs.html

[D15] 去重
来源：http://dali.ehwqpu.com/Article/details/gtxvfogxdq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtfxbzkwru.html

PHP:  array_unique($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtxuusjffg.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtaoitywjo.html

TS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtmlndzowk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gtrrloildh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gtwrhimhgf.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gtsdhzqglf.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtfvslweme.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gtrazvjbsz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.andypj.xyz/Article/details/gtogqirlou.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gthurzcsyw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtqesbghhz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtgvoghwpc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtfilhgwgx.html

Go:   // 手写循环累加
来源：http://dali.yj20258888.top/Article/details/gtqtzpkuzx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtoqptwjjp.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gtjlgqoljf.html

[D17] 最大值与最小值
来源：http://dali.xuanzx.com/Article/details/gttwstfrqg.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gtttnkpcyc.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtljkrchnu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtknmbyqrr.html

TS:   Math.max(...arr);
来源：http://dali.cashguo.top/Article/details/gtxglzwmuc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nwbrower.top/Article/details/gttcvgxhdx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gtjohqwxxg.html

Ruby: arr.max;  arr.min
来源：http://dali.yuanzhike.top/Article/details/gtjbbykwsz.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigfzy.top/Article/details/gtftwxcdoy.html

[D18] 扁平化嵌套数组
来源：http://dali.cucudq.cn/Article/details/gtnglwpgxs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gtdrgduopl.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gtnmemdxsi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gtilzosonc.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gtbhgppaeb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gtguzocuao.html

Go:   // 手写双层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gthsjeiglx.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gtbwrgmcgx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gtksgjujll.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlbagtyl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gtpenlalrm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gtdefgsntp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sxryk.cn/Article/details/gtxhhnqxer.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gtqdhbxmrj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gtkwmarrho.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gtfppizrki.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtizjmiqlx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gtyubrpocs.html

[D20] 统计每个元素出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtdzcgeufc.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gtbdkgrtyf.html

PHP:  array_count_values($arr);
来源：http://dali.aibaodan.cn/Article/details/gtrumasnmc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtvndrudzo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gtvtlzbsiu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.9152youxi.cn/Article/details/gtnlrnzsyg.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gteqkhshti.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyomoiou.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sufxvd.cn/Article/details/gtktcqtobv.html

[D21] 判断是否包含某元素
来源：http://dali.yanxiufei.cn/Article/details/gtbuzkrhux.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtfqqhzywd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtjzhigppr.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtfatrlkck.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtqtlcmptc.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gtargewcox.html

Go:   slices.Contains(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtnfkuoohr.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtufyqaqav.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtgavgquad.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gtkostclwr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gtjubqnnmc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuanzhike.top/Article/details/gtfdembgaw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbkysxzk.html

TS:   [...arr];
来源：http://dali.tianlin.xyz/Article/details/gtaqqbfvwj.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gtusvpclcu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jianghu66.top/Article/details/gtrbfhdtnb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gtueztrcwl.html

C#:   new List<int>(list);
来源：http://dali.jianghu66.top/Article/details/gtrnlaaneq.html

[D23] reduce 累积计算
来源：http://dali.yanxiufei.cn/Article/details/gtzfikrsoe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtggdfmabr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtqytaxfbm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtfteifzqz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtvlzcbpwp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gotoacloud.top/Article/details/gtosvcteae.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gttoffqwub.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhixingplan.top/Article/details/gtzhatcjrk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.0kj1m.cn/Article/details/gtihzpuecp.html

[D24] 字典 / Map 基本操作
来源：http://dali.xziqi.cn/Article/details/gtwffcscbg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gtdwcscrpr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigufen.top/Article/details/gtybqraxqx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gtnurxsojd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtbjwybkot.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gtnzpsxrsc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.9152youxi.cn/Article/details/gtixyysuju.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtjcvgednq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gtmhwfxkrm.html

[D25] Set 集合去重与交并差
来源：http://dali.hfpthk.cn/Article/details/gtlulzudey.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxinkj.top/Article/details/gtnxnbcvrw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gtohhmqtwi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tian-w.cn/Article/details/gtykoosrie.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fzhhl.top/Article/details/gtinxpieej.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ehwqpu.com/Article/details/gtonjwqgar.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ppjwa.cn/Article/details/gtbvhxvgzq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.svipenyu.cn/Article/details/gtrnyltemc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xylfe.cn/Article/details/gtnrsdlngi.html

[D26] 数组转字符串
来源：http://dali.hnqzz.top/Article/details/gttdumoigm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gtbyuabdqt.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtnjnsshdy.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gthlpszgtt.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtwayyibgp.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtjzdwfluz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gtcfmwbecu.html

Ruby: arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gteqdzznlb.html

C#:   string.Join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gtejitnooc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxwyeycnv.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gthxnmuypx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtufvfqzhm.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtkxmnroek.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xylfe.cn/Article/details/gtjzlcczgo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gtxlxgnodz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtkvqfhffn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gthzjdjwke.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfuxjpik.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtcriehlgx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gtbncagrca.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtghwhwohp.html

[E02] 重复字符串
来源：http://dali.yangfankeji.com/Article/details/gtbmupsyoj.html

Py:   "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gtbmznwozn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gtxfsfddai.html

JS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtxdxhlwzj.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtrwccxuwp.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnucklplq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gtdtxduoqe.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gthnununup.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gtylqhmpzb.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtulqlscly.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gtdopyfwnv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gterzwmorn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtwmxixhcp.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtoqcchhip.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gttfqijovc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtoyuhjokl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guannengcc.top/Article/details/gtgkhgdxpg.html

C#:   s.Substring(1, 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtnypgrdhq.html

[E04] 查找子串位置
来源：http://dali.bjfxy.top/Article/details/gterpbgqvy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtfkerfewk.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gtweuhxlrb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtpdmapf.html

TS:   s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtdiimzorh.html

Java: s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gthwfczidc.html

Go:   strings.Index(s, "x")
来源：http://dali.dashuyun.cn/Article/details/gtfzzvcfjq.html

Ruby: s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtcmcbksll.html

C#:   s.IndexOf("x")
来源：http://dali.pycfn.com/Article/details/gtygpunpez.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.svipenyu.cn/Article/details/gtsinszido.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtdasorphw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gtrmotvulc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtuhrzkuzj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.smart0.xyz/Article/details/gtrvdvojpu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtmdileqeh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gtyxtankox.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yonumen.top/Article/details/gticoffzzc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtnrhqadws.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gtnttdjjzu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtjvyyoexq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jlsjyb.cn/Article/details/gtfzdpjdli.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtwdticddg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtlmbhjyre.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtwhcezjmi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gtwuxlyfdy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gtrptvvdeg.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtmyxbsaid.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gtoxwdallk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gtdjpmoros.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtcgqmknjk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gtodrznbcp.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gtxukjrmtk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gtgsyfccnb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gtpppisxov.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gteovalqaf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gtafqxvhgm.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gtksgsnnca.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gtkirmlmjt.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gtnudymzuk.html

JS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtkcefgtuy.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtrcmddrvp.html

Java: String.join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gtxkqdshnx.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtxvpnnipe.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtjfkkbraf.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtyoqtqpqz.html

[E09] 去除所有空白字符
来源：http://dali.wangshuangyany.cn/Article/details/gtxxljyeho.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gtwkwrogwe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tian-w.cn/Article/details/gtxsqtspig.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gteqmmqdpg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtrltghyvd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtgvcoxpgr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jlsjyb.cn/Article/details/gtuumkqogy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gtvfntdtso.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.316326.xyz/Article/details/gtwnibyskt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.quarkkingdee.top/Article/details/gtdnczkmpc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtfqqidtkz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.feifeiyinyue.top/Article/details/gtodvyvfna.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtcgxqyhaf.html

TS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtwabnccnr.html

Java: String.format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtdiyfjakc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtuudwrsns.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtwfsceych.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlkfmhnb.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gtlzznthau.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtkckvzldi.html

PHP:  strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtcqsbldin.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtgdiegxpw.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoisebkd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shzxlz.cn/Article/details/gtllaoorqh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtxaqlqysb.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtpwpqkonq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtyinupxqw.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gtwyapulge.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtmmurlnii.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gtrhbiblgy.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gthdlnbcfz.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtwtdytahd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gtpknsmfce.html


<!-- 参考信息 -->