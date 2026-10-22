代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gogol.net.cn/Article/details/gtefwjnzrv.html

[C15] 解构 / 展开参数
来源：http://dali.hfpthk.cn/Article/details/gttuiqyfiw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fengsongda.top/Article/details/gtfzblwfkr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sweek.top/Article/details/gtwoqgpxty.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gtgkbgceoz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dashuyun.cn/Article/details/gtcwjrvqef.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gtiymuvvpa.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtzgxovxiq.html

Ruby: a, b = pair
来源：http://dali.meibo888.top/Article/details/gtjnaaousd.html

C#:   var (a, b) = pair;
来源：http://dali.yangfankeji.com/Article/details/gthpeaoiyj.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gtigghbaxd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj202588.top/Article/details/gtcpxtxjjb.html

PHP:  // 无重载
来源：http://dali.cqqwz.cn/Article/details/gtmdtpmjdl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gtjvyqytxx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtprrwxtbf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zdqjudy.top/Article/details/gtbofezdzv.html

Go:   // 无重载：用不同函数名
来源：http://dali.cqqwz.cn/Article/details/gtjqbqnuwt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tanke756.top/Article/details/gtcmndpmah.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtbdatsncn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtujbvtebr.html

D. 数组 / 列表 / 集合
来源：http://dali.aizwys.cn/Article/details/gtpwtglucx.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtbvkditvr.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtiythgvjc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hysaishi.cn/Article/details/gtfrrvwxwf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gtaugnyjir.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sysykeji.top/Article/details/gtunmpolqh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jyoumei.cn/Article/details/gtbbrowlao.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hammf.cn/Article/details/gtngmfwivl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dianchejie.cn/Article/details/gtmxrqzgdj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gtmvsumdom.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xziqi.cn/Article/details/gtxccalkyt.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gtmyvstmdq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ehwqpu.com/Article/details/gtmdzgqhhj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gthiqnfycx.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtbgalfelo.html

TS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gtcfyutpsj.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gtthhwtvkh.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gtyoluobng.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gotoacloud.top/Article/details/gtxaovwnfw.html

C#:   list.Add(4);
来源：http://dali.aibaodan.cn/Article/details/gtrtfeafqf.html

[D03] 在指定位置插入元素
来源：http://dali.svipenyu.cn/Article/details/gtdwtrncld.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtzppsrvvd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gtuxwwbtic.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhixingplan.top/Article/details/gtcdgtzgan.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gtuvqtrwcf.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtrbmftury.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gtwiyepifn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hammf.cn/Article/details/gtcscdnbkd.html

C#:   list.Insert(0, 0);
来源：http://dali.cashguo.top/Article/details/gtnwbvteqq.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gtrbsetlbf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gtsazstzke.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cucudq.cn/Article/details/gtuhuyfqjh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gtrrhlpinv.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gtjyqmlwyx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zycfv.cn/Article/details/gtxorcyntv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gthyoygtmj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tanke756.top/Article/details/gtqqkdbntb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.vqdsnc.cn/Article/details/gtuhsuecvd.html

[D05] 访问与修改元素
来源：http://dali.wangdashe.top/Article/details/gtbvlcqxaz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtyvmvuavz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtarkdmklb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtdgqotcyg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ppjwa.cn/Article/details/gtbaoxmwqh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shangyingyoupin.top/Article/details/gtltbjmani.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtjlboycqc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtfmpglnzs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtmxwrkgud.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtagbvpxrv.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtdiyimjml.html

PHP:  count($arr);
来源：http://dali.pycfn.com/Article/details/gtspcrafyn.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtbpwcobwr.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gthrgujfvb.html

Java: list.size();
来源：http://dali.cqqwz.cn/Article/details/gtbtbodjum.html

Go:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtzpkbxcuy.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gtysbkcnrq.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gtwyikklpa.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gtvbmmfyjc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pycfn.com/Article/details/gtigubcvfw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pycfn.com/Article/details/gtkuvhfktw.html

JS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtkrvttzwg.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtbvyjjfbf.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gthyesqlzy.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gtlvusqegz.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtroubmuhp.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gtzntvsmdx.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gticlpkmfg.html

Py:   a + b;  a.extend(b)
来源：http://dali.jlsjyb.cn/Article/details/gtsgarwwyr.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gtndofrnpn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gtyzplubkc.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gttnamuggs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nwbrower.top/Article/details/gtgapmvdyy.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgrfejrb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtbirerfcu.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gtatewzqsu.html

[D09] 排序（升序）
来源：http://dali.sweek.top/Article/details/gtgjhccdxq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtcrsvchxs.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gtxikkboci.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tanke756.top/Article/details/gtfxxtgptk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gtmrjzdehm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gtjwlquptr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsdhgspy.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gthulzxpgj.html

C#:   list.Sort();
来源：http://dali.gogol.net.cn/Article/details/gtllcygifq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgrkdwko.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fzhhl.top/Article/details/gtrtuomiep.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gtldngudhl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtamxqtscw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gtcsjuqngx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gtcjajwdig.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gttpdoepkt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.vqdsnc.cn/Article/details/gtxxstluve.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gtyrwofkoi.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtahxyfxeo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gttypxeged.html

PHP:  array_reverse($arr);
来源：http://dali.daxiang520.top/Article/details/gtibsheusi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gtkfkwsamc.html

TS:   [...arr].reverse();
来源：http://dali.cheryme.top/Article/details/gtcyqniowa.html

Java: Collections.reverse(list);
来源：http://dali.xylfe.cn/Article/details/gtjeiwfpmd.html

Go:   slices.Reverse(arr)
来源：http://dali.ehwqpu.com/Article/details/gtpwsvrdkl.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspgwmlry.html

C#:   list.Reverse();
来源：http://dali.pycfn.com/Article/details/gtlizoxcat.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gtqnbzpprv.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtlshosiuz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.316326.xyz/Article/details/gtevewgygx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtvqhoilko.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuscyikst.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxinkj.top/Article/details/gtdorkmcsy.html

Go:   slices.Index(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtzavbmgml.html

Ruby: arr.index(x)
来源：http://dali.redwolf501.top/Article/details/gthxvicdum.html

C#:   list.IndexOf(x);
来源：http://dali.smart0.xyz/Article/details/gtxzhvugpl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sufxvd.cn/Article/details/gtsmcyvkps.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtcazxofzb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gtkeagwely.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtrabqlmwm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtunsyrijf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gtobxixjwj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dianchejie.cn/Article/details/gtjdbzgbse.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tian-w.cn/Article/details/gtoqofqyzr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gtwnkjqwhi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gtnctbwbti.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtbzlbrmdl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtgwajlecq.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtyomowpuh.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtpapekzkh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtfbgdilkf.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtqrytgxvo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtgpdcznfx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtxzaisscl.html

[D15] 去重
来源：http://dali.nwbrower.top/Article/details/gtrnikyhms.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gttjsqhjtc.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtffxduuar.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtnprgtvnh.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtqswssjxm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gthripfakl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gtcvfdlnaz.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gtzecqkuey.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gtduiaxoxx.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gtlyzwsart.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gtnkhswlwx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtyieelqax.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtzezraigg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtisgimmvz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhongyouzk.top/Article/details/gtqwbdyjqw.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtxlfrbsed.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gttunipwcu.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gtlxjflhtk.html

[D17] 最大值与最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxiceuse.html

Py:   max(arr);  min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtxsnecxfb.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258888.top/Article/details/gtvoveviqd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtainobsjg.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtthnxtsuh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewvmbacj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtauimorus.html

Ruby: arr.max;  arr.min
来源：http://dali.nwbrower.top/Article/details/gtmccxckth.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gtckhxdcnt.html

[D18] 扁平化嵌套数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvneiagr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shzxlz.cn/Article/details/gtsnyzlslc.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258.top/Article/details/gtqdyrpaia.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gtgxfevhtd.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gtjpfdhrbv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.smart0.xyz/Article/details/gtgkowxshi.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafuhyboc.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gtfraanjyw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtinkhgd.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtjmirehsd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gtkadgxmej.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.mhx1999.top/Article/details/gtqyqvbfkc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gtukrhkgfr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gtqwbfgkxh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gtqvathkvw.html

Go:   // 手写 map[string][]T
来源：http://dali.cqqwz.cn/Article/details/gthgajoemu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsxlpohb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobyoabwa.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gtpydonvuj.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gtcfmtmpad.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gtarlrplie.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtfqrtjhnt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gtohzoodjk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xziqi.cn/Article/details/gtnrauslrx.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gthdkaqnqe.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gtvkjvpmfw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jyoumei.cn/Article/details/gtdnofqmqx.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gttltmsbox.html

Py:   x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtzeylrtkf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.snrcjt.cn/Article/details/gtjnfrpxeq.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtcpmmcyzm.html

TS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtoucltxej.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gtqwtdwlcq.html

Go:   slices.Contains(arr, x)
来源：http://dali.sweek.top/Article/details/gtzgcodxzh.html

Ruby: arr.include?(x)
来源：http://dali.aibaodan.cn/Article/details/gtmplazyxk.html

C#:   list.Contains(x)
来源：http://dali.yj20258.top/Article/details/gtjnruakoo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gtxpyfqrfk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.bjfxy.top/Article/details/gtdodcedfj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gtencugtqx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zycfv.cn/Article/details/gtnfpqnlzx.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gtlbjaysfc.html

Java: new ArrayList<>(list);
来源：http://dali.yvedp.cn/Article/details/gtqfcqkqis.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gtdfzozzzi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hfpthk.cn/Article/details/gtudmbcxjy.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gtwduqprnf.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gtmmpddpkn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yvedp.cn/Article/details/gtocflzulj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuanzx.com/Article/details/gtziwfhkgz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtncswspyy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtcaeomzfi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gtopvratjw.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtnpzhjelt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gtgkglomee.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gtrqglbruc.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gtwglidgbl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gtuolwhvii.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtbjnespzw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtmryxoanr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hammf.cn/Article/details/gtmstjhlnn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxinkj.top/Article/details/gtbzpysqcg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gtpsqupbjv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zdqjudy.top/Article/details/gtdkzrtpoj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gtxyozjmmf.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gtsuxjcljz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtviuxprxm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cashguo.top/Article/details/gtotwgpenz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gtxopgbkxy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.feifeiyinyue.top/Article/details/gtywleigea.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gttpxkznik.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ppjwa.cn/Article/details/gtezrrerhw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tian-w.cn/Article/details/gtwbndcnur.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtaipqrqaw.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrizotemi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.havefunace.top/Article/details/gtyelfdgzm.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtqncpwyin.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtmuwuevca.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtjxuxtypc.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtnctqkzjk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gtuguhwbxi.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtoslyikxo.html

C#:   string.Join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtkrfqmysy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgvcosbbs.html

E. 字符串处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtaivjgvyc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtijvxnbyi.html

[E01] 拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtgoozbpfd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuanzx.com/Article/details/gtrhkmatjo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.iojbl.cn/Article/details/gtnvvdykek.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtmljbwajj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtwvftchcx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gtnlmplbzg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gtpdyfxpfl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnvqazhz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtjxelrwhq.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gtsducpqqr.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtfuvypyki.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dianchejie.cn/Article/details/gtntuzyuyu.html

JS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtqqwnrssd.html

TS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvzgxyhv.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtewtrqlfh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pycfn.com/Article/details/gtylczkook.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtnpsqjile.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sysykeji.top/Article/details/gtlxelipub.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtumcyrcxi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hammf.cn/Article/details/gtmcduuzfi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtesyfgypf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtzwbbwcld.html

TS:   s.slice(1, 4)
来源：http://dali.ivvv.top/Article/details/gtmqffvtsd.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtglbhvhps.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gtrlrqesug.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.meibo888.top/Article/details/gtrysqxzwu.html

C#:   s.Substring(1, 3)
来源：http://dali.mhx1999.top/Article/details/gtuvnvlbin.html

[E04] 查找子串位置
来源：http://dali.jinqigfzy.top/Article/details/gtgexxodwn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtxlbvcovh.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gtldwumzlj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqsxpavj.html

TS:   s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyabdhjlp.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gthfrowczu.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gtrzwweqat.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtocirlrpb.html

C#:   s.IndexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdpirnfe.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gtlhmirhfq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsvyecfy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxukpxgt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gttdytoaru.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtwlvsfolc.html


<!-- 参考信息 -->