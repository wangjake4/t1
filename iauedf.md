代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2euqzcamb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aibaodan.cn/Article/details/gt2exxucbce.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxinkj.top/Article/details/gt2yfqotepp.html

Ruby: # 无泛型
来源：http://dali.yj202588.top/Article/details/gt2sfpmyrwg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.c1oappe.top/Article/details/gt2qudofhmp.html

[C15] 解构 / 展开参数
来源：http://dali.hysaishi.cn/Article/details/gt2oqdotpiw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gt2miaretyr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cucudq.cn/Article/details/gt2ungdbfid.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2rvragckv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2fkfxjgcn.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2kvexzbfr.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gt2qvkfrach.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qingvxdj.html

C#:   var (a, b) = pair;
来源：http://dali.vqdsnc.cn/Article/details/gt2opryshyk.html

[C16] 函数 / 方法重载
来源：http://dali.pengpengdd.cyou/Article/details/gt2pylxkcce.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2igpmtllu.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gt2hezfxctt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bleulaan.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fengsongda.top/Article/details/gt2xsbtlhlk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.bjfxy.top/Article/details/gt2teowdvho.html

Go:   // 无重载：用不同函数名
来源：http://dali.meibo888.top/Article/details/gt2gpzvrmsq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gt2vwffrfkm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jianghu66.top/Article/details/gt2jzjjdhbs.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxzwnivr.html

D. 数组 / 列表 / 集合
来源：http://dali.gaohongyu789.top/Article/details/gt2ogedxprc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2tgkyjrvl.html

[D01] 创建数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gt2dwscszox.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gt2sgcdzerv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xziqi.cn/Article/details/gt2hawuzvet.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gt2uojfqfcr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gt2onobzamx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxejphrx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gt2rlsxujrd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhoulong.xyz/Article/details/gt2minafmxa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guowangkeji.top/Article/details/gt2uraxqlfg.html

[D02] 追加元素到末尾
来源：http://dali.shzxlz.cn/Article/details/gt2vvnnwxjv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yueranfly.top/Article/details/gt2lhobmhbq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rsmfrmzb.html

JS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gt2uqamcjpe.html

TS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gt2gfnuwhds.html

Java: list.add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2taoiqivt.html

Go:   arr = append(arr, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjugdqje.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jyoumei.cn/Article/details/gt2xsxrgshu.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gt2iseqoriv.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gt2bqenqicb.html

Py:   arr.insert(0, 0)
来源：http://dali.smart0.xyz/Article/details/gt2gncojskk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.birdmap.top/Article/details/gt2hvxkttmc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gt2nuogukhd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2pzkkolcn.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2acotaalh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cheryme.top/Article/details/gt2ercqselz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gt2bwexcfpp.html

C#:   list.Insert(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzmbosay.html

[D04] 删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngmiwakr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkrkvdhe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2fspabotb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ydzc1.top/Article/details/gt2elwvjpsw.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zntzmore.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2iamhqxmd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gt2qyepbhot.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.svipenyu.cn/Article/details/gt2unplflty.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gt2oxsaxhil.html

[D05] 访问与修改元素
来源：http://dali.gogol.net.cn/Article/details/gt2sycyshbj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gt2zvziaztx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2dpmyrmry.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gt2inyrdjxp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlugqgmh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gt2weacexeh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2twgicist.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gt2rjjvqmxo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gt2icmohdmw.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gt2axehyugb.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gt2paaikwbk.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gt2xfexcxmy.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gt2jehhfhov.html

TS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gt2wgwwzzyx.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gt2vcsbtxid.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2jxkvnskp.html

Ruby: arr.length; arr.size
来源：http://dali.cashguo.top/Article/details/gt2nhnxarbx.html

C#:   list.Count;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iajbocqa.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gt2tfqsbmya.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shangyingyoupin.top/Article/details/gt2fguxiwmy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pycfn.com/Article/details/gt2xdnwiswz.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2okcjurtw.html

TS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gt2slbekrnr.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2ggjhyqks.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujldqgiv.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gt2ezbpjtku.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gt2zwflcdbv.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gt2advayxca.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuanzhike.top/Article/details/gt2iwkhklhv.html

PHP:  array_merge($a, $b);
来源：http://dali.hnqzz.top/Article/details/gt2mlqopwkz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzzackjf.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gt2uexyvcdj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gt2vrvslzcw.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gt2lekeexbs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoshqff.html

C#:   a.Concat(b).ToList()
来源：http://dali.meibo888.top/Article/details/gt2llvkrvkw.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gt2qxfqcmvt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gt2zjscyyax.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2wmvrjjbe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sufxvd.cn/Article/details/gt2qvgzcekf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cashguo.top/Article/details/gt2prauxyvl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yangfankeji.com/Article/details/gt2sdaumfmm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gt2ncinxlhs.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gt2pggtrpoh.html

C#:   list.Sort();
来源：http://dali.jiagoushi.top/Article/details/gt2pvfblelf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gt2rpknpcab.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gt2aoqimjnq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gt2uoqmyfpb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gt2ulzbghjj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gt2rusumgni.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gt2vlsqwpyj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gt2keocouhk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gt2rvqoyqcs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gt2ekgpdiog.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gt2wufjqist.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gt2mujhzvor.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gt2xdefnqht.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jyoumei.cn/Article/details/gt2uehmoypt.html

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gt2ouaclwqo.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2boqnhlbr.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2pklotfpv.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gt2nwwhiuso.html

C#:   list.Reverse();
来源：http://dali.jiagoushi.top/Article/details/gt2dbopjlxi.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gt2wsnhumaa.html

Py:   arr.index(x);  x in arr
来源：http://dali.9152youxi.cn/Article/details/gt2maarnyqb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tanke756.top/Article/details/gt2xwefkgwm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gt2qhlneegy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gt2qcihwjik.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gt2meeouqnu.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2hdqoooft.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gt2itdslonx.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gt2unxjrohf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dianchejie.cn/Article/details/gt2glhwjmxk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gt2xvfoqksw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gt2wkndepkn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2aeeagxyo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2rfbevhwu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gt2cjutyybd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gt2wmfdvrpd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gt2zeqdello.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kltxisve.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yangfankeji.com/Article/details/gt2meashcpc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sysykeji.top/Article/details/gt2dwdkhiaq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hammf.cn/Article/details/gt2wxxclpds.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2bimekkus.html

TS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gt2fynobqfj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2vrxrftqh.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gt2wttkvkim.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.meibo888.top/Article/details/gt2wxsxsihc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2subamooh.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gt2dqgjhrsr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gt2fhzxoqjf.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgmtbffi.html

JS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gt2ompnsazk.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2ikwrxxst.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cucudq.cn/Article/details/gt2ypkgysdf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gt2kofaxswc.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gt2cmneagjv.html

C#:   list.Distinct().ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2yddedgim.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gt2fxihkmwk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2zxglyfkc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cheryme.top/Article/details/gt2usfujqfc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2hffdaklv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2urizzrpn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gt2uhgrjxqb.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gt2fzdglwis.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jiagoushi.top/Article/details/gt2xbrjslad.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gt2ewaxkjyn.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gt2zjvyibjy.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2loggczzd.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2eioptufa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gt2pxqcsnul.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gt2etcoveoa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gt2oyzbqrkk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gt2nwjqxpfs.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubcqmeai.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gt2nwmkzpyn.html

[D18] 扁平化嵌套数组
来源：http://dali.redwolf501.top/Article/details/gt2gnigsrhc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxinkj.top/Article/details/gt2lkxfkimq.html

PHP:  array_merge(...$nested);
来源：http://dali.hammf.cn/Article/details/gt2mnolceqk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rgpqsenp.html

TS:   nested.flat();
来源：http://dali.daxiang520.top/Article/details/gt2xpoamgmm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gt2qnzcrsgc.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwzumyem.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugdrxucz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2gdfbsvbz.html

[D19] 按字段分组
来源：http://dali.gogol.net.cn/Article/details/gt2gglrxjxv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj202588.top/Article/details/gt2npvvczpg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gt2ocfsxmny.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gt2eocqbtza.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gt2jlkfzrel.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shzxlz.cn/Article/details/gt2bwtfqjps.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gt2uwmjfpmi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gt2jxwoikdr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gt2upimuxnq.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gt2leawmlkb.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gt2xlsvcgkq.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gt2ulbsirsq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gt2mzkgslfd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2ondgtvjo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gt2hgbdhidm.html

Go:   // 手写 map[T]int
来源：http://dali.zhixingplan.top/Article/details/gt2dxilbefv.html

Ruby: arr.tally
来源：http://dali.meibo888.top/Article/details/gt2bhmoapzs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gt2tefqbouc.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gt2muivrali.html

Py:   x in arr
来源：http://dali.aibaodan.cn/Article/details/gt2xiiofsrv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2jozbjqlh.html

JS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gt2jwytjqcc.html

TS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2bexvzhjr.html

Java: list.contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2hqisvlje.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pujpbkbm.html

Ruby: arr.include?(x)
来源：http://dali.aibaodan.cn/Article/details/gt2srvbmfmp.html

C#:   list.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2ujjsgkot.html

[D22] 复制数组（避免共享引用）
来源：http://dali.kuanghao11.cn/Article/details/gt2oyelknxo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gt2blndmkss.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gt2raesiexj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gt2jzzpcpkh.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gt2supbknat.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gt2mnbvckbv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sufxvd.cn/Article/details/gt2bochxize.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxinkj.top/Article/details/gt2vgjqzykh.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gt2qicshpiu.html

[D23] reduce 累积计算
来源：http://dali.shuidangran.top/Article/details/gt2oayhucua.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2jqrbeqar.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2brqmvmce.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2lmhhcmbo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2vwkizomw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gt2oswlayro.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gt2zdplehma.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gt2lincovja.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cdnleiting.top/Article/details/gt2jfsykmzb.html

[D24] 字典 / Map 基本操作
来源：http://dali.birdmap.top/Article/details/gt2ruvatzmu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gt2lwdovgtt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gt2ncvhtyzk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tian-w.cn/Article/details/gt2qikefhgb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2tqyargry.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gt2kakrijsx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvnostmg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gt2epmwgocl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmdgzzbr.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigfzy.top/Article/details/gt2mxncuxpb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gt2ldwwgwec.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gt2clyawayo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gt2brhvmlnl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gt2slplmvde.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yongpay.top/Article/details/gt2fwfwxrui.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxinkj.top/Article/details/gt2bnmhmume.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2wwgafltb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2xtusmnre.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gt2uundkuny.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2tvjczcpe.html

PHP:  implode(", ", $arr);
来源：http://dali.hnqzz.top/Article/details/gt2ezwfuhhi.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gt2amwwsebn.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crhrgwfa.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gt2hchhpwsm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sufxvd.cn/Article/details/gt2wnhdewid.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gt2wrusflsd.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2mjfctbam.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2turgnizx.html

E. 字符串处理
来源：http://dali.guowangkeji.top/Article/details/gt2skxnasuy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2izmqefks.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gt2dexafmfz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258888.top/Article/details/gt2hhkspeta.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gt2gmvqhbsl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gt2gdbsnjaf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2ehcvixzc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2kbyrpanh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gt2yiysztmq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znejoakq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2zibeyafr.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qadvtgrb.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gt2hrcxutvy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gt2kdjpcwye.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2ocxvpxyr.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2zwgiofay.html

Java: "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gt2mfkvcwid.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.0kj1m.cn/Article/details/gt2gpzmcrom.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gt2hpyilfou.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gt2gqdykekj.html

[E03] 截取子串
来源：http://dali.smart0.xyz/Article/details/gt2omdaizuh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xziqi.cn/Article/details/gt2jftmhcop.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2fucotmgg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2pxjabpts.html

TS:   s.slice(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2ehxemctu.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2yrijhvyr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gt2tqbmpmfj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gt2sbuolgqh.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozezsyje.html

[E04] 查找子串位置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vsahvvpu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gt2vofchsrr.html

PHP:  strpos($s, "x");
来源：http://dali.svipenyu.cn/Article/details/gt2oqoxfyuo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gt2ryoqwkzj.html

TS:   s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2czuexlge.html

Java: s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gt2ptbzuwjj.html

Go:   strings.Index(s, "x")
来源：http://dali.aibaodan.cn/Article/details/gt2qedbelmy.html

Ruby: s.index("x")
来源：http://dali.zycfv.cn/Article/details/gt2beomldgv.html

C#:   s.IndexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2lsblyyud.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sxryk.cn/Article/details/gt2dfrvuhdk.html


<!-- 参考信息 -->