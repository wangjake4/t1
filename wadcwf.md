代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gtnlmicpvl.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gtihjkjlcq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gteymapffx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgybdqotg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtkyjvvjny.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cdnleiting.top/Article/details/gtnbfdpvhg.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gtdsfdsfef.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtigrlwbtd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtufduqszb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtsdwtjgym.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gtfljgcnrw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.c1oappe.top/Article/details/gtbxnvnrwe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtgwtvezzc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtcsyecmsn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvycsorb.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtadlqurcr.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtjaxbnwxt.html

PHP:  count($arr);
来源：http://dali.tanke756.top/Article/details/gtkdgmortw.html

JS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtnieabjeu.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gtslmliehj.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gtvxfdrbai.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtyvkxebnq.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gthihslmgj.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gtsbzukhtx.html

[D07] 切片 / 取子数组
来源：http://dali.pycfn.com/Article/details/gtdayrcjqo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gtldhgocao.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtzpsrebag.html

JS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtciwghqub.html

TS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtuevsnyyu.html

Java: list.subList(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtlarwpnav.html

Go:   arr[1:4]
来源：http://dali.zycfv.cn/Article/details/gtephiadfl.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gtvwktclrb.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtkbaqxmcv.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gtnpsamufd.html

Py:   a + b;  a.extend(b)
来源：http://dali.birdmap.top/Article/details/gtvgmwsehb.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gtvcixcujl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gtfhgepkcu.html

TS:   [...a, ...b];
来源：http://dali.xinyue.icu/Article/details/gtbhqaolbs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jyoumei.cn/Article/details/gtwltmskqe.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gtsudytkyb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gtbaazkylo.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtrjwjoskt.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gtizfigkjq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtnrwibcir.html

PHP:  sort($arr);
来源：http://dali.cashguo.top/Article/details/gtdykjshsr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gthtmtmpvm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuetiantiany.cn/Article/details/gtzrogxeyr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.birdmap.top/Article/details/gtzvauexfv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtkdmqjjfm.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtfmusfkzt.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gtuaigtmas.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gttvdonoyj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gttlpqujot.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtjbnrqxjl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtqzwikpil.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gtlgcgbwje.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xziqi.cn/Article/details/gtvjotftnw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gtfkqgyzse.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gtymmyubtf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gthpykvrwc.html

[D11] 反转数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvfyyxjm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnqzz.top/Article/details/gtkorxqgar.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtflxaswrw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.feifeiyinyue.top/Article/details/gtxabxerqa.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gtrofifmyz.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gtcykdohsq.html

Go:   slices.Reverse(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtauuwhseb.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gtylgxesud.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gtgeidyhat.html

[D12] 查找元素下标
来源：http://dali.xuetiantiany.cn/Article/details/gtwixonkfp.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gtzhwbvbsi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gtfueyuwxh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtlkfmcwhm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtywmtikqj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjuqloxy.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gttyagtnqk.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gtwyngnywn.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtwwmrczid.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj202588.top/Article/details/gtpzoazlao.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtnhwgnzll.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258888.top/Article/details/gtgdqfucvj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtbccndnap.html

TS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtklksabpp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hysaishi.cn/Article/details/gtglozqypo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gtwkrzgcnj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sweek.top/Article/details/gtektjqvqh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtbicvvvkt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtlupiuj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenzaomai.com/Article/details/gtlmyuyldh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sufxvd.cn/Article/details/gtqxofvnur.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtlpumkkxw.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtnnchudfh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gtapdvsidl.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtdxrbxgjz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yonumen.top/Article/details/gtgxikrrqp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gzhubu.top/Article/details/gtkfhtbhew.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydtanuht.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtblhzllxl.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdkhaekg.html

JS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtcoeebndd.html

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtjqyskizf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gtkxrjbvqy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pycfn.com/Article/details/gteuzkmzkr.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gtkbbstbms.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigufen.top/Article/details/gtlkdqlely.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gtdrhwcoqh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gtixbnpttc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.c1oappe.top/Article/details/gtxoufpjpk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtbayqgzyp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtsqfxkpal.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj202588.top/Article/details/gtaqckernm.html

Go:   // 手写循环累加
来源：http://dali.jinqigfzy.top/Article/details/gtxakehjtq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gtatwqnmyn.html

C#:   list.Sum();  list.Average()
来源：http://dali.havefunace.top/Article/details/gtabeoywln.html

[D17] 最大值与最小值
来源：http://dali.jiagoushi.top/Article/details/gthrrbkvmr.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtmtzslljw.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gtfzolubbc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nwbrower.top/Article/details/gtycvrdhaa.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtnjhayobk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnqzz.top/Article/details/gtzwaapvxq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtmzsaxerx.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gtzkvgddfg.html

C#:   list.Max();  list.Min()
来源：http://dali.xylfe.cn/Article/details/gtgwurtuag.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigufen.top/Article/details/gtnhpdjetb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258888.top/Article/details/gtcjpftidf.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gtnnmrryqs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gtxxcrjetz.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gtesbdeukr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtxgzatbnt.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gtsvbvrjtk.html

Ruby: nested.flatten
来源：http://dali.tanke756.top/Article/details/gtanjouldb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtuokyopup.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gtpimmxono.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtrcqaxhpe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cheryme.top/Article/details/gtxaqphijd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.iojbl.cn/Article/details/gtckduyikt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtvodfxycd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gtjnetpnhp.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gthhydjqef.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gtzumzdvyq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gtxlebuocf.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gtnujzvvce.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gtxsozswev.html

PHP:  array_count_values($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiynocicd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtjhadmgzg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtvnetzdbg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gtftnlqgey.html

Go:   // 手写 map[T]int
来源：http://dali.nanxuanxn.top/Article/details/gtoyyvodyq.html

Ruby: arr.tally
来源：http://dali.chenlongwang.top/Article/details/gtuqynzsgo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gtaahqfdar.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gtgdpbcoml.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gtsnoinatl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuanzx.com/Article/details/gtpnpjvjaw.html

JS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtpwamhepf.html

TS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtqvzvvwyu.html

Java: list.contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtzdmwuuuw.html

Go:   slices.Contains(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtxlujrydf.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gtsueyrmwu.html

C#:   list.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtfocstbcv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnxiangtu.top/Article/details/gtcblmzrsz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gtwyafzshj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gtnerjjslp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtjbcpymei.html

TS:   [...arr];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbgyzhdn.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gtitxfhcyp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtenpvvtwg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gtaftgwpje.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gtbayylxsu.html

[D23] reduce 累积计算
来源：http://dali.zhengqikj.top/Article/details/gtxojkkdjq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gtnycbhiix.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtbrvmvozy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gthsjeiwuj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtmokbvdqe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gtuowvimge.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtsjeosliw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jiagoushi.top/Article/details/gtfrkrfxko.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhiwuduotai.top/Article/details/gtmofwizlw.html

[D24] 字典 / Map 基本操作
来源：http://dali.xziqi.cn/Article/details/gtjxcbbacg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gtwbfokufa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gtltcdbqhq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrsljojit.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtypwbrvns.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yangfankeji.com/Article/details/gtwqbygkwd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gtameocozj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gtxgyfsoag.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ppjwa.cn/Article/details/gtxjzevbel.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gtkudungik.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gtpyticqoc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hfpthk.cn/Article/details/gtgevkwtfu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zycfv.cn/Article/details/gtorfgewoq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gtbvuakksr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtuychonuc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gtquglcpde.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbwdlutn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gteqcbuced.html

[D26] 数组转字符串
来源：http://dali.dashuyun.cn/Article/details/gtaqqgupoh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtmdlgpjkc.html

PHP:  implode(", ", $arr);
来源：http://dali.daxiang520.top/Article/details/gthfkxsgza.html

JS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtizkhykop.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtedrirmct.html

Java: String.join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtetbvostt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgufenzy.top/Article/details/gtxppbmkce.html

Ruby: arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtppbatuik.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzjwdlxs.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtnjwyeuzc.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gtzwhhuuou.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjmtwgqix.html

[E01] 拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtcaauduyf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigufen.top/Article/details/gtzdosmmvt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hywenlv.cn/Article/details/gtivbruuvk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtotuzbdvn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtiahavzvt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzecxmwyn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ehwqpu.com/Article/details/gtbtsdpojx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gtjjqtzknt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtemlpqxyl.html

[E02] 重复字符串
来源：http://dali.hnxiangtu.top/Article/details/gteaxgmovd.html

Py:   "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtnjjyuxqy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtfgygdyua.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtzslfrxmt.html

TS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtchilaxnn.html

Java: "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtjwbshksi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258888.top/Article/details/gtmpdkqzcz.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtviopzqqe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gttosrsrxh.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtrqvvgbqy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ehwqpu.com/Article/details/gtaqlqeljj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtvegqyluy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtmglcyunq.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtdnlpgghb.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtbzhscbsr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gtvaoitqys.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jianghu66.top/Article/details/gtkmlzztig.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gtavwihsrv.html

[E04] 查找子串位置
来源：http://dali.tianlin.xyz/Article/details/gtacqeyjhe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtoghfwkik.html

PHP:  strpos($s, "x");
来源：http://dali.tanke756.top/Article/details/gtpkkqnonf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nwbrower.top/Article/details/gtdxxihxkr.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtwcdwezll.html

Java: s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtvaxevahp.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gtrpgnctco.html

Ruby: s.index("x")
来源：http://dali.zycfv.cn/Article/details/gtbpjypmcf.html

C#:   s.IndexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtwxzhimoz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gtbhdlkhzr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gthjsbwgru.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gtwiazdsry.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtbmxvhuln.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jianghu66.top/Article/details/gthzaphqgz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtikxbbzab.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gtcbhlcckz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gtktlcmwll.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtnuxbkgak.html

[E06] 替换子串
来源：http://dali.xinyue.icu/Article/details/gtwtzoywis.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtfslojmfk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gtetfekfzv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtjctovzpn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtfgrlbefz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtnlpixqer.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtxyswtdbu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtbjhsyjwz.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtsxhrqbul.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gttgkbhrga.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkomrwew.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtappkrptw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gtwrvkbxxw.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gteetxbgdy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcekmnck.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtbwmcnxnc.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gtuzhpetlc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gtrxkqbltb.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gtkcqsgpjy.html

Py:   ",".join(items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhmnphhd.html

PHP:  implode(",", $items);
来源：http://dali.wangshuangyany.cn/Article/details/gttlzhjayf.html

JS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtfrgefirb.html

TS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtmhpxtjdx.html

Java: String.join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gtvvknavhi.html

Go:   strings.Join(items, ",")
来源：http://dali.zdqjudy.top/Article/details/gtkgpazvrf.html

Ruby: items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtedwoiyel.html

C#:   string.Join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtmjumnpkc.html

[E09] 去除所有空白字符
来源：http://dali.hnxiangtu.top/Article/details/gtszkzylog.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gtwvypakks.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtkujfwboe.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtbexjsjez.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtoesjvmcc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtniaxdiuj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gthorydurb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gtunwerows.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtskpzpnrq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gtkqkosfna.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtsbaqkvir.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gtpzzdvzec.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtxefkuzui.html

TS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtkditimup.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtzraevxzv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtqnyxxwnp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtenczuyde.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gtnwfudbgw.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtxgsgftjq.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtsrbiforb.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gttypujyub.html


<!-- 参考信息 -->