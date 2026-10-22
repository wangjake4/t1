代发 wailian999

[C14] 泛型函数
来源：http://dali.fengsongda.top/Article/details/gt2ldezwslq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipmssrlg.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2yobytoqa.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gt2qbzvsivi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.316326.xyz/Article/details/gt2pixlmexe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.snrcjt.cn/Article/details/gt2etlmcxyo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zycfv.cn/Article/details/gt2couqvfno.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gt2hcrexmhn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gt2hiihleqd.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gt2mapisxgw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.9152youxi.cn/Article/details/gt2kuwkqyct.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ivvv.top/Article/details/gt2gfytgiqy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2cvnwpvhk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2xmoadstt.html

Java: // 无解构
来源：http://dali.aibaodan.cn/Article/details/gt2ujbylglc.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gt2sbybmazt.html

Ruby: a, b = pair
来源：http://dali.yonumen.top/Article/details/gt2aunubgdm.html

C#:   var (a, b) = pair;
来源：http://dali.xziqi.cn/Article/details/gt2sjrqmbja.html

[C16] 函数 / 方法重载
来源：http://dali.quarkkingdee.top/Article/details/gt2cgpxbvkd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gt2yxpdpdjs.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gt2zbfdgqpl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gt2lytjehzj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gt2xocoyqva.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gt2xwzuqdzk.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gt2coxziscv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gt2dpltlasc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yongpay.top/Article/details/gt2awmkqzts.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2sespsroh.html

D. 数组 / 列表 / 集合
来源：http://dali.chenzaomai.com/Article/details/gt2ipupbokc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wupyugmn.html

[D01] 创建数组 / 列表
来源：http://dali.bjfxy.top/Article/details/gt2qdqipjmq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gt2vuzzvwhs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2medbbpim.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gt2hsircqbz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.havefunace.top/Article/details/gt2cejfoonk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gt2ekkmngdq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenlongwang.top/Article/details/gt2rggwxbhp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gt2ekywiksx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.meibo888.top/Article/details/gt2kqhvdkrg.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gt2gctiqhac.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gt2lvgtivsz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2czcouxlo.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gt2gddsfnbh.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2yejlyxxs.html

Java: list.add(4);
来源：http://dali.0kj1m.cn/Article/details/gt2tdqctqop.html

Go:   arr = append(arr, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2miaywtbj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gt2xzpvubko.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gt2bkgxccnp.html

[D03] 在指定位置插入元素
来源：http://dali.snrcjt.cn/Article/details/gt2xnwwoewu.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2tpsurhlj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cucudq.cn/Article/details/gt2kxmhkogx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gt2ycoapkbm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2zbxmtbvi.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2jtsyxwmq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2zgeioytw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.smart0.xyz/Article/details/gt2diiuivwb.html

C#:   list.Insert(0, 0);
来源：http://dali.hammf.cn/Article/details/gt2rlgmjhgo.html

[D04] 删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlfwvirm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ydzc1.top/Article/details/gt2vmbmhkek.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2lkrmkxwf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gt2drwqfmsn.html

TS:   arr.splice(0, 1);
来源：http://dali.c1oappe.top/Article/details/gt2pdjptwvx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gscxuwbh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gt2jdyzmupj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gt2pksmaxcy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuanzx.com/Article/details/gt2cvzuowkg.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gt2nwwwhlqn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gt2kyekwfiy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2oragydtc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gt2ckobrsug.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guannengcc.top/Article/details/gt2rqqownwl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sxryk.cn/Article/details/gt2ykuhzuzx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2czrjvrbi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gt2vqvqynzc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gt2jtmycitt.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gt2rlajitau.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gt2jwppowdq.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2qwpwrmrp.html

JS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gt2yticeowz.html

TS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohnaxrem.html

Java: list.size();
来源：http://dali.xinyue.icu/Article/details/gt2ejdltxlz.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2eisyotlt.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2ralqwvlq.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gt2fplnshxl.html

[D07] 切片 / 取子数组
来源：http://dali.nanxinkj.top/Article/details/gt2kbobfxtx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gotoacloud.top/Article/details/gt2vbtdiswq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sxryk.cn/Article/details/gt2yzlljgeg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2btxzennp.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gt2ovfjafxf.html

Java: list.subList(1, 4);
来源：http://dali.xuanzx.com/Article/details/gt2leeosfqp.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gt2dwogdcjl.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvxcxtmt.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2gxdpuvcc.html

[D08] 合并两个数组
来源：http://dali.snrcjt.cn/Article/details/gt2xlsrmnwt.html

Py:   a + b;  a.extend(b)
来源：http://dali.birdmap.top/Article/details/gt2hbcfvodx.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gt2ljiewwql.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gt2xxdnijue.html

TS:   [...a, ...b];
来源：http://dali.tanke756.top/Article/details/gt2qfguehso.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hgcnykzj.html

Go:   append(a, b...)
来源：http://dali.jianghu66.top/Article/details/gt2evzquajd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjtweigh.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2jgemujjs.html

[D09] 排序（升序）
来源：http://dali.jinqigfzy.top/Article/details/gt2owzwhaaj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gt2bosywgyu.html

PHP:  sort($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2zlrdxshk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gt2qzziclwl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yueranfly.top/Article/details/gt2xhkviwtx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tian-w.cn/Article/details/gt2ibelfgbx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gt2dkgbhhvs.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gt2dsetzntq.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gt2jfyvkvlo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhucbbkk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eczvhxrw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwdjfpn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gt2pbghctfj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gt2uakbfufd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjnhbzdj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.mhx1999.top/Article/details/gt2lsokutyi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pafrgjzr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gt2zhtvrmhq.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gt2fczzwpbc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gt2flsqyqgr.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2mejoeslt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gt2blqcnutc.html

TS:   [...arr].reverse();
来源：http://dali.zhengqikj.top/Article/details/gt2yvfrzbxx.html

Java: Collections.reverse(list);
来源：http://dali.xinyue.icu/Article/details/gt2rarjxtrm.html

Go:   slices.Reverse(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2mfogkqnu.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gt2ubjnstno.html

C#:   list.Reverse();
来源：http://dali.cucudq.cn/Article/details/gt2qedmfgxy.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gt2yowwcesc.html

Py:   arr.index(x);  x in arr
来源：http://dali.tianlin.xyz/Article/details/gt2mbbyopeg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swkbyqbv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gt2mfowepzp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjbgyydo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gt2ryumjwcj.html

Go:   slices.Index(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2ddgcvtbc.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gt2clpqfnph.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gt2yypbdbfg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gt2yzjswlnu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhvjhubn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.0kj1m.cn/Article/details/gt2stpwocyb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2hafrtrel.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gt2iipxiyse.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gt2qaxkbgat.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gt2fknnwrlq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenlongwang.top/Article/details/gt2yrgvqoqx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2mvgrttqs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gt2qylazwrx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gt2rcxscbwz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gt2fdnzwjab.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2nxwmdagt.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gt2kotunhdx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2nwrqkotf.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gt2qssphypf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2akxyffgk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2fxnxesac.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gt2dadwczzz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gt2qyahkkhb.html

PHP:  array_unique($arr);
来源：http://dali.smart0.xyz/Article/details/gt2xahbpxda.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2vmkthrwa.html

TS:   [...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gt2ynaohjjs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gt2yvzoudof.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258.top/Article/details/gt2vioichzq.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gt2agawdgsi.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbfctuij.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gt2yymkfzvl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gt2hapslsfy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gt2oaubzstx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2uuampzsk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2pctzcbnd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.bjfxy.top/Article/details/gt2isynxyci.html

Go:   // 手写循环累加
来源：http://dali.yuanzhike.top/Article/details/gt2kmyqojzh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gt2hxzqtloh.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gt2zlesivrz.html

[D17] 最大值与最小值
来源：http://dali.jqgfzy.top/Article/details/gt2gonuyqbl.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2htzetldc.html

PHP:  max($arr);  min($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2rooppnlw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gt2qplkakmk.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gt2jgtrxpde.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lacaakob.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gt2yiyhuahu.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gt2iegseqxb.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gt2gzcjhvwi.html

[D18] 扁平化嵌套数组
来源：http://dali.sufxvd.cn/Article/details/gt2vbnzbjqd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gt2owxjgaqz.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gt2bpjtttld.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gt2eolebjvn.html

TS:   nested.flat();
来源：http://dali.redwolf501.top/Article/details/gt2puddpzzx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhgvdqdk.html

Go:   // 手写双层循环
来源：http://dali.jiagoushi.top/Article/details/gt2yhkkicvq.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gt2zrnihsvx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2dubotyso.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvdgtghy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gt2ynkqohel.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dianchejie.cn/Article/details/gt2sewtbxyu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gt2soytyrba.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gt2ciednmsz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nxwwzjdl.html

Go:   // 手写 map[string][]T
来源：http://dali.ehwqpu.com/Article/details/gt2vqaquqph.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ppjwa.cn/Article/details/gt2hhnyxyly.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gt2arhzqcan.html

[D20] 统计每个元素出现次数
来源：http://dali.dashuyun.cn/Article/details/gt2vcmmjvnf.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2pmcemynx.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2clyivokk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gt2tsaauxlc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gt2humltxsn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gt2lgesxryn.html

Go:   // 手写 map[T]int
来源：http://dali.birdmap.top/Article/details/gt2nukmqpkb.html

Ruby: arr.tally
来源：http://dali.fzhhl.top/Article/details/gt2lyjzbtsu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yonumen.top/Article/details/gt2aqtfbfjy.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gt2shqmrlgs.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gt2ebippepk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gt2ddwyxvlo.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2gpbgctvf.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2tpztndmi.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2lzzdrfsi.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2usigaxfp.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gt2jfwfuiip.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gt2kdddnwxk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gt2zoarrhqf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gt2oaljaaod.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenjidiqi.icu/Article/details/gt2inyniywi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2qhvjeqpp.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gt2zrvzfzem.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ikwnnpfw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gt2qnxbrumn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gt2zpqoariy.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2esonvfil.html

[D23] reduce 累积计算
来源：http://dali.yangfankeji.com/Article/details/gt2marhmcqt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2dlinmtwa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gt2ftkgskpl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gt2qlxzsvkx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gt2bhavafrg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gt2rjxfsqcl.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gt2tbzbrxyv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2upbbqxke.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gt2rpdpfoal.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gt2zclltghu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gt2bgvadmrz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gt2wtdlwvwh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2srjpqqfj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2mfnqftva.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2fdfbqgsx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gt2uodqrnje.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckjuljqq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gt2yjttlaal.html

[D25] Set 集合去重与交并差
来源：http://dali.yuanzhike.top/Article/details/gt2ehgqrcuk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gt2bixtsiit.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hongshengwenyu.top/Article/details/gt2msvjpjwx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tianlin.xyz/Article/details/gt2edtnnrzl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuanzhike.top/Article/details/gt2kaxdkpce.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gt2slreeogp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guannengcc.top/Article/details/gt2hswzdgoj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gt2jxgozfbg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gt2gprezlij.html

[D26] 数组转字符串
来源：http://dali.yuxming.cn/Article/details/gt2hiqubbls.html

Py:   ", ".join(map(str, arr))
来源：http://dali.meibo888.top/Article/details/gt2akbskkxs.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fianumdv.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gt2tdwcoqpz.html

TS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2byokfoar.html

Java: String.join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkkqbqco.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2xygmxuac.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gt2miiocycb.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258.top/Article/details/gt2azcgsghb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2yyrfvncc.html

E. 字符串处理
来源：http://dali.xziqi.cn/Article/details/gt2hskufcqa.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2edpnndgf.html

[E01] 拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2pgprphbh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.9152youxi.cn/Article/details/gt2pncnszly.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gt2zlwwngoo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gt2qlmofnnw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gt2wswwxpho.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gt2rgclpizs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jyoumei.cn/Article/details/gt2vqdxrvqg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgwqfchq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2bjmilrrt.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2rfctxwcw.html

Py:   "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxaergmm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tianlin.xyz/Article/details/gt2ttjmchls.html

JS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2qzweerfc.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2juamddsh.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2bhosjyii.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.snrcjt.cn/Article/details/gt2gzekxyog.html

Ruby: "ab" * 3
来源：http://dali.hammf.cn/Article/details/gt2wxeymtfm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.meibo888.top/Article/details/gt2fknlxuua.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gt2tttdtwao.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gt2cdxhujxz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2spfzjwsf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gt2pvbtxzfp.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gt2mmoqqskl.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gt2tortuwwk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yvedp.cn/Article/details/gt2vqgvozgr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfcssqsd.html

C#:   s.Substring(1, 3)
来源：http://dali.yangfankeji.com/Article/details/gt2rwqxztyv.html

[E04] 查找子串位置
来源：http://dali.ehwqpu.com/Article/details/gt2wbdyichk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gt2dvlmigww.html

PHP:  strpos($s, "x");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofvgzurw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gt2kxhowksk.html

TS:   s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2sbciusis.html

Java: s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2wrzpwmpn.html


<!-- 参考信息 -->