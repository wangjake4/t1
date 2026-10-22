代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gbsjrtba.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gt2xdbjqidw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgutaxmw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gt2lnaewfvf.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gt2qygzlncc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pycfn.com/Article/details/gt2ixzcsidx.html

PHP:  // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2ghuhdpac.html

JS:   // 无泛型
来源：http://dali.bjfxy.top/Article/details/gt2vxlxujgl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sufxvd.cn/Article/details/gt2mhsiqymy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gt2amupjzhs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gt2wcbaeimg.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2fspgfsnt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gt2yhlkhxwp.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gt2fredbcpn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.svipenyu.cn/Article/details/gt2pgebhjuy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gt2tnjgevhr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gt2adqlwlgq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2akctbguo.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2uihyybtp.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gt2opiscypb.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gt2tbzivspv.html

C#:   var (a, b) = pair;
来源：http://dali.jqgufenzy.top/Article/details/gt2muwdtodk.html

[C16] 函数 / 方法重载
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayukdchp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gt2qbmzkptc.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gt2kdnuyhlf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gt2qunolgri.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vujtcdwl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2rbpunprk.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gt2lxdtaqba.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daria6918.cn/Article/details/gt2edsmqbok.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gt2pifixfel.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2evnrbzpy.html

D. 数组 / 列表 / 集合
来源：http://dali.chenzaomai.com/Article/details/gt2oupgawcd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2coymgldi.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rkousgwq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctlemuzw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gogol.net.cn/Article/details/gt2kllbfczu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2gadagiqb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigfzy.top/Article/details/gt2kqrmtxql.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hysaishi.cn/Article/details/gt2gkfzrtnj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xziqi.cn/Article/details/gt2drflkpdx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fzhhl.top/Article/details/gt2fzbbyyqh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gt2vyranfnz.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gt2iscsnobj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.9152youxi.cn/Article/details/gt2dmmymsle.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gt2ztmxsjxt.html

JS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gt2oojbworo.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gt2yqezgern.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gt2vhlzksil.html

Go:   arr = append(arr, 4)
来源：http://dali.tian-w.cn/Article/details/gt2qjoezmki.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sufxvd.cn/Article/details/gt2wncpztzk.html

C#:   list.Add(4);
来源：http://dali.chenlongwang.top/Article/details/gt2dtukdkje.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gt2qrnbhjcw.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gt2gqewtsdx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cashguo.top/Article/details/gt2cehrevuc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jianghu66.top/Article/details/gt2gjdstmxn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2gfddtmlx.html

Java: list.add(0, 0);
来源：http://dali.yongpay.top/Article/details/gt2kdybxxzs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.c1oappe.top/Article/details/gt2pbuvmhpj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dlhrtzec.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjbzfihi.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gt2dnwojbja.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gt2lttgjvyy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gt2xejxygve.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jyoumei.cn/Article/details/gt2vjutgaka.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gt2ejpuutay.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2fxubvfbr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gt2cwirzcmf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hywenlv.cn/Article/details/gt2wpeqwzlm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigfzy.top/Article/details/gt2svoweoqg.html

[D05] 访问与修改元素
来源：http://dali.cheryme.top/Article/details/gt2nejlzrxc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gt2yjxlchbc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gt2rdgditsk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2tzdvnbpe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sweek.top/Article/details/gt2rkupqapg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gt2lrzayicb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2hnmxqtxm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gt2kvsvcaic.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2amthsmxv.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gt2qlbvwnrr.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbdbzkki.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzrkjhyf.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqbcmnix.html

TS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gt2gyzmntqr.html

Java: list.size();
来源：http://dali.jqgfzy.top/Article/details/gt2wvivesik.html

Go:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdvtzwwa.html

Ruby: arr.length; arr.size
来源：http://dali.0kj1m.cn/Article/details/gt2lmdbrqms.html

C#:   list.Count;
来源：http://dali.guowangkeji.top/Article/details/gt2slwkhosk.html

[D07] 切片 / 取子数组
来源：http://dali.9152youxi.cn/Article/details/gt2koxfdvfn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj202588.top/Article/details/gt2lnvanljv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guannengcc.top/Article/details/gt2kzcppibn.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2lufblvmh.html

TS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2ewimvcho.html

Java: list.subList(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gt2yszhjqyq.html

Go:   arr[1:4]
来源：http://dali.shuidangran.top/Article/details/gt2qbidurvw.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2djeeymxb.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2xoaxubqn.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2xoywjxzy.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwkikuyn.html

PHP:  array_merge($a, $b);
来源：http://dali.pycfn.com/Article/details/gt2wyoesdih.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gt2vwwfaiab.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gt2pbfggepl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2ohqrazbb.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gt2rztlutsl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxinkj.top/Article/details/gt2uhcdacbi.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2kryryqlo.html

[D09] 排序（升序）
来源：http://dali.yueranfly.top/Article/details/gt2fasxmqqd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrrrmswq.html

PHP:  sort($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqgycwjc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gt2zpazuuyv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gt2uqnwyoiu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gt2ruepqljf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gt2elpmptct.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gt2koxfasux.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2amdpvmna.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gt2wjtwtgey.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wimeijrk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkhaxprf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gt2jschtudc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gt2cbnulvaf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.andypj.xyz/Article/details/gt2hpktmezt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gt2tfpkosmy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gt2lvhcquxf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gt2dmpggvvn.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gt2ybrrpmma.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.birdmap.top/Article/details/gt2taoabsst.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gt2wlvkrycq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gt2mbejwqxg.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gt2lgosketx.html

Java: Collections.reverse(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdjgrmef.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gt2tdrhbgrn.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gt2joozjfwi.html

C#:   list.Reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2rlkdknmh.html

[D12] 查找元素下标
来源：http://dali.ydzc1.top/Article/details/gt2ojiqsbno.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygtsntzy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gt2mzhtpveu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2vetzryul.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2fndibicj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gt2vjumutyy.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxcmprk.html

Ruby: arr.index(x)
来源：http://dali.gotoacloud.top/Article/details/gt2eicdxpzv.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tuarmwgm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gt2yadcpyth.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gt2ctxnbppu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cheryme.top/Article/details/gt2zahtdoqw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubvpkrnk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gt2zauvzypc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2npsezhrc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gt2fudvodgv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilahzmxo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2mdibuthl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqapxfjg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2bsrwjnvr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gt2kwrqshao.html

JS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2plnbjsdq.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2hzobismh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2wjgydjfe.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gt2uowbnums.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gt2lhztjscv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gt2qhqgmajx.html

[D15] 去重
来源：http://dali.0kj1m.cn/Article/details/gt2dtklulom.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gt2usydbqrj.html

PHP:  array_unique($arr);
来源：http://dali.yj202588.top/Article/details/gt2nyuzoyxn.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gt2sswhdigz.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gt2xzvdrjov.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gt2lybhjkca.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gt2pukwmylu.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gt2zklssqnz.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2llkslnuo.html

[D16] 求和与平均值
来源：http://dali.jlsjyb.cn/Article/details/gt2qsdsbyhr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oyzsraic.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2dxdwrhdx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gt2ekpqunvq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2egwtewkc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gt2uyiatbmn.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gt2rpkurzvk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.iojbl.cn/Article/details/gt2qcfpnvyb.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gt2cifjfojw.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gt2lgvtrjkr.html

Py:   max(arr);  min(arr)
来源：http://dali.ybcxt.top/Article/details/gt2khsxcwfo.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258888.top/Article/details/gt2rbtxtuub.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hoidelkl.html

TS:   Math.max(...arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2axybmhfr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yvedp.cn/Article/details/gt2wugxaimp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2chensxrd.html

Ruby: arr.max;  arr.min
来源：http://dali.aibaodan.cn/Article/details/gt2ckbffhsa.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgufenzy.top/Article/details/gt2onnjaqah.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gt2eyeqxzkz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj202588.top/Article/details/gt2rsabmzsg.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2surlbqvu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jianghu66.top/Article/details/gt2kdgdacvu.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gt2mrajswfk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2ghtujasw.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gt2xjonnbob.html

Ruby: nested.flatten
来源：http://dali.gotoacloud.top/Article/details/gt2uppfpvrk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2pbnyaptg.html

[D19] 按字段分组
来源：http://dali.wangdashe.top/Article/details/gt2cpbvguas.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ucketqfe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nwbrower.top/Article/details/gt2akxovcoj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sysykeji.top/Article/details/gt2lazqjpxm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gt2pxkxofkt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gt2lyjkgjwt.html

Go:   // 手写 map[string][]T
来源：http://dali.pengpengdd.cyou/Article/details/gt2wyifyfoo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shzxlz.cn/Article/details/gt2rttqnqvj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tanke756.top/Article/details/gt2ngarzhbh.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gt2zazyccin.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gt2nbarsfah.html

PHP:  array_count_values($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2pinfiluf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gt2qvgaexzb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gt2emzfonqc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gt2jsotuoov.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gt2vwbohayi.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtbsoxfb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gt2rkgivhsh.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gt2ocjafxwp.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gt2mzhuvdvj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gt2dyqzvann.html

JS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gt2ctsztbhu.html

TS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gt2yclswgnb.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2khwuwqgg.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2lwivalsw.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2wshpvlto.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2niytvoiv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigufen.top/Article/details/gt2uxpjcmlt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2cndhgekk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqsfcmcu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2bfgkgsfy.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gt2aitrfise.html

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2jsnaifty.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xylfe.cn/Article/details/gt2avaofrav.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dianchejie.cn/Article/details/gt2adiuapwv.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gt2oepwbwlb.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gt2wmjespyx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2fucxbtma.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuanzx.com/Article/details/gt2auggfyns.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2nyraysqd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2utxrdrqa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gt2yajsmjor.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gt2vpzifcqn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gt2pigbmcjd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gt2bkyqxgnh.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gt2rdachtem.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gt2xitoxedw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gt2xtfvgynz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gt2ibonasll.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2kiezeatn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gt2uhekmuoi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gt2rxyekudy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hszheozk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gt2gadqjbfv.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gt2bkhyfhac.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxgizoap.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gt2yndypych.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tian-w.cn/Article/details/gt2dtcmjqml.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gt2mqwwtyos.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fengsongda.top/Article/details/gt2mbcuwhxm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gt2egstjxgs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258888.top/Article/details/gt2icimvmfl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fengsongda.top/Article/details/gt2apyejwts.html

[D26] 数组转字符串
来源：http://dali.316326.xyz/Article/details/gt2gpzhkbvr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cheryme.top/Article/details/gt2zypsgnlr.html

PHP:  implode(", ", $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2elljuqqa.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2xhqlhnjd.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2yiosdxtn.html

Java: String.join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxmvmqnb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocathtso.html

Ruby: arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gt2gqgzfumv.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gt2mleojkqc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2seckhtcb.html

E. 字符串处理
来源：http://dali.redwolf501.top/Article/details/gt2xbxncyoi.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ceqfuhsm.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gt2vrswnxgi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.kuanghao11.cn/Article/details/gt2ysxxiezf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gt2kxsntxhn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gt2zvhezuau.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xivqwnsm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgfzy.top/Article/details/gt2ukhcqnqb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xylfe.cn/Article/details/gt2zvpaabfi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gt2mpbwdgnd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2itenpqsh.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gt2jrslcgkw.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gt2nmkxeeht.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cucudq.cn/Article/details/gt2hsjbwitn.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gt2vvvizuqm.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2wkwflnlo.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2ukpcxnus.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hysaishi.cn/Article/details/gt2uqmhuows.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2kehrhunq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gt2dwselzty.html

[E03] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gt2lzyppyuw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gt2sfdsxpoj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2sklbrjjz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2pvroxsxp.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gt2utdytdyb.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2shdfcyuc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhengqikj.top/Article/details/gt2vwvakjuo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.iojbl.cn/Article/details/gt2hxxgjoev.html

C#:   s.Substring(1, 3)
来源：http://dali.shzxlz.cn/Article/details/gt2hlpkgstk.html

[E04] 查找子串位置
来源：http://dali.yj20258888.top/Article/details/gt2jvbepdwt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gzhubu.top/Article/details/gt2ubymqufm.html


<!-- 参考信息 -->