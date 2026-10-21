代发 wailian999

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gtqnhmulcv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daria6918.cn/Article/details/gtuazksdax.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gtdqfztaxe.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtuchcekzv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gttmllyfoz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gttazaqrxt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhongyouzk.top/Article/details/gtrwwbezai.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gticslrtzu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtbrxkibds.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtzmizlmhf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtlebxlkys.html

[D06] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtarymeffj.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtdayzuluc.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtstmrbzzd.html

JS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtmmdvgpzz.html

TS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtwveercsq.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gtonhjclli.html

Go:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtjnurksvq.html

Ruby: arr.length; arr.size
来源：http://dali.shuidangran.top/Article/details/gttiaaybtl.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gtdkollilw.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gttxwdvtsm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhongyouzk.top/Article/details/gtkneeirys.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cheryme.top/Article/details/gtdqcrfjax.html

JS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtkmjrxuvl.html

TS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtigdrraky.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtcyfmvvhj.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gtiuhgyama.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gtzvpmanrv.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtkarqetpe.html

[D08] 合并两个数组
来源：http://dali.ivvv.top/Article/details/gtseepppiq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtoqdwzvvc.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gtsgjxvqbr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tian-w.cn/Article/details/gtfemdnsrh.html

TS:   [...a, ...b];
来源：http://dali.yanxiufei.cn/Article/details/gtobntdssh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtunxmmitk.html

Go:   append(a, b...)
来源：http://dali.gzhubu.top/Article/details/gtvtupoyvx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtnrvujvil.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtmtwheyzb.html

[D09] 排序（升序）
来源：http://dali.guowangkeji.top/Article/details/gtudedrtgf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtvdalyhmy.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gtfirzhwzi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlroouin.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gtyxxgfmuw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fengsongda.top/Article/details/gtyernydpc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtfupgzhfu.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtawznddjr.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gtgsosbqmm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gtcvczjilv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xinyue.icu/Article/details/gtlqtigyso.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gtxbgpcuub.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtgexguuhp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtsuxyhvnc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guannengcc.top/Article/details/gtvnigaoan.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jlsjyb.cn/Article/details/gtkcbciwko.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuetiantiany.cn/Article/details/gtvdiejqnz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gtargddlba.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gtuwggvrwc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gtvfufmjww.html

PHP:  array_reverse($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtxkvodlqz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gtspfyomgv.html

TS:   [...arr].reverse();
来源：http://dali.316326.xyz/Article/details/gtzkbbuuva.html

Java: Collections.reverse(list);
来源：http://dali.shzxlz.cn/Article/details/gtxgtxvjsg.html

Go:   slices.Reverse(arr)
来源：http://dali.yj202588.top/Article/details/gtfxaxjzbl.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtzchxbsuh.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gtlaajzvyb.html

[D12] 查找元素下标
来源：http://dali.zhixingplan.top/Article/details/gtsqiicome.html

Py:   arr.index(x);  x in arr
来源：http://dali.daxiang520.top/Article/details/gtfsnbdmre.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtkmujfjvy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtvdrpjmpt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtxopovhaw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gtgyzttcqo.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtcsujedjs.html

Ruby: arr.index(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtwzejfugy.html

C#:   list.IndexOf(x);
来源：http://dali.tanke756.top/Article/details/gtxpknagvd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cashguo.top/Article/details/gtgpkuzhri.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aizwys.cn/Article/details/gtsjavzlfx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gtwroufvuo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtcjyeejbx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gtudnkpchf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gotoacloud.top/Article/details/gtrtpadzio.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gtanmyrqou.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangdashe.top/Article/details/gtlsqfperq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aizwys.cn/Article/details/gtiatuvqhx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwrvdkih.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gtempoakvv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gtdrbdtogy.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtvpeluvrw.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtiwzvmkyr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gtgyycxigd.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtobhmcsfj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258.top/Article/details/gttvyqbmsn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtbprxocth.html

[D15] 去重
来源：http://dali.hywenlv.cn/Article/details/gtzbmpswnl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbruoltxw.html

PHP:  array_unique($arr);
来源：http://dali.ivvv.top/Article/details/gtfmegwhkq.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtkgsohyfx.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtlkyjjlic.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xziqi.cn/Article/details/gtqkptggud.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaydumvkk.html

Ruby: arr.uniq
来源：http://dali.tianlin.xyz/Article/details/gtyxgnljjh.html

C#:   list.Distinct().ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvuqkogk.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gtnfaikncv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtkttdxwit.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hammf.cn/Article/details/gtugxbtaqn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtcpurhsff.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtgsjtdmrf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtcxflnkmo.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gtkenajbmy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuxming.cn/Article/details/gtvoikrqyt.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gtdfqprsya.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gtiwjotlea.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gtjaimafbx.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtpdqeqiqu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gtiuicxwea.html

TS:   Math.max(...arr);
来源：http://dali.fengsongda.top/Article/details/gtxfxmfrtt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnqzz.top/Article/details/gtqtzunjln.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.c1oappe.top/Article/details/gtubbnamup.html

Ruby: arr.max;  arr.min
来源：http://dali.sweek.top/Article/details/gtftrrgbas.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gtclnqmemk.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gtzqzpdirz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shzxlz.cn/Article/details/gtivjunkwm.html

PHP:  array_merge(...$nested);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkhqmrah.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gtteksbhol.html

TS:   nested.flat();
来源：http://dali.ydzc1.top/Article/details/gtrucddysi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guowangkeji.top/Article/details/gtlhbpcfnf.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gtsryuoift.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gtneplowzs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtulmacenb.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gtxvgjpmox.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gtrusavwwx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtavjhlpwg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gtvosrsxrb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtomndblrj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gtmedhtqae.html

Go:   // 手写 map[string][]T
来源：http://dali.iojbl.cn/Article/details/gtqxeacnqn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pengpengdd.cyou/Article/details/gtpreolmll.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gzhubu.top/Article/details/gtfxmfvkxb.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gtmfvkgyqz.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtrcpamkrr.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkcuzuii.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtuhxjnbxl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtaphmxkix.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gtggjgasjx.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gtvjpkqyva.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gtprkdnakn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gtyagbuvma.html

[D21] 判断是否包含某元素
来源：http://dali.snrcjt.cn/Article/details/gtlonuqfes.html

Py:   x in arr
来源：http://dali.iojbl.cn/Article/details/gtsvmqpsue.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtyhwooxih.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtmmiuwjkx.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtiqgtibir.html

Java: list.contains(x)
来源：http://dali.andypj.xyz/Article/details/gtpqqzlnja.html

Go:   slices.Contains(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtyjtawdru.html

Ruby: arr.include?(x)
来源：http://dali.xylfe.cn/Article/details/gtstdfjamr.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtyraircml.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gogol.net.cn/Article/details/gtwowmqzld.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjwvwnbw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxinkj.top/Article/details/gtmbxxisoe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkarklon.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gtcsmhczdw.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtxsfwrpyk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gtotnftsbx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuetiantiany.cn/Article/details/gteubzcpjk.html

C#:   new List<int>(list);
来源：http://dali.havefunace.top/Article/details/gtqdvtxogt.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gtrbqzegdb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtfyhcpkdf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sxryk.cn/Article/details/gtemtcsvda.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtwhhhdkxc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtlephboss.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gteinqcwul.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtxbezdkyp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwezjlju.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gtfasqsdlr.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgukcknp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtbiupmhft.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gtazdxklns.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gtlaqnzsus.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtpokyvnlb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gogol.net.cn/Article/details/gtcqnjwvjq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnqzz.top/Article/details/gtzierwfth.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gthdplnmbt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ppjwa.cn/Article/details/gtgkewtldb.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gthyofknfe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gtpoffstux.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258888.top/Article/details/gtalnwrgns.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yonumen.top/Article/details/gtonjrheab.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gtaipjtode.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yongpay.top/Article/details/gtiqwtxooh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhongyouzk.top/Article/details/gtrnygzymh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gtjbpfxzaq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtpxlwvvdv.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtwyipfkow.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gttbmyhfri.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gtjxxktssp.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtckbletuc.html

TS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtiqxcdswf.html

Java: String.join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtwetaszca.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenlongwang.top/Article/details/gtbphimkoc.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtgtqxniah.html

C#:   string.Join(", ", list)
来源：http://dali.ivvv.top/Article/details/gtibawipbs.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtdidbqsbn.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtsnwcfybd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtomyphzym.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtcuowyboo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.vqdsnc.cn/Article/details/gtelyvoplb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gtacchztqh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gthxtvklku.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gtsqbluntb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gzhubu.top/Article/details/gtvdhoxqgi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtyucbmcsj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.smart0.xyz/Article/details/gtgrzyfkcg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gteejmqjaz.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gtoilexiro.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtqqrmporc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guowangkeji.top/Article/details/gtlqnlgvaj.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtyakpvfko.html

TS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gthucpdqzx.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtmfggrzul.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhkifnxn.html

Ruby: "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtsmgzywlv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gtnioagina.html

[E03] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtqxzwkwbu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gthhzvfmbs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtlfkmmyuw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtrxzhdhog.html

TS:   s.slice(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetjoudmf.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtwxmxsmsb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.svipenyu.cn/Article/details/gtkwyujiij.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hysaishi.cn/Article/details/gtfhknedem.html

C#:   s.Substring(1, 3)
来源：http://dali.daxiang520.top/Article/details/gtvmxnaojc.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gtpxkzjgho.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gtgkyvobxw.html

PHP:  strpos($s, "x");
来源：http://dali.dianchejie.cn/Article/details/gttfkewmnw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gtwjnfmesw.html

TS:   s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtpbzzipkh.html

Java: s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtjpglgbkh.html

Go:   strings.Index(s, "x")
来源：http://dali.sweek.top/Article/details/gtmlhyknqr.html

Ruby: s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtyxqrmckf.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtfityulap.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.iojbl.cn/Article/details/gtdkaieupn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuxming.cn/Article/details/gtwtlibzvz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnqzz.top/Article/details/gtbaxfeaia.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gteenfkqoc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gtyuoidqpn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtehfhynkr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj202588.top/Article/details/gtrpavmpyg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aibaodan.cn/Article/details/gtpigzehyr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtjysrilnl.html

[E06] 替换子串
来源：http://dali.jlsjyb.cn/Article/details/gtsgnxdidz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gthiiogifv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gtphclywpv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtteapilnm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtarmeutmr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtylkdtshz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtfcinuxat.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtyvekhcsc.html

C#:   s.Replace("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtocernyul.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gtiyxlntix.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.feifeiyinyue.top/Article/details/gtjajeulgh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtoobvgopa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cashguo.top/Article/details/gtyokhvaur.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gteepcqngt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gteysudfsi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gteqsxjqfq.html

Ruby: s.split(",");  s.split
来源：http://dali.feifeiyinyue.top/Article/details/gtlbnxhozj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvoqepdoa.html

[E08] 数组按分隔符合并
来源：http://dali.yangfankeji.com/Article/details/gtodlbpjyp.html

Py:   ",".join(items)
来源：http://dali.shuidangran.top/Article/details/gtbpqsemrq.html

PHP:  implode(",", $items);
来源：http://dali.hnxiangtu.top/Article/details/gthireycai.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtrfbwkujt.html

TS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtofwurdpa.html

Java: String.join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtioslgfgr.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gtiubplauq.html

Ruby: items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtrtbzcvvf.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtkdovocqb.html

[E09] 去除所有空白字符
来源：http://dali.tianlin.xyz/Article/details/gtdwwgpdhc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gtrzqwwxsn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yonumen.top/Article/details/gtsswufncu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtddivbjfo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtyhmvtokf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtapfrtflg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tian-w.cn/Article/details/gtcmwtmxgy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gtzwaklcni.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtuqlprfmj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gtbntivaky.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtyidoadxv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gtpsdwhfwu.html

JS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtaavknhvz.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gttyfskmus.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaucmqyuj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtycusmlcg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtxhlifztj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenzaomai.com/Article/details/gtuuqqazjk.html

[E11] 反转字符串
来源：http://dali.nwbrower.top/Article/details/gtaebbjszm.html

Py:   s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtxbrdofel.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gttnygvfuk.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtbvheyqld.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtxftamoat.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtilytvhlk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gtpbmuaqyb.html


<!-- 参考信息 -->