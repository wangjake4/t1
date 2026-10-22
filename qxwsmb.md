代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gt2kcyiqglr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gt2qvvffcok.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gt2bcgusxel.html

Ruby: # 无泛型
来源：http://dali.redwolf501.top/Article/details/gt2ofqiwozm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yanxiufei.cn/Article/details/gt2qmvwuoyt.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfrsdblb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gt2xtoviyvr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jyoumei.cn/Article/details/gt2eewrijbg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2kezpsiag.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.c1oappe.top/Article/details/gt2teorsqvv.html

Java: // 无解构
来源：http://dali.c1oappe.top/Article/details/gt2bzecauzc.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gt2yemoixdw.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gt2aguxrntl.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tuqvvdng.html

[C16] 函数 / 方法重载
来源：http://dali.xinyue.icu/Article/details/gt2axchzuij.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yongpay.top/Article/details/gt2rtlrvmyq.html

PHP:  // 无重载
来源：http://dali.ivvv.top/Article/details/gt2tusrjdnj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gt2gisrjjwe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gt2ejfuxtib.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jyoumei.cn/Article/details/gt2bgojawnh.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfngsdss.html

Ruby: # 无重载：靠动态参数
来源：http://dali.c1oappe.top/Article/details/gt2kvdglmcy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jianghu66.top/Article/details/gt2lvufhgml.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2rebtjgze.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gt2nerrdaxc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2dsqahlvu.html

[D01] 创建数组 / 列表
来源：http://dali.dashuyun.cn/Article/details/gt2svzrzxqb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daxiang520.top/Article/details/gt2ekuobbbk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gt2uyywgzap.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenlongwang.top/Article/details/gt2mcehplzb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigfzy.top/Article/details/gt2qoaibhkn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.snrcjt.cn/Article/details/gt2unmnvrli.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.andypj.xyz/Article/details/gt2ytzhoahc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2mducggoa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hammf.cn/Article/details/gt2ibicwhmv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdnraui.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xylfe.cn/Article/details/gt2gcmfbami.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlroewkz.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gt2hzqyhojh.html

TS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gt2ryronfwb.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwpfhdy.html

Go:   arr = append(arr, 4)
来源：http://dali.sxryk.cn/Article/details/gt2vduojfvg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xylfe.cn/Article/details/gt2flqqjndu.html

C#:   list.Add(4);
来源：http://dali.dashuyun.cn/Article/details/gt2wzmmsndu.html

[D03] 在指定位置插入元素
来源：http://dali.zhengqikj.top/Article/details/gt2srhliafa.html

Py:   arr.insert(0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mowvaokp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cheryme.top/Article/details/gt2ztqdtjbl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxgmidoa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2exjdczui.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2utrkgoka.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmetvvpt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gt2hexmcnup.html

C#:   list.Insert(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gt2sihadvzf.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gt2fjhsqdwt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gt2gbzvbxof.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fzhhl.top/Article/details/gt2wwhlvggm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.quarkkingdee.top/Article/details/gt2zfwulcys.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gt2cjyymhtr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.c1oappe.top/Article/details/gt2swnmvdhy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izlxxldz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gt2wxjibngx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrllogbw.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmenwkku.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gt2luktzyfr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2bifviwzl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2pvpxkdmb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnqzz.top/Article/details/gt2jpfsnkpa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gt2qhwvzaiw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2dysbaebe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2jhbnerig.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gt2dqmnmymj.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gt2oyhkyzpe.html

Py:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2yrgyukzu.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2yqccjlum.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gt2bunseqiu.html

TS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gt2swifsyil.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gt2bdhvjwxn.html

Go:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gt2ogrmnmfc.html

Ruby: arr.length; arr.size
来源：http://dali.havefunace.top/Article/details/gt2qcsmfzcg.html

C#:   list.Count;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fgyfjimw.html

[D07] 切片 / 取子数组
来源：http://dali.havefunace.top/Article/details/gt2nprbruan.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yangfankeji.com/Article/details/gt2prlnkudw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gt2jncwvyip.html

JS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2zxgihnrd.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2yfxhrkjg.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvozqkyz.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gt2nukbmzml.html

Ruby: arr[1, 3]
来源：http://dali.guannengcc.top/Article/details/gt2cpewzhok.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gt2kgnegywb.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gt2nlqqsqtt.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2ienmpnys.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gt2ypcarlbx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gt2byqqcivq.html

TS:   [...a, ...b];
来源：http://dali.hnqzz.top/Article/details/gt2peotiuow.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.svipenyu.cn/Article/details/gt2nubedllw.html

Go:   append(a, b...)
来源：http://dali.ybcxt.top/Article/details/gt2jmfwheqd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2vzjitohv.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqhnwxty.html

[D09] 排序（升序）
来源：http://dali.cashguo.top/Article/details/gt2zivdwkuu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gt2piqhwbdw.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odmcpudg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nwbrower.top/Article/details/gt2lgacrpif.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gt2heneloqs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gt2unsqqanq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2iiyglimp.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbkvidky.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gt2rzqcybfa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.c1oappe.top/Article/details/gt2ycuunbyy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2caxuctwt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgbhmob.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gt2yzhhrhmx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gt2wlldfgzz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.svipenyu.cn/Article/details/gt2awfebvde.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdzulahl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gt2fiiskwae.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gt2utjyfvfu.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gt2znkqesde.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xylfe.cn/Article/details/gt2qekxuudq.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2lutmfmtu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuetiantiany.cn/Article/details/gt2nrnaapwe.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gt2lrqdpbzr.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gt2hnwsotog.html

Go:   slices.Reverse(arr)
来源：http://dali.xuanzx.com/Article/details/gt2nmoqkkpg.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gt2wbueokqj.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gt2sdzdndbb.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gt2oqeypyko.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gt2vmzlxjoq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2xdpaoxhd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rljxlpou.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lblhqjaj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gt2atsxxsth.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2ufwsihra.html

Ruby: arr.index(x)
来源：http://dali.cqqwz.cn/Article/details/gt2iyqpirxm.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gt2ygmpxecv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gt2aebazwmy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgdumajt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gt2nzigmiai.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gt2xlprzoee.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2avuhuonq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.svipenyu.cn/Article/details/gt2ziuokvit.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gt2roclujdg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gt2xrzggfnb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gt2sjkwnyvg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gt2djljqmwy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gt2hlkgzdfz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2alomljcr.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2bwwzfahk.html

TS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gt2arzfxppk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2ebjdxlxb.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2drcnyeii.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.meibo888.top/Article/details/gt2kcnzxodg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2mvjbfqro.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2fmehcxsa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gt2cyeekbtw.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gt2qrwiwizl.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gt2bleixcpu.html

TS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gt2oxyjnfzd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gt2dkhuyenm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xylfe.cn/Article/details/gt2ohaobydl.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gt2lxglhvlt.html

C#:   list.Distinct().ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2viqxhwpx.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2begpmddd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tanke756.top/Article/details/gt2bxyrfbxo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gt2pqkcrffq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gt2zgqurntg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gt2qfocwnvg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xziqi.cn/Article/details/gt2svnnmusn.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gt2zmznstno.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gt2sbmuynjr.html

C#:   list.Sum();  list.Average()
来源：http://dali.gotoacloud.top/Article/details/gt2anpttuwy.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gt2mzwogtaw.html

Py:   max(arr);  min(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2dveyhpwu.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2qcwbjloe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvnnuiy.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gt2qbluktgt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2vvusbwrk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2actibbuk.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gt2bsyyxisv.html

C#:   list.Max();  list.Min()
来源：http://dali.c1oappe.top/Article/details/gt2fzfzsjys.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gt2hsxjyuwg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gt2gjegrhcc.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gt2qkvfzflf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gt2hdcjqlxd.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gt2pfisngcc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ekgfxagp.html

Go:   // 手写双层循环
来源：http://dali.316326.xyz/Article/details/gt2wfsajmgd.html

Ruby: nested.flatten
来源：http://dali.guowangkeji.top/Article/details/gt2cbqtsuae.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2xwpsqdhm.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gt2vuwnlpdq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ivvv.top/Article/details/gt2rtglicmi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gt2zrfidyjv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.haohaochexian.top/Article/details/gt2mtnflgwj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gt2cnekgpbq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gt2fopfoiel.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gt2eedvtlde.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqdnmrze.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gt2zxmqsgma.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gt2rclujsyb.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2rkfzpsro.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2zpwxjppm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gt2xijzreyg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gt2yfvtmldu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzjlincl.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gt2fqiowuvd.html

Ruby: arr.tally
来源：http://dali.yvedp.cn/Article/details/gt2ffzofbot.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gt2shkcwnrw.html

[D21] 判断是否包含某元素
来源：http://dali.yanxiufei.cn/Article/details/gt2akavtwvl.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gt2eeppuahf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guannengcc.top/Article/details/gt2npylvovl.html

JS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzbxcyxx.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2jlxvvgoq.html

Java: list.contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2spgnpkwx.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2yvbhgfoy.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gt2lqrymjhp.html

C#:   list.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2qxlpnrgx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yangfankeji.com/Article/details/gt2zvrckacm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fobamjvn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gt2ejgjwmqf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2fwnfneld.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gt2ajufzsqp.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gt2daxnlacl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hywenlv.cn/Article/details/gt2nxurdhmq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gt2gmsnzags.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gt2dcdcholo.html

[D23] reduce 累积计算
来源：http://dali.yanxiufei.cn/Article/details/gt2abekllva.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gt2vuoamsnn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2yatausdv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2acjdcism.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2olgqqspj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zepldlmz.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gt2gavksxke.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gt2blqlojrg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gt2dvueyqda.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uosgxcrj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgbjlhja.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gt2pgejohqp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aibaodan.cn/Article/details/gt2copllcps.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2kmcixmly.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gt2ksunirld.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.vqdsnc.cn/Article/details/gt2egrcyzqo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigufen.top/Article/details/gt2oaoucifi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gt2vulorupw.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gt2secuumrz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.birdmap.top/Article/details/gt2kmsbkxxv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptoaysnu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gt2cbfzvuqi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgfczvtm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigufen.top/Article/details/gt2zewhabgx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ppjwa.cn/Article/details/gt2lgpdtcfe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ehwqpu.com/Article/details/gt2yxucckwm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gt2ffsjbkxv.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gt2zqprkxko.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2xraxeutm.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2ijoxmcwj.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gt2yinukptw.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2hvjqbvmz.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gt2uuyjuiez.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gt2rgqgqfgq.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2dmeieinj.html

C#:   string.Join(", ", list)
来源：http://dali.yonumen.top/Article/details/gt2xuwjdrll.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2wzxhmtys.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gt2stbfwotk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2drpghpsd.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2ooynnenz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxwqrahf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gt2dkjmproi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2kvxxdlhp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gt2uqvpzbbl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gt2ntlmtxem.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gt2rprrjxar.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gt2gpysjlvd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vppzqrpw.html

[E02] 重复字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljfubmzb.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gt2ezuspmeu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfhaqauz.html

JS:   "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gt2yksfldro.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2nlpqiwsq.html

Java: "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aharmaik.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gt2tuzidqxr.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gt2saarsczk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gt2vdidifqu.html

[E03] 截取子串
来源：http://dali.fzhhl.top/Article/details/gt2gxizgsuf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohfxauxg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2lwoysemn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2bdkuqjsh.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gt2qsirheyp.html

Java: s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gt2zvgdvcph.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhvjruwv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gt2rwwzxvyp.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gt2kedhlsya.html

[E04] 查找子串位置
来源：http://dali.chenlongwang.top/Article/details/gt2zeigimny.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2jvtkfyvp.html

PHP:  strpos($s, "x");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2makjuxio.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cashguo.top/Article/details/gt2wupazzdy.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2dtopdpuj.html

Java: s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2dkiyzrqg.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gt2fqsdtnef.html

Ruby: s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gt2qfccbeih.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2xpzabkvc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gt2yuwstyqo.html


<!-- 参考信息 -->