代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2psewsmzk.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbdmrsyy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gt2lrxsbviz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangdashe.top/Article/details/gt2uffmkgvg.html

[C14] 泛型函数
来源：http://dali.jinqigfzy.top/Article/details/gt2loqlrtfy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hywenlv.cn/Article/details/gt2lsuosgsq.html

PHP:  // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gt2utvhkwql.html

JS:   // 无泛型
来源：http://dali.yongpay.top/Article/details/gt2zmzzvbyk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tianlin.xyz/Article/details/gt2nlryhmqj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ebkdyzzc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yangfankeji.com/Article/details/gt2etaksmjh.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gt2bfdswitz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqqultfo.html

[C15] 解构 / 展开参数
来源：http://dali.yvedp.cn/Article/details/gt2gypjzewz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.svipenyu.cn/Article/details/gt2ugzqntre.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gt2crywmhnb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2zhxhdbep.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258.top/Article/details/gt2fvvunxsc.html

Java: // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwkmyszy.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gt2wwmyvuvd.html

Ruby: a, b = pair
来源：http://dali.zhiwuduotai.top/Article/details/gt2snflvqtp.html

C#:   var (a, b) = pair;
来源：http://dali.hnqzz.top/Article/details/gt2oeytzwqx.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hduwzpcv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.meibo888.top/Article/details/gt2ejdpismv.html

PHP:  // 无重载
来源：http://dali.xuanzx.com/Article/details/gt2abeeoegu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gt2iaqyqxmd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gt2hjjpxnvy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shuidangran.top/Article/details/gt2rtgbeigl.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuxming.cn/Article/details/gt2bnhbwmid.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gt2efcjfwrg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gt2nvzgrcys.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ouljxqfq.html

D. 数组 / 列表 / 集合
来源：http://dali.hywenlv.cn/Article/details/gt2xvifedad.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2wsllpoqg.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gt2gmlhshwr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gt2xdpnxmti.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2gintpkbk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sysykeji.top/Article/details/gt2tchminby.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jyoumei.cn/Article/details/gt2afpdkyni.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dashuyun.cn/Article/details/gt2lzgamddo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gt2xvnzjrxk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gt2wpidgzlc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gt2nzinerlr.html

[D02] 追加元素到末尾
来源：http://dali.feifeiyinyue.top/Article/details/gt2edzeggze.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.0kj1m.cn/Article/details/gt2zrqohzmy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aibaodan.cn/Article/details/gt2iewsnzoh.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gt2heyumjwp.html

TS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gt2hiinybrd.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrbfizoy.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2rublyfpd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aizwys.cn/Article/details/gt2wzqnjymk.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2fpoyqkqt.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258.top/Article/details/gt2hdigimaf.html

Py:   arr.insert(0, 0)
来源：http://dali.yvedp.cn/Article/details/gt2xdqboxpk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ehwqpu.com/Article/details/gt2bqiblclz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gt2whocgfea.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jianghu66.top/Article/details/gt2cilpnuaw.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2meqolrnm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2geuzwaam.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gt2frzvmwto.html

C#:   list.Insert(0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2pcvlrgbq.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhgypexr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2tgddutyu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2jokpculn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gt2lkmzukhf.html

TS:   arr.splice(0, 1);
来源：http://dali.guannengcc.top/Article/details/gt2ykznpsam.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdgjbkid.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gt2vivqehpn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gt2nkahvrza.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kczmhzyh.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gt2uemzqgfl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flmjhldj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gt2rvizpoez.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2kqkkkscx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yonumen.top/Article/details/gt2shvemphf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sweek.top/Article/details/gt2sdsytcar.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gt2xfqsegvx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2hbuchitd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2tdcrmwov.html

[D06] 数组长度
来源：http://dali.redwolf501.top/Article/details/gt2oglvrzhe.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gsnqqlws.html

PHP:  count($arr);
来源：http://dali.ybcxt.top/Article/details/gt2vxsmvvzz.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gt2zyweavcq.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gt2gjztamqz.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gt2hffcobol.html

Go:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2euasifcm.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gt2ovecpbcr.html

C#:   list.Count;
来源：http://dali.shuidangran.top/Article/details/gt2hzedawdx.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gt2zjbhqylm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gt2stbplzbu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2issptnyh.html

JS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2gflrsgmx.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gt2hluyvvzk.html

Java: list.subList(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2xpxmefir.html

Go:   arr[1:4]
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxljqwzx.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gt2sjhvdcej.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2bwkdvixo.html

[D08] 合并两个数组
来源：http://dali.cqqwz.cn/Article/details/gt2nczlldoz.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangdashe.top/Article/details/gt2pjlusujl.html

PHP:  array_merge($a, $b);
来源：http://dali.guannengcc.top/Article/details/gt2uqlxcpiq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tietqimn.html

TS:   [...a, ...b];
来源：http://dali.dashuyun.cn/Article/details/gt2twbfruol.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sztjbryw.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nufceuyq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2irecllqs.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2sxjmskqi.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmrvhsx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gt2ybkpsivi.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gt2tubsyaqy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gt2mvkshfag.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gt2oqswxflh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yonumen.top/Article/details/gt2kfufyhek.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxkpualb.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2naybwjnd.html

C#:   list.Sort();
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwbuigjq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gt2gabtdzys.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xylfe.cn/Article/details/gt2ixpssliz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2btstcgeb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gt2qqeweqjk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gt2joakwdrg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhoulong.xyz/Article/details/gt2bvywuwrz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dianchejie.cn/Article/details/gt2pfbwangs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tian-w.cn/Article/details/gt2tmfldkjm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dhnkuoeg.html

[D11] 反转数组
来源：http://dali.aizwys.cn/Article/details/gt2phvhucwk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gaohongyu789.top/Article/details/gt2fbkdiohu.html

PHP:  array_reverse($arr);
来源：http://dali.ybcxt.top/Article/details/gt2cftnztpl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gt2azhkdqai.html

TS:   [...arr].reverse();
来源：http://dali.yvedp.cn/Article/details/gt2olgzdhmc.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gt2omcgqgyq.html

Go:   slices.Reverse(arr)
来源：http://dali.xinyue.icu/Article/details/gt2qpstzgrr.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gt2rkkdrcub.html

C#:   list.Reverse();
来源：http://dali.andypj.xyz/Article/details/gt2vrrujpvn.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gt2wqffgufc.html

Py:   arr.index(x);  x in arr
来源：http://dali.xinyue.icu/Article/details/gt2pzpzqwiu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fzhhl.top/Article/details/gt2xomxbbaj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gt2akjihadw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gt2zqrthrrg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gt2uczdtwki.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2uvagjvnx.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gt2vmbrclte.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gt2tebkunre.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgufenzy.top/Article/details/gt2nfoismms.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gt2zmebcaee.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gt2yhhlcvfh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2fzpwtbfm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gt2sqzhreda.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2lhqhfxoh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.haohaochexian.top/Article/details/gt2qerbkwhg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.snrcjt.cn/Article/details/gt2jhdcwtbf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2pgqchyql.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gogol.net.cn/Article/details/gt2llilkszo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txrivcnn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.haohaochexian.top/Article/details/gt2didglnhh.html

JS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gt2mjpfkzxn.html

TS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gt2ovoyilfd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gt2xxqzlhpd.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gt2oqpvwiyr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj202588.top/Article/details/gt2rsikcqir.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2ydkmoheg.html

[D15] 去重
来源：http://dali.yonumen.top/Article/details/gt2zpgyzxkh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gt2dscshiaj.html

PHP:  array_unique($arr);
来源：http://dali.zycfv.cn/Article/details/gt2qrlpxqkw.html

JS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gt2kcdccetv.html

TS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsbsxvoj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.vqdsnc.cn/Article/details/gt2rlkzwhib.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hongshengwenyu.top/Article/details/gt2cldqatzy.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gt2ymqlrsap.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gt2kytlmkwf.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gt2aufhkhfu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2iljkyced.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edyxjrrg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gt2vqdmrwbx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2hxccntbu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gt2nbvrephw.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gt2thkpikzx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2hzzqaosm.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gt2yywmlbqh.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gt2antlfpkt.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gt2nocovubf.html

PHP:  max($arr);  min($arr);
来源：http://dali.316326.xyz/Article/details/gt2rdxwdhmk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gt2szdczxbn.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gt2uhbfvoft.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dashuyun.cn/Article/details/gt2bgvzcrge.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gt2pbfzdxgh.html

Ruby: arr.max;  arr.min
来源：http://dali.mhx1999.top/Article/details/gt2ipeyeknj.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atvtjnnd.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxcovjy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmitxhsr.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bnntkobr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gt2kljiupva.html

TS:   nested.flat();
来源：http://dali.daxiang520.top/Article/details/gt2zztiiaoe.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2euudguwc.html

Go:   // 手写双层循环
来源：http://dali.ivvv.top/Article/details/gt2tehngenx.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gt2ykzobebk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2igeuyoid.html

[D19] 按字段分组
来源：http://dali.chenzaomai.com/Article/details/gt2njvuoclj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.c1oappe.top/Article/details/gt2lnztqibg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yonumen.top/Article/details/gt2cfpzrysx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gt2huugrbvx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gt2tpoagdcm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gt2xnwaldtd.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqmtggby.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tanke756.top/Article/details/gt2wgkvahsg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ivvv.top/Article/details/gt2hthqfjcd.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqulofga.html

Py:   Counter(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2momwkxcq.html

PHP:  array_count_values($arr);
来源：http://dali.cheryme.top/Article/details/gt2xpxjfnav.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gt2ihhfzpuy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gt2hkviegla.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.iojbl.cn/Article/details/gt2pgdcqyms.html

Go:   // 手写 map[T]int
来源：http://dali.sxryk.cn/Article/details/gt2wjogpxyz.html

Ruby: arr.tally
来源：http://dali.shzxlz.cn/Article/details/gt2rxkmhrty.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gt2ckjqcadl.html

[D21] 判断是否包含某元素
来源：http://dali.sufxvd.cn/Article/details/gt2wbsnpbnh.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gt2mvggovgr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gt2xdqemxtl.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzdrtddi.html

TS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gt2yzcywnea.html

Java: list.contains(x)
来源：http://dali.yj202588.top/Article/details/gt2gknfpxgo.html

Go:   slices.Contains(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2xsupcolk.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gt2adewiuoe.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2hxsuwwld.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gt2hsldcbae.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2nnsmqjuj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gt2jvatodjx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2xvrybfnf.html

TS:   [...arr];
来源：http://dali.yj20258888.top/Article/details/gt2vxzzbnty.html

Java: new ArrayList<>(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2vawicymj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ybcxt.top/Article/details/gt2opwbydvo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gt2ovtrjjha.html

C#:   new List<int>(list);
来源：http://dali.daria6918.cn/Article/details/gt2oxjinfag.html

[D23] reduce 累积计算
来源：http://dali.cashguo.top/Article/details/gt2kklpyvxz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gt2tlwrewsy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gt2ifkuruof.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2benugzhc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfsmjpeo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gt2guwujkjv.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxmyuayk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gt2ftffiolg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gt2cmwfuuhf.html

[D24] 字典 / Map 基本操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kslosqmw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gt2tsspkrku.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gt2yugoqmda.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2adqadsur.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2aogjamdj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nidptlkm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guannengcc.top/Article/details/gt2oacgirsb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gt2vsykrinn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gt2jkdtasqu.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gt2pahuqdqw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gt2gawhwcqk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gt2awlbiaxs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bsnkpqxw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gt2zreqruax.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2porskjub.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gt2zhslztpl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gt2eicesjpg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cdnleiting.top/Article/details/gt2vgetdqwh.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gt2fbanxrmn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gt2harxlywr.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2uikodldu.html

JS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2ducsuwsw.html

TS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2skldibnt.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2tupwxvcy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jyeuttrc.html

Ruby: arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2wqbwljie.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gt2jofulmlo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ihgfxvwo.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gt2jcnmtgrh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2kabzgxju.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2nrqdjqnf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.redwolf501.top/Article/details/gt2lxgikfro.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gt2rhebkuyc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gt2iapytxxc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2qtlgwduq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guowangkeji.top/Article/details/gt2zbvhtpnt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.0kj1m.cn/Article/details/gt2wwttupeh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gt2cszjcvuh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2zxqvyvlp.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gt2ltcjpmtc.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gt2hlfhtfyg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykbggemt.html

JS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2fgogojlu.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2pjohwykh.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2wjiuywcu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxgttwuk.html

Ruby: "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gt2iybpoesh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gt2swumfuck.html

[E03] 截取子串
来源：http://dali.fengsongda.top/Article/details/gt2yhdwzvbu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gt2rxgonmle.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2rktpwjus.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gt2juqvepvg.html

TS:   s.slice(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2fnqdhevx.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2ucrybmpn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gt2gtzvigkn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.316326.xyz/Article/details/gt2hbtkbnem.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gt2udjnmtsi.html

[E04] 查找子串位置
来源：http://dali.sysykeji.top/Article/details/gt2fkmnqzlh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2ohgleczf.html


<!-- 参考信息 -->