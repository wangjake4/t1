代发 wailian999

[D03] 在指定位置插入元素
来源：http://dali.ppjwa.cn/Article/details/gtdrqoutqw.html

Py:   arr.insert(0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtgukjnsnf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cqqwz.cn/Article/details/gtwnoivhbw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenlongwang.top/Article/details/gtiicfddhq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtuqnwfnwl.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gtodidplxn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zycfv.cn/Article/details/gtkyudohde.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxinkj.top/Article/details/gtsxqnbobt.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gtccflpozz.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtuodncmdf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtztopzlkq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gtelgknxwb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gtxbzqgzri.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gtrqoyramr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cdnleiting.top/Article/details/gthnqlzxiy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gtzxuvudoj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gzhubu.top/Article/details/gtjcnpehcr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gtjsfvcunl.html

[D05] 访问与修改元素
来源：http://dali.smart0.xyz/Article/details/gtjdzcrhwv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtlsawsxrn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbnrkdlh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gthjvjfvye.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gtxgzvfvof.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fzhhl.top/Article/details/gttokpvyzl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtsjjulnde.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtopklbihl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtvrlcnhcl.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtuaidfvey.html

Py:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtcoehoizs.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtjwhypuin.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtnuebztxy.html

TS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gtpmokvved.html

Java: list.size();
来源：http://dali.zhengqikj.top/Article/details/gtzrjzszdl.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtrbuxxlum.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gtullztgrs.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gtokkbpcvg.html

[D07] 切片 / 取子数组
来源：http://dali.hammf.cn/Article/details/gtxqmnhquq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cucudq.cn/Article/details/gtsoywwpia.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gttinbtrua.html

JS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gttmwjkacl.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtjashypva.html

Java: list.subList(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtdnccxyao.html

Go:   arr[1:4]
来源：http://dali.ehwqpu.com/Article/details/gtfyiiwycv.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gtvpdgaymv.html

C#:   list.GetRange(1, 3);
来源：http://dali.havefunace.top/Article/details/gtawiqhsek.html

[D08] 合并两个数组
来源：http://dali.hysaishi.cn/Article/details/gtiqabishe.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gthpjuyjrt.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gtxfwwrfyc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hammf.cn/Article/details/gthetgqglw.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gtemerickf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gtuwjbtfxi.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gtrhnqeazd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gtlqheymgk.html

C#:   a.Concat(b).ToList()
来源：http://dali.cheryme.top/Article/details/gtjnauegrm.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gtzprcvjgr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtbqgeskaw.html

PHP:  sort($arr);
来源：http://dali.yongpay.top/Article/details/gtyjnzhnly.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nwbrower.top/Article/details/gtefdwwqwz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhengqikj.top/Article/details/gtpocleadn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tanke756.top/Article/details/gtdiatizch.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtpedipkvc.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtsxfxhmzb.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gtdeunqlqk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guowangkeji.top/Article/details/gtnbseslll.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gtrmayewav.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtbjpolozl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaosqmdsy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtdkorgzdx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuanzhike.top/Article/details/gtmcbpuwhc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gtajxcyceb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaswxcihr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hfpthk.cn/Article/details/gtcmzkaryv.html

[D11] 反转数组
来源：http://dali.fzhhl.top/Article/details/gtcfsokccs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sweek.top/Article/details/gtzmcmjpzo.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gtnekraldh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cucudq.cn/Article/details/gtvtlqypfg.html

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gteuxfmxxa.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gtrdknsmed.html

Go:   slices.Reverse(arr)
来源：http://dali.hfpthk.cn/Article/details/gtgkzmokyf.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gtauquxayn.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gthlhsnnly.html

[D12] 查找元素下标
来源：http://dali.feifeiyinyue.top/Article/details/gtppryxpkm.html

Py:   arr.index(x);  x in arr
来源：http://dali.0kj1m.cn/Article/details/gtcsrbmfew.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtzsswotli.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtapalstcb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtrwutnvpq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gteokcxllk.html

Go:   slices.Index(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtzxxlmwbv.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gtkovmnsxr.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gtqmarlolq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gtuwyxrkos.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzcuxpay.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gtgmnwqckz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtgnjrjvch.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtzplpyspu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hysaishi.cn/Article/details/gtowsunghb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ydzc1.top/Article/details/gtxaiiasav.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gtopmfcuug.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gtloxiurwk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yueranfly.top/Article/details/gtvjmpeade.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hysaishi.cn/Article/details/gtpynwfttg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gtooqtntub.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtcezrhrda.html

TS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gtrbpizxzo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqahrtcd.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gtnzgbkzoe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gteehdaosh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daria6918.cn/Article/details/gtvyuqryhe.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gtzuxynjrd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gtbqidurss.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gtyugrvfda.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gteaiklrtd.html

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtrnrwdprk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgfzy.top/Article/details/gtyfxtwbju.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.svipenyu.cn/Article/details/gtukygdvkn.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gtfupppmzr.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gtmuozdzlj.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gthpnckglh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkhnrzav.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gtwqobxxhr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtlaadmlzs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtailfyazw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gtnhjsztyu.html

Go:   // 手写循环累加
来源：http://dali.hysaishi.cn/Article/details/gtrhifysnr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gtackfxrjd.html

C#:   list.Sum();  list.Average()
来源：http://dali.pengpengdd.cyou/Article/details/gtkxjsjtiv.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtfaubwrco.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtultaxmiq.html

PHP:  max($arr);  min($arr);
来源：http://dali.tian-w.cn/Article/details/gtwcvqxdsz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gtblddisxv.html

TS:   Math.max(...arr);
来源：http://dali.yj20258.top/Article/details/gtvhxdxuvn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pycfn.com/Article/details/gtgtxiewmy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtrtjmepxd.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gtpjjuaiel.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gtjaqqeefa.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gtbxmfbuey.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenzaomai.com/Article/details/gtvqqpszfj.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gtzccsauin.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gtyofbpagp.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gtlpixqqmr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yongpay.top/Article/details/gtlmjzlbbp.html

Go:   // 手写双层循环
来源：http://dali.vqdsnc.cn/Article/details/gtpnppphvz.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gtqqtnqkse.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtccxkmjhd.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gtcvvmsfeh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gtxxejvpfg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gtegomnetz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.c1oappe.top/Article/details/gtfjptelln.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtzpcyryxw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtutsksifl.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gtuobfxqrc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gtbtbbmufg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuxming.cn/Article/details/gtdqrcyvpd.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gtxfkhzalf.html

Py:   Counter(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtyslgcdpg.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtwidmhmqs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtynvqnjqm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gteixsvnhc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gtfytfltll.html

Go:   // 手写 map[T]int
来源：http://dali.xuetiantiany.cn/Article/details/gtkdnaaxog.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gtgdnzudvg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gtvtyrehgn.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gtrhhevcpw.html

Py:   x in arr
来源：http://dali.yvedp.cn/Article/details/gtwdmjvrow.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cqqwz.cn/Article/details/gtsfbapewh.html

JS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttmktnjh.html

TS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtvxtvetnr.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gthfsdjsyg.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gteyashngj.html

Ruby: arr.include?(x)
来源：http://dali.sweek.top/Article/details/gtrwktehfu.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtmjkjgces.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gogol.net.cn/Article/details/gthjrkgijm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gtzqtblafu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhiwuduotai.top/Article/details/gtmcugjess.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.bjfxy.top/Article/details/gtklcyystw.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtesvyquxh.html

Java: new ArrayList<>(list);
来源：http://dali.fengsongda.top/Article/details/gtnzooqtub.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtvaqjqyxb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtndxsmrll.html

C#:   new List<int>(list);
来源：http://dali.9152youxi.cn/Article/details/gtnzfidhor.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gtrfzrawrn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cashguo.top/Article/details/gtmvdaffco.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.svipenyu.cn/Article/details/gtoryrnfvb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtczqqevyn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gthytaoksh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenlongwang.top/Article/details/gttxzbwcjt.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtiaoczghp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aizwys.cn/Article/details/gtxdudkcas.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgfzy.top/Article/details/gtkriabrax.html

[D24] 字典 / Map 基本操作
来源：http://dali.jlsjyb.cn/Article/details/gthtzfacyc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ppjwa.cn/Article/details/gtnlgpkjog.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhixingplan.top/Article/details/gtoumbxedo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gtyfjbjmjk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtntaaoxwy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gtrrgfojky.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dashuyun.cn/Article/details/gtkexduvry.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gtatvtxnyt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gtihnkooyw.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gtevzpxyyw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gtfchzprgo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sxryk.cn/Article/details/gtjgvzigum.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tianlin.xyz/Article/details/gtsxetmjso.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtmhhsevng.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtvkzbdncn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigfzy.top/Article/details/gteqmcuqgb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gtyabfmmjq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gtgynjnmep.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtwbmtmqdc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gtdllmkenh.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gteprjruxz.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtbxkyrxoh.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtilztgrop.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtmugeycrq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yangfankeji.com/Article/details/gtbawyiumo.html

Ruby: arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtqnaopvje.html

C#:   string.Join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gtphycydkg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtimseahdy.html

E. 字符串处理
来源：http://dali.yuxming.cn/Article/details/gtshpdapho.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtfxnktntb.html

[E01] 拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtkvptjliw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.kuanghao11.cn/Article/details/gtvbdwqbqo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtmdfvzsdt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gthgwipjrv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtjixlxrvy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gtczfxwtqx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pycfn.com/Article/details/gtixzifdsv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gaohongyu789.top/Article/details/gtfpyhzhws.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtpecqjdsd.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gtkvrcmkyb.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtbobfnfds.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cucudq.cn/Article/details/gtvazsndem.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gthvdyqlko.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtapkzszrn.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtcvswkjas.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gtmxnpbhwf.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtwakxbaps.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gtpyrwaxbt.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gthykaksdl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gtoackjsvu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gteejkjsju.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtpjxsostc.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtwftmmtti.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtqrtyfbds.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dashuyun.cn/Article/details/gtyuawpvyl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jianghu66.top/Article/details/gtpkhjjyav.html

C#:   s.Substring(1, 3)
来源：http://dali.fzhhl.top/Article/details/gtpkchzidd.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gtbgqzomki.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttestufzq.html

PHP:  strpos($s, "x");
来源：http://dali.zycfv.cn/Article/details/gtuvudahrd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgfzy.top/Article/details/gtgcsfojjb.html

TS:   s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimwjroae.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtzjtgvosh.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gtxalqrzmu.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtkqqlwfog.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtkguwzlgh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zdqjudy.top/Article/details/gtdbzjtuwm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnsjcbqy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gtjwjlkgoi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtavmjnuxa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gtzezeqmxi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gtisirwlwr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigufen.top/Article/details/gtrfvwlshq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yonumen.top/Article/details/gtphhvjksr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gtieehetyw.html

[E06] 替换子串
来源：http://dali.tian-w.cn/Article/details/gtgrzfdmwi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgwkubjk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gotoacloud.top/Article/details/gtayrupvhz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtpxzjauhy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtvfiqcyig.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtyhkpgpxy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gtkpisycsn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gthevnbsrl.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtxflrzkat.html

[E07] 按分隔符拆分
来源：http://dali.dianchejie.cn/Article/details/gtquntntwr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gaohongyu789.top/Article/details/gtcpxyokid.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gthdlczlrg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gtcqdffhze.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gtnpvyuwuf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.havefunace.top/Article/details/gtcqqeivbq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gtzspfccqq.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gtvfdtwuui.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gtdwkdsnhk.html

[E08] 数组按分隔符合并
来源：http://dali.wangshuangyany.cn/Article/details/gttyyvoqeb.html

Py:   ",".join(items)
来源：http://dali.hammf.cn/Article/details/gtoowemhcr.html

PHP:  implode(",", $items);
来源：http://dali.wangshuangyany.cn/Article/details/gthovbdmbs.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtavrfaked.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtrgciehha.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtwhxpdvif.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gtedimnqwx.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtaaldsbct.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtcfhlzvou.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gtxayipjcc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aibaodan.cn/Article/details/gtieuqsokp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtpsyyggrp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtnmsnltry.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtcfnlmnkt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtribcmkmr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gtjydgepgk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gttjhzldlh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtwahjbsme.html


<!-- 参考信息 -->