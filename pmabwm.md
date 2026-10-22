代发 wailian999

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gt2uycgpibw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenlongwang.top/Article/details/gt2sxittkhc.html

PHP:  // 无泛型
来源：http://dali.mhx1999.top/Article/details/gt2hbizdzxh.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gt2crzksvqa.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruqlwafq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gt2ryhtcvvc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yangfankeji.com/Article/details/gt2mwqoqjil.html

Ruby: # 无泛型
来源：http://dali.chenlongwang.top/Article/details/gt2qqbtpjzd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gt2guiygrir.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzveghpz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yongpay.top/Article/details/gt2qpfxvfgv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cqqwz.cn/Article/details/gt2yxrvsnsw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gt2jxglmpzt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2sgnkifyw.html

Java: // 无解构
来源：http://dali.nanxinkj.top/Article/details/gt2yavrgysi.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gt2blswavlp.html

Ruby: a, b = pair
来源：http://dali.wangdashe.top/Article/details/gt2ueokecyd.html

C#:   var (a, b) = pair;
来源：http://dali.yongpay.top/Article/details/gt2kacqvatn.html

[C16] 函数 / 方法重载
来源：http://dali.jlsjyb.cn/Article/details/gt2vfnbgdip.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cheryme.top/Article/details/gt2oxdzuyxz.html

PHP:  // 无重载
来源：http://dali.zhengqikj.top/Article/details/gt2cfhwxexq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgfzy.top/Article/details/gt2gbnoudhs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.birdmap.top/Article/details/gt2wymarzyd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258.top/Article/details/gt2hzkqovmp.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvgnkgda.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guannengcc.top/Article/details/gt2eclovibn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2uzwmvkcm.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2opupzxks.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gt2wluisang.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2mirvffot.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kptxpspe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.svipenyu.cn/Article/details/gt2shobutnd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gt2uerbbmtm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2auzlofmy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ivvv.top/Article/details/gt2xlqodizn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xylfe.cn/Article/details/gt2lmaqmyrd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gt2cgprfxmz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhoulong.xyz/Article/details/gt2lvymcvbf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gt2amuixzlf.html

[D02] 追加元素到末尾
来源：http://dali.gaohongyu789.top/Article/details/gt2jqnxftzv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yongpay.top/Article/details/gt2mysfjbok.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gt2enflbnlk.html

JS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gt2brshsbke.html

TS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pptdccqe.html

Java: list.add(4);
来源：http://dali.yongpay.top/Article/details/gt2oanheolx.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gt2kkxpsfib.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odfrbhjq.html

C#:   list.Add(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2tayhlass.html

[D03] 在指定位置插入元素
来源：http://dali.yj202588.top/Article/details/gt2ethsdgvi.html

Py:   arr.insert(0, 0)
来源：http://dali.andypj.xyz/Article/details/gt2wgmlyphv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hysaishi.cn/Article/details/gt2indnwmke.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2usabxivu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2rhpxchew.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2gdbrxvhy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zycfv.cn/Article/details/gt2emxvwqmu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gt2korvwexh.html

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2wqymmpug.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gt2taompyay.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gt2bjwfilpg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gt2mjxsgohx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.svipenyu.cn/Article/details/gt2djfswoef.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gt2qnwqsytm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gt2qirfjvtt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbfhpcqr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itydgceh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2quxzxmjp.html

[D05] 访问与修改元素
来源：http://dali.cqqwz.cn/Article/details/gt2cmsmonrs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gt2itmpgjqz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2zpotakoi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2yissdilt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqccgfox.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nwbrower.top/Article/details/gt2dlulypdv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gt2gmxmzzvn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2vhzuozeu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2nucsgetm.html

[D06] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gt2ujwgzqww.html

Py:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2odcvytpe.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gt2rwgcblqg.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gt2vckyxomz.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvtrchfl.html

Java: list.size();
来源：http://dali.gaohongyu789.top/Article/details/gt2mnqsppsf.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gt2xoomronl.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gt2etdazdlg.html

C#:   list.Count;
来源：http://dali.fzhhl.top/Article/details/gt2dmiwrzhq.html

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gt2psmosxas.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gt2cwskrjpd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gt2pbylbepu.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2taxrsnse.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2ssnoarhd.html

Java: list.subList(1, 4);
来源：http://dali.xuanzx.com/Article/details/gt2jaruxfpp.html

Go:   arr[1:4]
来源：http://dali.andypj.xyz/Article/details/gt2tdrvuhyk.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gt2dsrtskyh.html

C#:   list.GetRange(1, 3);
来源：http://dali.havefunace.top/Article/details/gt2qykhmxei.html

[D08] 合并两个数组
来源：http://dali.9152youxi.cn/Article/details/gt2ggghvdpi.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gt2aycuoypv.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gt2sqqapwiv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gt2qlmdyvpk.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gt2yhlzfhok.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gt2mzqsrxrg.html

Go:   append(a, b...)
来源：http://dali.redwolf501.top/Article/details/gt2umlozgoy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gt2xvvsesuz.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gt2eylipswt.html

[D09] 排序（升序）
来源：http://dali.dashuyun.cn/Article/details/gt2dbjkyiik.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2cykvaplq.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2yutssdsu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gt2gaizxosc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gt2riwuytez.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxuanxn.top/Article/details/gt2dlmnyryz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2tummsolg.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gt2dlarwlfv.html

C#:   list.Sort();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnbiymhw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.snrcjt.cn/Article/details/gt2joagvppa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sysykeji.top/Article/details/gt2xbmaalfb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gt2xrlyhsku.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gt2vfdukhhu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gt2jonzvyiv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cqqwz.cn/Article/details/gt2eoundcsg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gt2scfxdefg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zdqjudy.top/Article/details/gt2uaawtbbx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gt2iukadmzx.html

[D11] 反转数组
来源：http://dali.jinqigufen.top/Article/details/gt2ppcfpxab.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gt2eurmmumw.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szkfwoha.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgufenzy.top/Article/details/gt2wevhssxm.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yeslvukf.html

Java: Collections.reverse(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2gltoropm.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2ctcdcjnn.html

Ruby: arr.reverse
来源：http://dali.hnqzz.top/Article/details/gt2uekwpwru.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqrcktsi.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ygbzyofe.html

Py:   arr.index(x);  x in arr
来源：http://dali.jlsjyb.cn/Article/details/gt2lcbglmtf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2bwaucdhg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2hyuxxcut.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lfusrnjq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.redwolf501.top/Article/details/gt2kpthblrr.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2aksetoko.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2mgfqeoan.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gt2asdagfmf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.bjfxy.top/Article/details/gt2egspwzge.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258.top/Article/details/gt2wxcdgjjq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gt2vglcfsjo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gt2vhrxvhqt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uuzcugec.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2izdtgmvw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gt2pitqsaub.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.kuanghao11.cn/Article/details/gt2yyzcsmlq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gt2zrwgvick.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdrqltgp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2fwwbtjkt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2vspomwmt.html

JS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gt2mfuewhhq.html

TS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2lsbblgqe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gt2rhhcnzia.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gt2anesvlza.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tongcxcd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hammf.cn/Article/details/gt2eccsazbo.html

[D15] 去重
来源：http://dali.jianghu66.top/Article/details/gt2douzmvsj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtsmssrh.html

PHP:  array_unique($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2qkzjecsu.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2vbkzpqli.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gt2lmprltsm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2hakdjlwa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gt2xiarijqy.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gt2bmccspss.html

C#:   list.Distinct().ToList()
来源：http://dali.pycfn.com/Article/details/gt2jczgonlx.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gt2olxxfmye.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2yijiftwj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2nhtmtnqp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2iovmrirf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2xqazjtxp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hywenlv.cn/Article/details/gt2nrguenuz.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gt2ktdgumxw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bcaikymf.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258888.top/Article/details/gt2zedkvywe.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gt2hibtxoqa.html

Py:   max(arr);  min(arr)
来源：http://dali.andypj.xyz/Article/details/gt2faktpulo.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2msnetamy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gt2mshnzesp.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gt2tjrtxlcu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sxryk.cn/Article/details/gt2gafsnvua.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2tgmoqxuh.html

Ruby: arr.max;  arr.min
来源：http://dali.ydzc1.top/Article/details/gt2fkdwkwux.html

C#:   list.Max();  list.Min()
来源：http://dali.sxryk.cn/Article/details/gt2zawpnqap.html

[D18] 扁平化嵌套数组
来源：http://dali.hnxiangtu.top/Article/details/gt2rivpjrxq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gt2biqewbwm.html

PHP:  array_merge(...$nested);
来源：http://dali.cucudq.cn/Article/details/gt2erxkdxbk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hysaishi.cn/Article/details/gt2nmmdhtih.html

TS:   nested.flat();
来源：http://dali.hnqzz.top/Article/details/gt2sfgpjyoy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2loffrfqo.html

Go:   // 手写双层循环
来源：http://dali.316326.xyz/Article/details/gt2ycwtlcgn.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gt2scaaqipm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2zjtjpjth.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gt2zlqtzhnt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangdashe.top/Article/details/gt2utauysii.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258888.top/Article/details/gt2yfvfmpfr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ybcxt.top/Article/details/gt2xgbixgoa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gt2eropcyyn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gt2sxczropo.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gt2tatpwuzl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhixingplan.top/Article/details/gt2ppqxlfqp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenzaomai.com/Article/details/gt2nkgqizof.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2mejbsapi.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gt2mjfnyhvg.html

PHP:  array_count_values($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2mixwlccv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gt2maesqpqh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gt2nggzhyrk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gt2gfotefog.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gt2bwmfxikv.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gt2bfaikmsv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gt2cqyjrvry.html

[D21] 判断是否包含某元素
来源：http://dali.jyoumei.cn/Article/details/gt2nutusqna.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gt2zdkacqfu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxaidjie.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2blqjoxtf.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2wgyxiube.html

Java: list.contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2qsrkeuzk.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2ufdfzooq.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gt2qhitojvf.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2bpnmlqui.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gt2vrrimbgy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2hisynjak.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gt2sfwiwiuv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2tkxsanfz.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwajzwqk.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gt2plwxyfwy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yanxiufei.cn/Article/details/gt2mjnvfjbp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gt2ukjrjgcj.html

C#:   new List<int>(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2bqedpfxi.html

[D23] reduce 累积计算
来源：http://dali.yueranfly.top/Article/details/gt2zuvmdhse.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tian-w.cn/Article/details/gt2imniuscu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnqzz.top/Article/details/gt2saevehxt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2igrnpvmb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gt2scrawigb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yongpay.top/Article/details/gt2mwpsjiye.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2uoiitcyc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guannengcc.top/Article/details/gt2gpbtznwc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfrmjopc.html

[D24] 字典 / Map 基本操作
来源：http://dali.tian-w.cn/Article/details/gt2sedemyzg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.0kj1m.cn/Article/details/gt2btouujtj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqnoosdr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.316326.xyz/Article/details/gt2ypcyeyfn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2nyhmzwsr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jyoumei.cn/Article/details/gt2ivljsnui.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cekcalbe.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gt2nysrupne.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guowangkeji.top/Article/details/gt2ymjfgqwh.html

[D25] Set 集合去重与交并差
来源：http://dali.hnqzz.top/Article/details/gt2vnjwmpdp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hysaishi.cn/Article/details/gt2hjosabce.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj202588.top/Article/details/gt2mksnoefi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gt2uondvxsq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jiagoushi.top/Article/details/gt2myjqbmpe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gt2fnfjjmle.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fzhhl.top/Article/details/gt2cglkojap.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2fzqpnths.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvhdnhuz.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2lrdittdm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpsudlps.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gt2mrxnbujv.html

JS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2isxelzcj.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2mjdelfks.html

Java: String.join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gt2zinlbnfl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gt2eeeokuyn.html

Ruby: arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gt2fzqisdef.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2iqzkosuv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2spjujxjv.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gt2hyglwvvy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2uxoezkwf.html

[E01] 拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2ecsvmire.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxexzzlb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gt2jltdyiic.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2hsktjpco.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gt2ziyivpmb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxacgazy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2pqcrkicu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gt2sicwczyu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2kesglohe.html

[E02] 重复字符串
来源：http://dali.jianghu66.top/Article/details/gt2vfskpdnn.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gt2yviiahok.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtnsqvrm.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezbvxldg.html

TS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gt2dcdnqpog.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2aycwmose.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hfpthk.cn/Article/details/gt2aitevshe.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gt2ycihpgat.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gt2sikzazhy.html

[E03] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gt2acjeffot.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gt2qamvcbji.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2fabucirp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2dbmsumdn.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2akflzruc.html

Java: s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2rznyoadd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxatjzrc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daxiang520.top/Article/details/gt2afncqfof.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gt2diuqlgfn.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gt2tlmnptqw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xklmdddv.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gt2qthohkei.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gt2lgmljqhl.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gt2oakrwivj.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2kwqzfomf.html


<!-- 参考信息 -->