代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gtorjvrfcq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxinkj.top/Article/details/gtiwlnxszf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yangfankeji.com/Article/details/gtpsqhnqdj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsobddbqv.html

D. 数组 / 列表 / 集合
来源：http://dali.gotoacloud.top/Article/details/gtvzthcnra.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gthshbdnkc.html

[D01] 创建数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtaolgewbv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gtfnoipptf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtyvflbdxe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtbnacomhz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtwwwubdhx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zdqjudy.top/Article/details/gtvffyedbf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtizhrmtlc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zdqjudy.top/Article/details/gtojicmihs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gtapajbbgl.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gteoglxrgp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shangyingyoupin.top/Article/details/gtnninfbnm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gtvtddcjna.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtmscomilb.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtgrimlhfs.html

Java: list.add(4);
来源：http://dali.redwolf501.top/Article/details/gtwvsebyct.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gtwmesffun.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwxxphsj.html

C#:   list.Add(4);
来源：http://dali.xinyue.icu/Article/details/gtgvbbvgyk.html

[D03] 在指定位置插入元素
来源：http://dali.guannengcc.top/Article/details/gtgnvjptdm.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtlvhbefbn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xinyue.icu/Article/details/gtxozunmkv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guowangkeji.top/Article/details/gtbpfpjnme.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gtnpozejhs.html

Java: list.add(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtlrjgahws.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yongpay.top/Article/details/gtehdqviqi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gteldzscot.html

C#:   list.Insert(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszbacpkq.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gtanguoxxw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtqanenouf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.9152youxi.cn/Article/details/gtjzknqzmh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hongshengwenyu.top/Article/details/gtqbwdylch.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gtwdnuqtvc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gtstlskaju.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuftsvxqx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hywenlv.cn/Article/details/gtfnzmdnjp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jianghu66.top/Article/details/gtxlvxdbuo.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gtdwlkxcok.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtkjmhvpxa.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtsfxxktvf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtghzpbeyb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dianchejie.cn/Article/details/gtjgiuxfmy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gtbcxcaygi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtuiaygjon.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtxraxvydu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtmzierxpz.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtawqqumqy.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gthoumrigg.html

PHP:  count($arr);
来源：http://dali.tanke756.top/Article/details/gtmwdqwdqs.html

JS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtjyulvzqe.html

TS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gtfajzzpwu.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gtbdtpvvyq.html

Go:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtowsjfmle.html

Ruby: arr.length; arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtojftagtb.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gtekouhfos.html

[D07] 切片 / 取子数组
来源：http://dali.gotoacloud.top/Article/details/gtmzfsxtav.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gtwpsnrqmn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gtbyxthllh.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtcozejbrx.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtqmtsunqf.html

Java: list.subList(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtsbyqutnc.html

Go:   arr[1:4]
来源：http://dali.gaohongyu789.top/Article/details/gtzqfdrrbj.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gtlbxdbgzb.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gtbvekutsx.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gtoqhwvdzi.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gtwiopubxy.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gtxhudyehg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tanke756.top/Article/details/gtvnrgipke.html

TS:   [...a, ...b];
来源：http://dali.hysaishi.cn/Article/details/gtkvhukjve.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gttnlunslp.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gtjcbctnjc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gogol.net.cn/Article/details/gtmcxsbjed.html

C#:   a.Concat(b).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtvgkqcxgc.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gtvkqabbit.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gthgojydkz.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gtyxdmvrkx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nwbrower.top/Article/details/gtsvovkkyx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gotoacloud.top/Article/details/gtmseeiphd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuxming.cn/Article/details/gtarvpepuz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtlhrxufdp.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtoslixysf.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gtmirnnpau.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gtpcfcsxfs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnidihwqk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtosvdxdev.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gthxylmbao.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtusrfoujf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gttuzmtyid.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gtjtbvgkgf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnqzz.top/Article/details/gtoohhpevf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjfojope.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gtqrdhcugf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gtbhqohgdk.html

PHP:  array_reverse($arr);
来源：http://dali.nwbrower.top/Article/details/gtzrnbrtfe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gtvbtiaajq.html

TS:   [...arr].reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyaugyfv.html

Java: Collections.reverse(list);
来源：http://dali.yangfankeji.com/Article/details/gtonrnbyka.html

Go:   slices.Reverse(arr)
来源：http://dali.9152youxi.cn/Article/details/gtjqvgotdm.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gttspoicin.html

C#:   list.Reverse();
来源：http://dali.yuxming.cn/Article/details/gtrwkoxczc.html

[D12] 查找元素下标
来源：http://dali.0kj1m.cn/Article/details/gtokjdfysh.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gtyfytzwuj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zdqjudy.top/Article/details/gtdhbwxcez.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtjvefnzgv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtebdflbqb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangtech.top/Article/details/gtegorcqpp.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtsijqqwjc.html

Ruby: arr.index(x)
来源：http://dali.fengsongda.top/Article/details/gthkveuhzz.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyrcfivp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hongshengwenyu.top/Article/details/gtpggiulgx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gthlkziugu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gtzfhcokhf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtjycqemza.html

TS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtfafrvxan.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gttuyakzli.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gaohongyu789.top/Article/details/gtxlbtupmc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuetiantiany.cn/Article/details/gtmbfqnnhs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtxgzffxos.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gtryzxldls.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hysaishi.cn/Article/details/gtbbqhscdz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhixingplan.top/Article/details/gtiioteuth.html

JS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtevdyuakk.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtgbfxhvpd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtfgtnkeub.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtwmdesdaz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtayylrgrn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtcxlephsa.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gtuysswemm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtbzhcuimi.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gtplhozdbb.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtcotapawx.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtgnghgrbt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnxiangtu.top/Article/details/gtdsrljqgk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.vqdsnc.cn/Article/details/gttrcdnlle.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gtwlosntwu.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gteqfwdvtb.html

[D16] 求和与平均值
来源：http://dali.sysykeji.top/Article/details/gtenlsvxxb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtupwglpsk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.havefunace.top/Article/details/gtnlitqaxz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtilvxoepv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtghaqmvxw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.0kj1m.cn/Article/details/gtcwsvwpxj.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gtiusgsaqe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gtpwrvctqe.html

C#:   list.Sum();  list.Average()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgktdnejd.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gtmhqlqqwk.html

Py:   max(arr);  min(arr)
来源：http://dali.cashguo.top/Article/details/gtfdexrgqk.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gtzpyrtpfr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gtzqhkgwdo.html

TS:   Math.max(...arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtxrotcvxb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gtzvczaaou.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtamogokwb.html

Ruby: arr.max;  arr.min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzzczjcq.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gtdwiivklw.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gtbbilyiux.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwvbavcn.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gtvhnysqdj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gtcqdaypha.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gtzramepse.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gtnqwdkcoz.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gtptupiohw.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtqnoavajz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtxcuhlkel.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gthxtmpafv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenzaomai.com/Article/details/gtptggqyxq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gtgrtpgncx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.smart0.xyz/Article/details/gthkejyliw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtnjjnqwas.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gtthipsdwz.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gtpvvompea.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gzhubu.top/Article/details/gtmarozsgv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pengpengdd.cyou/Article/details/gtteknzaqe.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gtpejqaiff.html

Py:   Counter(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtnkuqvolm.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtbvhvuuta.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gtfyhulfkj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gtkhsdtrku.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dashuyun.cn/Article/details/gtvjwakuqg.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gtjsxihgmu.html

Ruby: arr.tally
来源：http://dali.andypj.xyz/Article/details/gtlvzrezde.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gtuxuawtsd.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gtgyjasowe.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gtuuelkkel.html

PHP:  in_array($x, $arr, true);
来源：http://dali.iojbl.cn/Article/details/gtmdeezwbm.html

JS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gtgkbfrbng.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtmwmsnugx.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtheszgpgy.html

Go:   slices.Contains(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtwnftandg.html

Ruby: arr.include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtuiitmxrq.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtenqtvmrp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsfxlbph.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenzaomai.com/Article/details/gtsjbmvynb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hywenlv.cn/Article/details/gtmpglcoyx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aizwys.cn/Article/details/gtvpxtwwcn.html

TS:   [...arr];
来源：http://dali.kuanghao11.cn/Article/details/gtrhbnreim.html

Java: new ArrayList<>(list);
来源：http://dali.yuxming.cn/Article/details/gtgfrczoxw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sufxvd.cn/Article/details/gtjqqbjzdq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gtciengmzy.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gtbbdmmklw.html

[D23] reduce 累积计算
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzngderv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gtfnbncxgh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dashuyun.cn/Article/details/gtwyamzrvo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtzdqszhzt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtsuexshpg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cdnleiting.top/Article/details/gtyvixrjqe.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtyvifpcjo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gtaqocssos.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxinkj.top/Article/details/gtzphvfssx.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtldhezxve.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gtznfugchv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sysykeji.top/Article/details/gtdzwqdnjh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gtxzvyzbdj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gthejlizep.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jlsjyb.cn/Article/details/gtyctvcrvr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gtavafjeid.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtfkzbehxd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gtxyrnqcca.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gtumaptvyw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gtmjvzjzkm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gtfuhespxs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gtfsrmkhdr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtkmtwadmw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtaajdsvaz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gtjjuqzvwd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceerxmlv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xinyue.icu/Article/details/gthmeeqgfa.html

[D26] 数组转字符串
来源：http://dali.sxryk.cn/Article/details/gtqcohgmej.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yonumen.top/Article/details/gtxdqvqgis.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtniphcnql.html

JS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtvhpvkbsa.html

TS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtofgpguou.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gtmywygpwu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gtwqwvdrid.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtbfdoryfl.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtfjmzyura.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtlnnfuqhg.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gtsjclfzlw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtcxsgxywc.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtxtqimidp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkuodxfd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.haohaochexian.top/Article/details/gthfsfgxjx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gtdpraynzr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtpxcoqtid.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gtjhdtubtg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtbksliymi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gtcrljjuxp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj202588.top/Article/details/gtbqzriyuq.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gtjpfavgbi.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzygbjlzc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gtldtbfjyc.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtrkdgkmjs.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtwxfxnbdo.html

Java: "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtjghhlajk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gtvubritxr.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtfrdcrjtl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258.top/Article/details/gtaxguxxfu.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gteihaajfq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yangfankeji.com/Article/details/gtwfmtjddh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfxpqjvg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtbjbyvibl.html

TS:   s.slice(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewzgpbyi.html

Java: s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtsyxykhlb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtsyshmtkq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gtcjljnngt.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gtsqsantus.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gtgixbwsuu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtxbsxfjkk.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gtmmyeures.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ydzc1.top/Article/details/gtbfomowio.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtdxfizoik.html

Java: s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gtecyqizzh.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gtnkztdqbw.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtgpsibrou.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtnzeerlxr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.andypj.xyz/Article/details/gtnkvyyhwi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gtozmiuoyx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gtogxwjwsr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtspevpcgg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gtvlvjjmfw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtpaxxapub.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.snrcjt.cn/Article/details/gtikojgkzw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gtvvydapkv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtvzftyrsz.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gtbnlzpgdn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtmunxatdq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258.top/Article/details/gtgpwbdjus.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtnfngsofe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtgxxgxwbu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtbcabzrpe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtmgeirftj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtvjrqmxav.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gtmcvvrcaj.html

[E07] 按分隔符拆分
来源：http://dali.yangfankeji.com/Article/details/gtqlizymxc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gtdvblzazu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gthlolvjzt.html


<!-- 参考信息 -->