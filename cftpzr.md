代发 wailian999

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gtixwjnkvs.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gthvpgiqay.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gtnnpnvjzh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtrirkmvnx.html

PHP:  // 无重载
来源：http://dali.kuanghao11.cn/Article/details/gtndzwlkkp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gtpsvprhge.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gtdeinzhzz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.svipenyu.cn/Article/details/gtsyejkesu.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gtqkcqjzud.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxinkj.top/Article/details/gtjevqtnuo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtbbszefvq.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlvcehnrw.html

D. 数组 / 列表 / 集合
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmhnafux.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmcfpnvih.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gtrpjqncbs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gtetzymmre.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtazjnwizq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtoiykiyve.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xinyue.icu/Article/details/gtvuesvmqb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xinyue.icu/Article/details/gtumwucprd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gtbnmyrwkp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangdashe.top/Article/details/gtvsokiraz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtslrrmtmb.html

[D02] 追加元素到末尾
来源：http://dali.hnqzz.top/Article/details/gtlhbfdljt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hysaishi.cn/Article/details/gtqubibvat.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gtywuzlgbj.html

JS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gtlhskwhqk.html

TS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtzyjmppft.html

Java: list.add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtkpjyixoq.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gthpijmggg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tanke756.top/Article/details/gtpbxvmshl.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gtxkztmbuc.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangtech.top/Article/details/gttvlrtici.html

Py:   arr.insert(0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtiyccgien.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gtndsgyqsz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gtmjzuiolb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuxming.cn/Article/details/gtgeuljdpj.html

Java: list.add(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtwdlwttig.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yvedp.cn/Article/details/gtfsqebyhl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jyoumei.cn/Article/details/gtzznpbmnl.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gtrfkrffpz.html

[D04] 删除元素
来源：http://dali.ybcxt.top/Article/details/gtetkflzrq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnqzz.top/Article/details/gtrujcwsnd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtapdpwvge.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gtvfhfjobr.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gtwzphyzkw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gtayrjilnc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gtvmghrtbo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ehwqpu.com/Article/details/gtcmtrlmxm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.mhx1999.top/Article/details/gtuszzqwze.html

[D05] 访问与修改元素
来源：http://dali.jqgufenzy.top/Article/details/gtdycuttrc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtmfmnkubx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtfytdouzk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtlwuluxkl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuxming.cn/Article/details/gtxeoaeopf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jyoumei.cn/Article/details/gtiwtxigqg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtqohemivt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtvconufyt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtytmtfftp.html

[D06] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtrhoisfwk.html

Py:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtxstcuteg.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gthbrmvxqy.html

JS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtcpxdkxyp.html

TS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gteeagixhj.html

Java: list.size();
来源：http://dali.0kj1m.cn/Article/details/gtddpbvbpj.html

Go:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtlgjusaao.html

Ruby: arr.length; arr.size
来源：http://dali.bjfxy.top/Article/details/gtsukehhts.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhpalukk.html

[D07] 切片 / 取子数组
来源：http://dali.kuanghao11.cn/Article/details/gtgbkvkxxy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenjidiqi.icu/Article/details/gtghlhwusg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gtjnlhlmhp.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtrnevvjsd.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtvsvvrmsn.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtspcezccy.html

Go:   arr[1:4]
来源：http://dali.yangfankeji.com/Article/details/gtjmakfyqo.html

Ruby: arr[1, 3]
来源：http://dali.xziqi.cn/Article/details/gttttoojce.html

C#:   list.GetRange(1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtwuhqbitw.html

[D08] 合并两个数组
来源：http://dali.sufxvd.cn/Article/details/gtcapwibkn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gtkiohscsj.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaotymgzs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gtbbtngrte.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gtygwenpox.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gtmuumdmce.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gtipqefqud.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gtcjcrqsnj.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gtxjbrnxqf.html

[D09] 排序（升序）
来源：http://dali.shuidangran.top/Article/details/gtizfolmoi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtnwazqezx.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gtksqdbkaz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jiagoushi.top/Article/details/gtnqaoshot.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtfukubudx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxwiuypd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtanwknbtn.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gtyqckntkq.html

C#:   list.Sort();
来源：http://dali.sxryk.cn/Article/details/gtlvuvwzyl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gtohxuzsrx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.smart0.xyz/Article/details/gtuishgyut.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtvtdafrgd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gtghgizneu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtichkarjw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gtkisczjlc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cdnleiting.top/Article/details/gtaaoqkmjw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pengpengdd.cyou/Article/details/gtngwanjpq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.c1oappe.top/Article/details/gtfeednsfx.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmycyqobb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.kuanghao11.cn/Article/details/gtfihydtuk.html

PHP:  array_reverse($arr);
来源：http://dali.mhx1999.top/Article/details/gtdegkkyid.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gtwbiwneho.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gtddzyozkr.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuayvfwe.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gthaskcbwr.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpnpmvrh.html

C#:   list.Reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtebdqnjoe.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gtatuhgplw.html

Py:   arr.index(x);  x in arr
来源：http://dali.tanke756.top/Article/details/gtwaisvzmv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.andypj.xyz/Article/details/gtuepmvcvc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtynfzhbko.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gthjssulij.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxinkj.top/Article/details/gtbypqhwcj.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtcbiobdji.html

Ruby: arr.index(x)
来源：http://dali.quarkkingdee.top/Article/details/gtsbknufje.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gtvgehdugo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gttevvucir.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.snrcjt.cn/Article/details/gtpmssitmd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtoozgjurs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtwaybdybe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtkgqoiamx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuiqadevn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shuidangran.top/Article/details/gtemicoqiw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgprwwigq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtirbzqqbg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guannengcc.top/Article/details/gtqkhpzdpw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gtdsekuipt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gtgtphyger.html

JS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gtkpzjeycm.html

TS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gtkdrmcthe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtkyubawav.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtemymmecf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtkczncoub.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtwzrkuwhm.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gtpixlizzi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gtzrdstpht.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gtipkhyrnd.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtynfkwhph.html

TS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtdkcswunm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gtivcimivf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwqoxnxw.html

Ruby: arr.uniq
来源：http://dali.gzhubu.top/Article/details/gtrpiuskgm.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gtiwdmevob.html

[D16] 求和与平均值
来源：http://dali.zhoulong.xyz/Article/details/gtubohfbaj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtewrghuak.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.316326.xyz/Article/details/gtddvvbkjp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtydefzlfw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtyovtjtae.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.iojbl.cn/Article/details/gtxymifeyn.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtetggjnha.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gttluumaai.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuanzhike.top/Article/details/gtxfvqzcef.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gtzrvpwggs.html

Py:   max(arr);  min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtipukedco.html

PHP:  max($arr);  min($arr);
来源：http://dali.cheryme.top/Article/details/gtveddxjsv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gtdajvsmrr.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gtycfklndn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtsqipklpw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtcbxiwvvr.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gtuwzwpmgl.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gtxrzxibkr.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gtvziubkqr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhtvbwxg.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gtuchnyckk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fzhhl.top/Article/details/gtiayzxbij.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gtgsmwhnsa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gtozynnuwv.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxujhwci.html

Ruby: nested.flatten
来源：http://dali.feifeiyinyue.top/Article/details/gtpeuhkaeq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yongpay.top/Article/details/gtvdtcltbq.html

[D19] 按字段分组
来源：http://dali.dashuyun.cn/Article/details/gtqxkngful.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxinkj.top/Article/details/gtykubvoul.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.vqdsnc.cn/Article/details/gtvcuyxgee.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cheryme.top/Article/details/gtbftlszmq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtxjvjpxcn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gtleefgxoe.html

Go:   // 手写 map[string][]T
来源：http://dali.hnqzz.top/Article/details/gtdoknwlii.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtcdqgvomd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtgosqjwhc.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gtrquukfnr.html

Py:   Counter(arr)
来源：http://dali.birdmap.top/Article/details/gtlxgtwkxl.html

PHP:  array_count_values($arr);
来源：http://dali.ppjwa.cn/Article/details/gtdkcmsqgt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gthfptqtte.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtjapmwdxb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dianchejie.cn/Article/details/gthlarjcln.html

Go:   // 手写 map[T]int
来源：http://dali.nanxuanxn.top/Article/details/gttikbzxhm.html

Ruby: arr.tally
来源：http://dali.yanxiufei.cn/Article/details/gtprfolvuc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gtfsgdqssa.html

[D21] 判断是否包含某元素
来源：http://dali.0kj1m.cn/Article/details/gtjqcswjam.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gtkilniwmi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ybcxt.top/Article/details/gtnvuqtkrn.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtvhcgyinx.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtbhcuiszq.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gtmjeanbor.html

Go:   slices.Contains(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtdgprhzyu.html

Ruby: arr.include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtvcfulxen.html

C#:   list.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gteuuuiruf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gtvqefzuzn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gtclkvjgwa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gtrrnsxnyy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gtfmhdgfej.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gtaeqqkwem.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gtlerfhquw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gtbprciqet.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gtttzqdtfb.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gtijmgmffk.html

[D23] reduce 累积计算
来源：http://dali.wangshuangyany.cn/Article/details/gthgnobcex.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gtzmalvjum.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gtupjocuat.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtucvipzsb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtdllseewh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gtnnrcofrw.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtlmrftskx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gtnsljbjzf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gtzbywusov.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gtphvfmfrg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gtwbwaxtxm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtjdliczfs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258.top/Article/details/gtdebydjyp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtnngvdfyf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gtmlqyjspf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258888.top/Article/details/gtddlnwzen.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gtbcawluxm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hongshengwenyu.top/Article/details/gtffhhvwhl.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gtbplkrhvs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.birdmap.top/Article/details/gtnlmpbgbp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tian-w.cn/Article/details/gtsmwkqzpx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtrkyorled.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gtldgovgzs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gtslbkadsp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyeahirp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gtslqhaqug.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtmkdoqkht.html

[D26] 数组转字符串
来源：http://dali.sufxvd.cn/Article/details/gtbmpfapvq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gtkyvaslnx.html

PHP:  implode(", ", $arr);
来源：http://dali.daxiang520.top/Article/details/gtcxfsdaeh.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gttwtopbds.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtxhsrqcvn.html

Java: String.join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gtaiswnbvm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yonumen.top/Article/details/gtxhingyep.html

Ruby: arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtwtsywciy.html

C#:   string.Join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gtnxgvnaef.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtyazajkap.html

E. 字符串处理
来源：http://dali.dashuyun.cn/Article/details/gtdibetrqd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtaxjbgmil.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtvyolgoly.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigfzy.top/Article/details/gteuqsvysu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtnhivrrts.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtsvdhjmdd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtxzlmkkby.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gthpdwgudx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hywenlv.cn/Article/details/gtmzlwtbjk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pengpengdd.cyou/Article/details/gtsalbjzlc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwourezip.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gtqxijxwsf.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtbzywcwsl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gtxnuixdkm.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gttnbalkit.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnjwaruz.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtzxfnsknx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gtsytpotqm.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtwxrvjifv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gtfwmuomrj.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtjrnnfoip.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.vqdsnc.cn/Article/details/gtciovnawx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtzeryvhah.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtzrrucrxl.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtdcwscpfn.html

Java: s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gtnfojpgop.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmhstjts.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtfudhldjf.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gtgpyerpni.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gtyqzybwwa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtvqpwucbm.html

PHP:  strpos($s, "x");
来源：http://dali.c1oappe.top/Article/details/gtisvleqrk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuanzx.com/Article/details/gtjlwlqtgl.html

TS:   s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtjjfszfag.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtrpcpebae.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gtygnlgqzc.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtwftpmhvr.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtjniukiup.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gtoqmkqneb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtrhjuuubv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xylfe.cn/Article/details/gtefrxksqh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtdeumfcak.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shzxlz.cn/Article/details/gtsrulrsol.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtcdidruhj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gtptiibsdl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxuanxn.top/Article/details/gtmlzfbsmh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtuyuoodqm.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gtkxwgfrcp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtevnalgoc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aizwys.cn/Article/details/gtdtintzkm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtapcwazhc.html


<!-- 参考信息 -->