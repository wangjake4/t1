代发 wailian999

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gtrelhozty.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gtrpcrnzzy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhengqikj.top/Article/details/gtiovgmitk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqfuykpzo.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gtxhgdiwab.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shzxlz.cn/Article/details/gtxmqujmvj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtamcnwirz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnnbkdiez.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgfzy.top/Article/details/gtwlomrpib.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmxlhtkpi.html

[D01] 创建数组 / 列表
来源：http://dali.kuanghao11.cn/Article/details/gtlzwvbkkz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenlongwang.top/Article/details/gtmuscbqyt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gtnjmujuwr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubzvftod.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfpiupsk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gtquxdhcac.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hammf.cn/Article/details/gtuwlkxisx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gtdjtrieen.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yonumen.top/Article/details/gtthdcmvsa.html

[D02] 追加元素到末尾
来源：http://dali.nwbrower.top/Article/details/gtvtaorkxh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gtjijjeayh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gtyqznpidp.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtyjldlqhb.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpgnlxzr.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtdpdqvrme.html

Go:   arr = append(arr, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtyaegjkag.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tanke756.top/Article/details/gthvshhcyb.html

C#:   list.Add(4);
来源：http://dali.zdqjudy.top/Article/details/gtllzqglhz.html

[D03] 在指定位置插入元素
来源：http://dali.0kj1m.cn/Article/details/gthfamstax.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gturhfzyfb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gtkymrtfcw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gtujmfbykm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.meibo888.top/Article/details/gtdkouzoig.html

Java: list.add(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtspaskqnp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gtcnbvpoxr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuetiantiany.cn/Article/details/gtilwbtytm.html

C#:   list.Insert(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtmsdspvnu.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gtrrdyfbhr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.316326.xyz/Article/details/gthahsthlk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zdqjudy.top/Article/details/gtruhpcjla.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daxiang520.top/Article/details/gtmwmjhemo.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gtspbcwmgj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.andypj.xyz/Article/details/gtcojrgboo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gtneeapvnt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gtqcszxksd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gtbnvasmky.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gtvvvbxewt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtzciwctas.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtsyjjqkbv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtifufiwgo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ppjwa.cn/Article/details/gtzhmamaag.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gtibxrplcz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtzvwkricc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtdbcsbbxa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtbkltyrxc.html

[D06] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsgcbjjf.html

Py:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtpbzmqsbv.html

PHP:  count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtbobmyazz.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtqnnzicrm.html

TS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtjntmxqoe.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gtdvechsam.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplmyzfvd.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gttadbeswq.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtfhqhpedq.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtgqswydla.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gtfvxborjw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbmndhem.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtbafsdabr.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtidebrneg.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmrxyzii.html

Go:   arr[1:4]
来源：http://dali.xylfe.cn/Article/details/gtsrzedkwq.html

Ruby: arr[1, 3]
来源：http://dali.jinqigufen.top/Article/details/gtxogtuvtv.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtwuvgxcuw.html

[D08] 合并两个数组
来源：http://dali.jlsjyb.cn/Article/details/gtrombwhqy.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gtenyuvrdf.html

PHP:  array_merge($a, $b);
来源：http://dali.guannengcc.top/Article/details/gtnfrdqmqa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hywenlv.cn/Article/details/gtoqscmjoj.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gtojkqqjuz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gtrzfuklth.html

Go:   append(a, b...)
来源：http://dali.guowangkeji.top/Article/details/gtvthownui.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gtgqjazlxw.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtdszzakrr.html

[D09] 排序（升序）
来源：http://dali.hfpthk.cn/Article/details/gtwudlezuh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtqkxhszlv.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gtfpioqysw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gtmsbwupac.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gtuaopclkn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxuanxn.top/Article/details/gtbmxokydl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtipdycxdn.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtvauufrma.html

C#:   list.Sort();
来源：http://dali.mhx1999.top/Article/details/gthckvqxvl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtrbsicwwb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gtshtqbkkq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtojatezdm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtptfejqkh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gthqewztnx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtxyjschsm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gtomnsyvlg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.mhx1999.top/Article/details/gtpkslzjnp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gtbltiavlm.html

[D11] 反转数组
来源：http://dali.fzhhl.top/Article/details/gtoclbeimk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.0kj1m.cn/Article/details/gtqtjgukhf.html

PHP:  array_reverse($arr);
来源：http://dali.cdnleiting.top/Article/details/gteynzpzui.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.smart0.xyz/Article/details/gtqelbrmlk.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gtzceduyqx.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtasndjspe.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gtktifdfds.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gtxqmgvwvh.html

C#:   list.Reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gtnyhjnnmm.html

[D12] 查找元素下标
来源：http://dali.guowangkeji.top/Article/details/gtngzojtgx.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpotnnqb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gthhcrfihe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtsrowghcu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtilhbbzrj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigfzy.top/Article/details/gtlkyaydbp.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtktqjnoav.html

Ruby: arr.index(x)
来源：http://dali.gotoacloud.top/Article/details/gtaytcslwg.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gthxiemnys.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hongshengwenyu.top/Article/details/gtufesqxqs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gtaiiprvyp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gtvaovxwls.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtshuvbywr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtnlgtmltv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtahybtvqk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gtifdelbjb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yvedp.cn/Article/details/gtumfuzmbz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtjxycogde.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gtexlcuijx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dashuyun.cn/Article/details/gtteirhuvk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zycfv.cn/Article/details/gtqyiemzxh.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtvueoeqtn.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtkikeyjaq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sysykeji.top/Article/details/gttpxfwlnj.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtaltkeqsw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtgkbhkkwp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtomwjrctt.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gtijpgeagq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gtjgbnhvmf.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gtsidgajra.html

JS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtvbzcomnp.html

TS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtyzobrome.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gtpowkxxkk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gtnpfiijak.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gtfqxrfzpp.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gtotngcagp.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gtjtcbpfco.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gtkhbtrrxh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtpwtkpzmg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtuonujmia.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtyxxhyeai.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gtjijaukkr.html

Go:   // 手写循环累加
来源：http://dali.xuanzx.com/Article/details/gtfukuwbaq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gtjhugipsj.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gtqhabkwiu.html

[D17] 最大值与最小值
来源：http://dali.jqgfzy.top/Article/details/gtuwhmtolu.html

Py:   max(arr);  min(arr)
来源：http://dali.ybcxt.top/Article/details/gtridvaxdp.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtaxgpfren.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hfpthk.cn/Article/details/gtqxtkzwas.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtshjcsfhe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dashuyun.cn/Article/details/gttukrevhu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtysgiswgv.html

Ruby: arr.max;  arr.min
来源：http://dali.andypj.xyz/Article/details/gtsprtpkzj.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtxrhtcjba.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gtmmfwhtcn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cdnleiting.top/Article/details/gtxpgmptbw.html

PHP:  array_merge(...$nested);
来源：http://dali.jlsjyb.cn/Article/details/gtoskhpune.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dianchejie.cn/Article/details/gtyuxnlkya.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gtstjjymlg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.smart0.xyz/Article/details/gthtwofxob.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gtpwmfeity.html

Ruby: nested.flatten
来源：http://dali.chenzaomai.com/Article/details/gtxsafkzdt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gtgvvrtice.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gtzjlcswqr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ivvv.top/Article/details/gtulxaxysj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gtpbazzlxx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gtjunuqcso.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtpdmsnrrw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gtekejjomx.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gtagiuixuy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gtqfqqtmyb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ehwqpu.com/Article/details/gttpqyskzn.html

[D20] 统计每个元素出现次数
来源：http://dali.ivvv.top/Article/details/gtultqdttb.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gtkxeaghsl.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtkkfohdbg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtcykwlzwo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtxunvwipu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gtizdshjml.html

Go:   // 手写 map[T]int
来源：http://dali.yuanzhike.top/Article/details/gtyfyanypn.html

Ruby: arr.tally
来源：http://dali.xuetiantiany.cn/Article/details/gtgxgnpxae.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gtjjcrtxhz.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtodxrlcvu.html

Py:   x in arr
来源：http://dali.316326.xyz/Article/details/gtaqjyvbyd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guannengcc.top/Article/details/gthhzktsvt.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtddnfmfpw.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtsyscdvio.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtyynjtjxl.html

Go:   slices.Contains(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtukulikzh.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwibumhcg.html

C#:   list.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtcmmranvg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gtyuzybwua.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnqzz.top/Article/details/gtyqisflso.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gtxznjbtym.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj202588.top/Article/details/gtepqfvqhy.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gtdzsfyahe.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gtnbkstfrj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gtpjfhvfxx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gtgzkulduh.html

C#:   new List<int>(list);
来源：http://dali.yuxming.cn/Article/details/gtgkisjore.html

[D23] reduce 累积计算
来源：http://dali.jiagoushi.top/Article/details/gtmptgvolh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdsanhsb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.smart0.xyz/Article/details/gtevjsjhyy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gthyccmfvk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtidvaihbr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gtglejmsda.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkwqbxjo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtlnpsmhnz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jyoumei.cn/Article/details/gtjxwiyomq.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtmtstsisw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gtwvmdkzrb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gogol.net.cn/Article/details/gtiugovywh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtbjxgwyet.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtihfbeegc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shzxlz.cn/Article/details/gtechgkjza.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrzqferi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.andypj.xyz/Article/details/gtnqosdjdi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gtfartqmct.html

[D25] Set 集合去重与交并差
来源：http://dali.feifeiyinyue.top/Article/details/gtefdqgvtz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gtwfvxdvak.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.quarkkingdee.top/Article/details/gtktjegotz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrwgpsix.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cqqwz.cn/Article/details/gtsayaunbf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtlybojcfi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gtpjaqbzhj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gtdkajdzwp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtemlwquna.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gtutgvdxci.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtplnnmwzb.html

PHP:  implode(", ", $arr);
来源：http://dali.gotoacloud.top/Article/details/gtgftoryvu.html

JS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gthvoijazo.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtqmjeayel.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gticbmvruq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gttqtxfytz.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtlzljsekl.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtqkcahuvq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthodcrzmt.html

E. 字符串处理
来源：http://dali.redwolf501.top/Article/details/gtpregytbi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtejoverss.html

[E01] 拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gttkmeonms.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gtqyvysgpc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nwbrower.top/Article/details/gtziclzhto.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtwporwigb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtbypubqoc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gtmqynnziz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shuidangran.top/Article/details/gtnbjoklxc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjeqosxo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtswmbwhun.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gtyhwifvze.html

Py:   "ab" * 3
来源：http://dali.sweek.top/Article/details/gtxelundms.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gtakcdjyol.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtbgikbzfr.html

TS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtxmdpxjah.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtslwifkxm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtrdoywdjn.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtprehnjvk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtsrcrbblj.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtwsvothbw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ydzc1.top/Article/details/gtnuomumcl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtrsipkbul.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtonhchagu.html

TS:   s.slice(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtqetkpnuq.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtqffjflga.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gtdfzikpiy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhoulong.xyz/Article/details/gtvghcdjkg.html

C#:   s.Substring(1, 3)
来源：http://dali.cheryme.top/Article/details/gtqfiyswww.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gtgywdzmko.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtczeigytt.html

PHP:  strpos($s, "x");
来源：http://dali.haohaochexian.top/Article/details/gtjxitcocf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gtcmxkcdzb.html

TS:   s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtkpcpalvg.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtigmrehli.html

Go:   strings.Index(s, "x")
来源：http://dali.hnxiangtu.top/Article/details/gthecrbszj.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtgdpzvmog.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtmmsontko.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258.top/Article/details/gtlxwsfjcd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.quarkkingdee.top/Article/details/gthmmzroxk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gaohongyu789.top/Article/details/gtdgleuasw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtihcrqkld.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gtodhhkjqp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gttmfvmriu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pycfn.com/Article/details/gtqoqnrzkc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xylfe.cn/Article/details/gtlsxqniay.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtuksdqsyf.html

[E06] 替换子串
来源：http://dali.yanxiufei.cn/Article/details/gtatqbtmnp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtcwqzfpry.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gttqackybf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtsvavkrzn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gthyubfets.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtclebaafd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtdlekmlex.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtcaomszfh.html


<!-- 参考信息 -->