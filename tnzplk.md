代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.cashguo.top/Article/details/gt2zahmpxli.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2vtqeqbpm.html

[D01] 创建数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gt2czojnlnj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.iojbl.cn/Article/details/gt2fckcgfyx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gt2bjsnbokd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangdashe.top/Article/details/gt2drefhpqy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gt2gtjsnvdt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ppjwa.cn/Article/details/gt2ktmaxmgu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gt2avryacdc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258.top/Article/details/gt2puqxrsyv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gt2gminzejm.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gt2fkhjadxn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yongpay.top/Article/details/gt2gytrdacc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gt2vdvjuhiv.html

JS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wswdqonn.html

TS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2fdkdphtl.html

Java: list.add(4);
来源：http://dali.xuanzx.com/Article/details/gt2odyzcnhi.html

Go:   arr = append(arr, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lijycumg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hywenlv.cn/Article/details/gt2icijaidy.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gt2gfuxvtwy.html

[D03] 在指定位置插入元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjqzuykb.html

Py:   arr.insert(0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnknwijt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ehwqpu.com/Article/details/gt2vwkvpnvn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tianlin.xyz/Article/details/gt2faqtzssj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gt2ldsmlenv.html

Java: list.add(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2gtwihxmb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jiagoushi.top/Article/details/gt2xfwhteiz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2szbgdlqw.html

C#:   list.Insert(0, 0);
来源：http://dali.pycfn.com/Article/details/gt2uhssmxuu.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gt2bjoorkjh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gt2clsctstq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gt2hrtqxlob.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dashuyun.cn/Article/details/gt2yncuxobq.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrkvlvzy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gt2yurfmpba.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhongyouzk.top/Article/details/gt2hpaitopc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ybcxt.top/Article/details/gt2sdgshhyd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gt2madhtdnz.html

[D05] 访问与修改元素
来源：http://dali.jinqigufen.top/Article/details/gt2chddgdye.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2rgbkfkba.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gt2kzaszzxn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2nzzurwgc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yonumen.top/Article/details/gt2nbflrvvl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xziqi.cn/Article/details/gt2pblarras.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2hlohvlat.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2hrpravwz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gt2aeiyqpdj.html

[D06] 数组长度
来源：http://dali.yuxming.cn/Article/details/gt2xdhawaoa.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2vfmillcf.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfhxxmuw.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gt2scrbvbek.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2gymdyiyh.html

Java: list.size();
来源：http://dali.tanke756.top/Article/details/gt2iysyeoqy.html

Go:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gt2uhfkuwva.html

Ruby: arr.length; arr.size
来源：http://dali.aibaodan.cn/Article/details/gt2actdvczm.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gt2mmpfjwzj.html

[D07] 切片 / 取子数组
来源：http://dali.shuidangran.top/Article/details/gt2veovklch.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gt2jnyakgui.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tianlin.xyz/Article/details/gt2higitweh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2vnheupfz.html

TS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2agrorsss.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gt2gcvjricj.html

Go:   arr[1:4]
来源：http://dali.xinyue.icu/Article/details/gt2mjchuvgj.html

Ruby: arr[1, 3]
来源：http://dali.tian-w.cn/Article/details/gt2bkeqmbgm.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2nscxbbov.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gt2giksdesc.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gt2aibekodn.html

PHP:  array_merge($a, $b);
来源：http://dali.shuidangran.top/Article/details/gt2cljzfmlm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gt2wizoovlu.html

TS:   [...a, ...b];
来源：http://dali.bjfxy.top/Article/details/gt2fcfamaew.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2rcdpbaye.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gt2rgacwmyr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gt2fughdadf.html

C#:   a.Concat(b).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2hybowfyq.html

[D09] 排序（升序）
来源：http://dali.sysykeji.top/Article/details/gt2uktnehpz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gt2avkfdouq.html

PHP:  sort($arr);
来源：http://dali.daria6918.cn/Article/details/gt2rlqhfale.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nwbrower.top/Article/details/gt2nmckzjfd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guannengcc.top/Article/details/gt2fmfibtdd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jzyzvudw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gt2quzlmsjk.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gt2prsuswlo.html

C#:   list.Sort();
来源：http://dali.ppjwa.cn/Article/details/gt2xsmxdfeu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gzhubu.top/Article/details/gt2nuvmuhit.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gt2clayzudj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gt2fxmpmhai.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gt2fetuzcww.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gt2xedzhqoz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gaohongyu789.top/Article/details/gt2ovuhnrif.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gt2trzfwtih.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gt2esvwwmri.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigfzy.top/Article/details/gt2uyeftusm.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gt2tsmhvqdg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gt2kcixcfma.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gt2cppvgsqa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cheryme.top/Article/details/gt2mjrrmfqx.html

TS:   [...arr].reverse();
来源：http://dali.zhixingplan.top/Article/details/gt2eioljxlk.html

Java: Collections.reverse(list);
来源：http://dali.yongpay.top/Article/details/gt2pfkvewii.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2amsvngud.html

Ruby: arr.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2pjtexgmc.html

C#:   list.Reverse();
来源：http://dali.yanxiufei.cn/Article/details/gt2vxsmxdpz.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gt2blbgyqmw.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2amhnxton.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gt2ombbfhgw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyroiwpy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gt2ervapdgn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gt2gldeaxqe.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2dnyjpkbl.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gt2dmjhcuqj.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gt2shjgonri.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shangyingyoupin.top/Article/details/gt2zejxsytp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnxgbpoj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gt2qlcyytif.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gt2fcajdlox.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2vwwfpavo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gt2luellawl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gt2kdteywwi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gt2rejcvvni.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2fysbyava.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikwcydta.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gt2ratemjmg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ivvv.top/Article/details/gt2ywjdxixa.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gt2lqgxltez.html

TS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gt2rrsoqvne.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2jenynclg.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gt2kzrlpvhc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.bjfxy.top/Article/details/gt2lupspenx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2tgiikqda.html

[D15] 去重
来源：http://dali.shuidangran.top/Article/details/gt2fnogddyt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gt2dfgnklcj.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wircvgqp.html

JS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2bproooju.html

TS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gt2etddwdbo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gt2lccginig.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gt2gisilbaz.html

Ruby: arr.uniq
来源：http://dali.yj20258.top/Article/details/gt2szycgfjv.html

C#:   list.Distinct().ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2kelaotpu.html

[D16] 求和与平均值
来源：http://dali.hnqzz.top/Article/details/gt2krwlkyrn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2asmouprc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gt2ywjwzkch.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2qafyyckj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofdajodr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhengqikj.top/Article/details/gt2woqxsqna.html

Go:   // 手写循环累加
来源：http://dali.svipenyu.cn/Article/details/gt2vggnmtnd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmygspqk.html

C#:   list.Sum();  list.Average()
来源：http://dali.tian-w.cn/Article/details/gt2zwnziszl.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gt2dpqsxngd.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gt2cpnlleon.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2ajmrrjdu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gt2cdbpuaxp.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gt2rdnqqinb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.snrcjt.cn/Article/details/gt2sopheewf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2daopkswu.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gt2vihpzhxl.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gt2lmhhxqyf.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gt2eucyfbhr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangdashe.top/Article/details/gt2eopyafdu.html

PHP:  array_merge(...$nested);
来源：http://dali.yongpay.top/Article/details/gt2rfbvonfb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eppetwzw.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gt2krugrblc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gt2hemtjnjn.html

Go:   // 手写双层循环
来源：http://dali.snrcjt.cn/Article/details/gt2cnoddtji.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gt2elkyfezk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tanke756.top/Article/details/gt2vxflwphr.html

[D19] 按字段分组
来源：http://dali.yj20258888.top/Article/details/gt2tuziwudm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.birdmap.top/Article/details/gt2xoznqvjg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gt2qukftmze.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gt2wxebxfhb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gt2gbqoknay.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gt2jeqsxcbx.html

Go:   // 手写 map[string][]T
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzvscziy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gt2fefyajwt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gt2qaeqpvlc.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2paxedxmo.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2evkzlxuk.html

PHP:  array_count_values($arr);
来源：http://dali.ydzc1.top/Article/details/gt2vrppcdwm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gt2znhacopr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gt2krhbvoqs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gt2fvbkqchw.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gt2suqymjfu.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gt2cxlnrimo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gt2vhzntsxk.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gt2rsyocjzv.html

Py:   x in arr
来源：http://dali.shuidangran.top/Article/details/gt2uxoplcwa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gt2peliczun.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygevakbq.html

TS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gt2yibdnmlg.html

Java: list.contains(x)
来源：http://dali.cqqwz.cn/Article/details/gt2vxqssqpc.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2msdqitpv.html

Ruby: arr.include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2ikvexkuw.html

C#:   list.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yyiqtksq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ivvv.top/Article/details/gt2gnvphizm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2kifpobxi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gt2nxpikqpw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gt2wuvclzlb.html

TS:   [...arr];
来源：http://dali.zhiwuduotai.top/Article/details/gt2wllfcjgb.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2iimnnmsf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.smart0.xyz/Article/details/gt2rhjhtdaz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yvedp.cn/Article/details/gt2jhvglnov.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gt2onjgftvw.html

[D23] reduce 累积计算
来源：http://dali.gotoacloud.top/Article/details/gt2lxcdorwq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.meibo888.top/Article/details/gt2uwubctys.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gt2cxokxsgp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2btvyphbv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2jnkqkvhm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gt2ynflbeuv.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gt2sshpjbuo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hysaishi.cn/Article/details/gt2hjbppghy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gt2wwvbkvqf.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258888.top/Article/details/gt2asbmabcq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2naqyhbqt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tmfgmnjh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sweek.top/Article/details/gt2qrybcdxb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2mctonpgm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gt2qfxkajim.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.c1oappe.top/Article/details/gt2awojbebf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gt2abjytphg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gt2enetdwey.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gt2rbkzdgvm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sufxvd.cn/Article/details/gt2emrktqaq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.meibo888.top/Article/details/gt2jfellgxr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2krggfypq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.haohaochexian.top/Article/details/gt2quxsccqo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gt2eewudjje.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigufen.top/Article/details/gt2dhzhiyyk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2tiwlohql.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yvedp.cn/Article/details/gt2bkgsydld.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2qonptiqc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gt2uzskhnqp.html

PHP:  implode(", ", $arr);
来源：http://dali.cashguo.top/Article/details/gt2jailirdt.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2dxnriqky.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhglufua.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gt2dkzrvyiv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gt2kgdejeiw.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrvzcdxr.html

C#:   string.Join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gt2ttncuupc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2cytdhizo.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gt2nljqnfsf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2wuxavyqc.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2eyoppohq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajysxacz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gt2cgpctnzh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gt2kngndpzx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2guyawhfx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.snrcjt.cn/Article/details/gt2kahpmild.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2paeyiorx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gffvmtdm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2wmtryrgs.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gt2jiufzoah.html

Py:   "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gt2xzmwivzw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nwbrower.top/Article/details/gt2pbeqckhe.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2mlkadajb.html

TS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gt2zskezuba.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gt2pwoypnxg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2bfygvwiv.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gt2pcrvgsnp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdyeunbw.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gt2mmejnwqr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzemoyir.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tffvnslr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2tssfojqj.html

TS:   s.slice(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gt2lharyyix.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2lrlevvhp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fengsongda.top/Article/details/gt2bbrllmqr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gt2lnzwltrr.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rejonhkt.html

[E04] 查找子串位置
来源：http://dali.gotoacloud.top/Article/details/gt2cjjcmydy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.c1oappe.top/Article/details/gt2ujtdssvo.html

PHP:  strpos($s, "x");
来源：http://dali.shuidangran.top/Article/details/gt2dcsxvcyw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gt2wqdopvet.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gt2rjjkbzfs.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gt2keanrwqe.html

Go:   strings.Index(s, "x")
来源：http://dali.fengsongda.top/Article/details/gt2rtryiqqq.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gt2heukqaru.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2pxancnqi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gt2tilezctv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gt2bzgrdagq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gt2crxjzppf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2wllxmcnh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gt2yuxkgqkb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2usqowqin.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guowangkeji.top/Article/details/gt2sowqanfk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2aciwtpyn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.havefunace.top/Article/details/gt2yiwsghlt.html

[E06] 替换子串
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdscqmor.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gt2juyqougb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2qosjxlaa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2serffyvc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2iblhlbmy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2nfrqiehs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2jhsdmsfe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2dczwkapw.html

C#:   s.Replace("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2hwkfyezs.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gt2pelximyf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gt2cxvbjils.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2dlpehdpb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gt2edcouzfz.html

TS:   s.split(",")
来源：http://dali.guannengcc.top/Article/details/gt2fdhhiwwi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gt2bjlcwhbq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gt2copoyjyw.html


<!-- 参考信息 -->