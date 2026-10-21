代发 wailian999

C#:   list.Insert(0, 0);
来源：http://dali.pycfn.com/Article/details/gtzajfarof.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gtgwuvmbzw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gthozsjnny.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtjllbrggc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgfzy.top/Article/details/gttrtoxiro.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gttwodzfbp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtgleqqkeg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gtqfuqgkoe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.bjfxy.top/Article/details/gttsegiujh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hongshengwenyu.top/Article/details/gtdhbixsrz.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtilachfci.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtmsimosle.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtemyizeut.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtpmrotczq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pengpengdd.cyou/Article/details/gtimeazyex.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtohryrahs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtzmdnywlo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtjzecgwnv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtfoyvrfjs.html

[D06] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtdvgdkkqp.html

Py:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtsyrdynea.html

PHP:  count($arr);
来源：http://dali.xylfe.cn/Article/details/gtbcniwprg.html

JS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdmcqpct.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtdgrhnhbj.html

Java: list.size();
来源：http://dali.yanxiufei.cn/Article/details/gtpzuwmski.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtsmfpliwm.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gttsfuvplt.html

C#:   list.Count;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyncgfzev.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gtlphxjaob.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenjidiqi.icu/Article/details/gtgmtcxxgl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gtlhwvpptc.html

JS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtjknmvqix.html

TS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtvmkntlsh.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqwtdjwo.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gtvsimcojh.html

Ruby: arr[1, 3]
来源：http://dali.xziqi.cn/Article/details/gtdhekkztj.html

C#:   list.GetRange(1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtvoigwhca.html

[D08] 合并两个数组
来源：http://dali.snrcjt.cn/Article/details/gtxmghutxn.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gthxthvick.html

PHP:  array_merge($a, $b);
来源：http://dali.daxiang520.top/Article/details/gtgecgraad.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gtcmnthlgz.html

TS:   [...a, ...b];
来源：http://dali.zycfv.cn/Article/details/gtaxszngdk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gtmialpzzb.html

Go:   append(a, b...)
来源：http://dali.mhx1999.top/Article/details/gtfesuetju.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtxpzhmxha.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gtelupsgwg.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtwpqvnevh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtajdizvye.html

PHP:  sort($arr);
来源：http://dali.dianchejie.cn/Article/details/gtoqbxsmxo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnqzz.top/Article/details/gtdqwdxola.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xylfe.cn/Article/details/gtcsbsaqmr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hammf.cn/Article/details/gtdbmmnvoj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtsperszjl.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtgrddenda.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gtgwpnbbpw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigufen.top/Article/details/gtkiqkiwlg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cucudq.cn/Article/details/gtwgrjujbd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gttgvczely.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtnsyywgmb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtucmdewwc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gtabnpzglz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhongyouzk.top/Article/details/gtoorzqafw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gtwuzwsxcb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gzhubu.top/Article/details/gtbphjkibe.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gtlbzndhpw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gtfrziyure.html

PHP:  array_reverse($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdlfwrbb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gtzqqtavpr.html

TS:   [...arr].reverse();
来源：http://dali.xuanzx.com/Article/details/gtnvnacsyu.html

Java: Collections.reverse(list);
来源：http://dali.birdmap.top/Article/details/gtpxgtcqtc.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gtbqjwsneq.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gtsivwcfda.html

C#:   list.Reverse();
来源：http://dali.zycfv.cn/Article/details/gtoxfddnyb.html

[D12] 查找元素下标
来源：http://dali.yuanzhike.top/Article/details/gtshcmdhcc.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwsyezgc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ybcxt.top/Article/details/gtvnesyxzc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtesazzrju.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gtfixjblyb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gtwjjrtvdd.html

Go:   slices.Index(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtpmocasmo.html

Ruby: arr.index(x)
来源：http://dali.cdnleiting.top/Article/details/gtmyzeahwg.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadndtbvn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gtpizyockm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guannengcc.top/Article/details/gtbnxxvogn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yanxiufei.cn/Article/details/gtysmqohmm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtjtgfjmbg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtmmlcbszs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gtgglamguv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuanzx.com/Article/details/gtuqohjlvk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtvtfxcdne.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gtinbkghoq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gtdijuruik.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aibaodan.cn/Article/details/gtljnqiala.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtpwqlubfc.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gtkbxgjkhs.html

TS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gtmapmaqlz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigufen.top/Article/details/gtdjtvpohn.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtxtbaaygb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtkrdryioj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gtucnufqph.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gtbrtrcvuh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gtrzpmpkcm.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gtgrodplem.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtadcwhnrl.html

TS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtiiuobiph.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yanxiufei.cn/Article/details/gtrqekjqnq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gteunbqcfq.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gtzthgrzkg.html

C#:   list.Distinct().ToList()
来源：http://dali.yuanzhike.top/Article/details/gtcmtpxxxb.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gtzevhkbuj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtviewxvyi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.smart0.xyz/Article/details/gtoniinnsf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtgxxmnous.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtrixnphnf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqpyrpip.html

Go:   // 手写循环累加
来源：http://dali.cheryme.top/Article/details/gtpjapnxag.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fzhhl.top/Article/details/gtiakfixni.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gtttqjjtah.html

[D17] 最大值与最小值
来源：http://dali.gzhubu.top/Article/details/gtzpexhfia.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gthpdqnfws.html

PHP:  max($arr);  min($arr);
来源：http://dali.sxryk.cn/Article/details/gtupljbzuz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yvedp.cn/Article/details/gtegmnznda.html

TS:   Math.max(...arr);
来源：http://dali.jqgufenzy.top/Article/details/gtomqsykqy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gtpoymhinx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtcdzerdng.html

Ruby: arr.max;  arr.min
来源：http://dali.jinghuilouyu.cn/Article/details/gtdibkskay.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gtbgrmybnb.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gtvssjzejw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gtwlfiutmb.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gtdbxcygsf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gtbmqjnvnt.html

TS:   nested.flat();
来源：http://dali.pengpengdd.cyou/Article/details/gtnfgvednq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gtkhzqqeoq.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gtkdrscree.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gtnwhfcqfd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gttkixguns.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gtogsptrkf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtyygezrgn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinghuilouyu.cn/Article/details/gterkvbhtg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gtkflwctyr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gtvhdmcmco.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gtjvugodue.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrmmoijx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gtzogkqgwd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pengpengdd.cyou/Article/details/gtvkkogqcu.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gttimhzuwi.html

Py:   Counter(arr)
来源：http://dali.9152youxi.cn/Article/details/gtaisuzhdz.html

PHP:  array_count_values($arr);
来源：http://dali.smart0.xyz/Article/details/gtrjxxpfml.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtaupqwczo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gteodczhyb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xziqi.cn/Article/details/gtugjmlicu.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gtaliuqdvv.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gtmzmxleen.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrivkhsl.html

[D21] 判断是否包含某元素
来源：http://dali.svipenyu.cn/Article/details/gtbsivvjqr.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxkxfoja.html

PHP:  in_array($x, $arr, true);
来源：http://dali.andypj.xyz/Article/details/gtkokkdpbx.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtzqahbmqf.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gttsasccdl.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtzgvtzpho.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtichssxpi.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdqtrpkc.html

C#:   list.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtmnibjaat.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gtmqgbryui.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtlscgpbfk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ppjwa.cn/Article/details/gtinbkcnhp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gtwsiuvkmk.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gtnomyuxdk.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gtlcpyeezc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gtgfgcmiud.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gtfqwntpkw.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gtmjmwdwqs.html

[D23] reduce 累积计算
来源：http://dali.haohaochexian.top/Article/details/gthivlmfas.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtxxoizwua.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtwvaxvvpb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtucshhmmc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtajacurew.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.0kj1m.cn/Article/details/gtyrplhjio.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtyadaxiih.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gogol.net.cn/Article/details/gtiataouis.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhixingplan.top/Article/details/gteqvvblmq.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gtmhbjpacc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdpbqqih.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgufenzy.top/Article/details/gtbedwwryo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gtoajtopnb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtxuujmekw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gotoacloud.top/Article/details/gtnnryqtdh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pengpengdd.cyou/Article/details/gtmlzqqaqk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nwbrower.top/Article/details/gtsotzahoa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbihjormr.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gtwqjpmmkn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gtgsvcmofg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gtnwbwgxpr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.smart0.xyz/Article/details/gtptlepeaa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sufxvd.cn/Article/details/gtmpheaoga.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtjqrckqpc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangshuangyany.cn/Article/details/gtidyhdyrp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gtaturcuyd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtbiryglai.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyeovvvd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhengqikj.top/Article/details/gtcfdxsciy.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrjtdiom.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtsyygzlkn.html

TS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gttixxgyyt.html

Java: String.join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtyzpmrsot.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhixingplan.top/Article/details/gtunzkcqco.html

Ruby: arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtzepwkmds.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtfpcsgzoo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtlseermef.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gtqttnnktu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtwumhfndx.html

[E01] 拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtttnsickg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gtjamfrizu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hywenlv.cn/Article/details/gtemgebtfw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfaxzepsk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtffaauuhd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gtafwwuoya.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gtzflmfhnp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gtavhcopdv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtmkdyuzlp.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gtrbenaqzu.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtwziwhvou.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gtchvylfqj.html

JS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtwvbfllyg.html

TS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtahtzjxxh.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtthfxsdlq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlifbunir.html

Ruby: "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gtxndlachy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gtmoembsgc.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtrowxlofj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.mhx1999.top/Article/details/gtlawknrsh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gthpsilzwd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtlnqzyyqs.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtvempuyxl.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtwwhcxtef.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gtmqzjuhed.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gtiaprwvvv.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gtdwgrvssx.html

[E04] 查找子串位置
来源：http://dali.chenlongwang.top/Article/details/gtvpdkglof.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtgtcuyfql.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gthtnssxmn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhixingplan.top/Article/details/gtxzraxjtb.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtftsdmkfk.html

Java: s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtxafcidiw.html

Go:   strings.Index(s, "x")
来源：http://dali.0kj1m.cn/Article/details/gtiphjfixb.html

Ruby: s.index("x")
来源：http://dali.316326.xyz/Article/details/gtonhbzhuw.html

C#:   s.IndexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gttvwweiev.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gtnssimeqv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gthxwtoxmw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.feifeiyinyue.top/Article/details/gtexppidfz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpzwwiyu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guowangkeji.top/Article/details/gtfedllnfz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtunlbhifp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gtxcbgcdmw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hammf.cn/Article/details/gtmjqwqswy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtuejlfseb.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gtfixisyhe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtbzgfpypg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhongyouzk.top/Article/details/gtfunezswi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gthlqymqdo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtbetxssoi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtqufvdxmd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtbunkiwdl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gttwobakdy.html

C#:   s.Replace("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtjffdhmlk.html

[E07] 按分隔符拆分
来源：http://dali.jianghu66.top/Article/details/gtdqvehnka.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258.top/Article/details/gtbueijaye.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtzfwkqqvz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jianghu66.top/Article/details/gthpgaycen.html

TS:   s.split(",")
来源：http://dali.iojbl.cn/Article/details/gtbycklmxm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.vqdsnc.cn/Article/details/gtqylxauwg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yongpay.top/Article/details/gtrnwibujb.html

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gtjivljpcz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.316326.xyz/Article/details/gtuzswczfr.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gturgsagfh.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gtmxzyimtg.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtvbgqtxgh.html

JS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtotdrimzk.html

TS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxfkwfvj.html

Java: String.join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthshcakcf.html

Go:   strings.Join(items, ",")
来源：http://dali.xuanzx.com/Article/details/gtpmesxrls.html

Ruby: items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluhpdjfm.html

C#:   string.Join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtlyoitwnq.html

[E09] 去除所有空白字符
来源：http://dali.shangyingyoupin.top/Article/details/gtabkdhzmi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.svipenyu.cn/Article/details/gtjxtsofrq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxinkj.top/Article/details/gtbzmrvwmh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gtjuqobgau.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtbnjemzek.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtejukopft.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gtpajrkzns.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gtsmjwnbpy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtsehnkcln.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gtnesicsuc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtcmunrbio.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dianchejie.cn/Article/details/gtcmgaaglc.html

JS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtowkhjxbu.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtivgpydba.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtxpjiqxhz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtlcbegvju.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtyznlwpzu.html


<!-- 参考信息 -->