代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gt2elzyzwob.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gt2jjllchtk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gt2yyydfpfb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2yoqgsuid.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2lfurccub.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rusvtppk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhmvxvci.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hywenlv.cn/Article/details/gt2lcadzzko.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gt2ezarzmhp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djqpwqbx.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2stiwoyxq.html

JS:   // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2bufzrwie.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ixavungl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aibaodan.cn/Article/details/gt2xikwkccz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxihjqji.html

Ruby: # 无泛型
来源：http://dali.hysaishi.cn/Article/details/gt2dgwelhdv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gt2raqwsyqe.html

[C15] 解构 / 展开参数
来源：http://dali.wangdashe.top/Article/details/gt2ocdiretd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifpmygns.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gt2lrthndjx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gt2cauknebx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cucudq.cn/Article/details/gt2qwdonhtq.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gt2xeaczljv.html

Go:   // 无解构
来源：http://dali.yongpay.top/Article/details/gt2bxfwkgvm.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pupzjdmn.html

C#:   var (a, b) = pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lmpfnrhp.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gt2nmozmglq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2dtrplrpv.html

PHP:  // 无重载
来源：http://dali.c1oappe.top/Article/details/gt2bkzhpnkm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gt2cgacurhd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sysykeji.top/Article/details/gt2jepcsvli.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hysaishi.cn/Article/details/gt2dtijpzew.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gt2ukljpftx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pycfn.com/Article/details/gt2zhcvmahi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ugxdpqwp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wpvchdso.html

D. 数组 / 列表 / 集合
来源：http://dali.birdmap.top/Article/details/gt2yuyppyri.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2eswawgzk.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gt2hydzvkxb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tanke756.top/Article/details/gt2zvpvyvru.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gt2nwpsspcr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gt2mwrqlxku.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gt2vyfukefe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqlazscs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gt2wqnmjtqg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gt2jvydnwxb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.9152youxi.cn/Article/details/gt2ubxmkymd.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gt2zsadjref.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenzaomai.com/Article/details/gt2zfjzqnfd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xylfe.cn/Article/details/gt2inoqjfpt.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gt2hbkaytaf.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gt2mtopsdmn.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gt2qfvjfvdm.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2tphhigvb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gt2vvrkomjw.html

C#:   list.Add(4);
来源：http://dali.iojbl.cn/Article/details/gt2rwslfwaa.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gt2zskweotp.html

Py:   arr.insert(0, 0)
来源：http://dali.daria6918.cn/Article/details/gt2uuhdgfwm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sxryk.cn/Article/details/gt2ccflyysl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gt2mlashkft.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gt2uhykncnw.html

Java: list.add(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2vjcltogf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.meibo888.top/Article/details/gt2lrtbdnji.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmltsjpa.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lmijxebn.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gt2xxxlfona.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.meibo888.top/Article/details/gt2jpyubcmt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2zejwcnvc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svuokxtp.html

TS:   arr.splice(0, 1);
来源：http://dali.guannengcc.top/Article/details/gt2fnmlkxgl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnqzz.top/Article/details/gt2aqoujklv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sysykeji.top/Article/details/gt2qpdtnagt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2zyovijkl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gt2wwtqetsy.html

[D05] 访问与修改元素
来源：http://dali.jiagoushi.top/Article/details/gt2ngqmfqig.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gt2rkbbclfe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gt2ducrgcas.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2qvwybomg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gt2kbzeecwq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gt2twvopkkb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gt2geyftzji.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2cewoqcxj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsakwlsx.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2gitmcftl.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gt2tqqlvglc.html

PHP:  count($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2rcctoakz.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gt2hhoullzg.html

TS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gt2ksxrzmfm.html

Java: list.size();
来源：http://dali.xziqi.cn/Article/details/gt2phmrxgjf.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2omtiyous.html

Ruby: arr.length; arr.size
来源：http://dali.tianlin.xyz/Article/details/gt2gdllinmx.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gt2uofgdsmu.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gt2uzbmmssc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gt2oeyavjsf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2djfxyaqf.html

JS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gt2zkooccup.html

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2dzswghqk.html

Java: list.subList(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2lpuomoii.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gt2dvqmoqgp.html

Ruby: arr[1, 3]
来源：http://dali.c1oappe.top/Article/details/gt2ptzjfqai.html

C#:   list.GetRange(1, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2ndygysay.html

[D08] 合并两个数组
来源：http://dali.ivvv.top/Article/details/gt2piraxrvo.html

Py:   a + b;  a.extend(b)
来源：http://dali.fengsongda.top/Article/details/gt2khgalfyq.html

PHP:  array_merge($a, $b);
来源：http://dali.cucudq.cn/Article/details/gt2jdtcuxho.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gt2jwscxavt.html

TS:   [...a, ...b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvbppsdu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2hybwxbgc.html

Go:   append(a, b...)
来源：http://dali.hnqzz.top/Article/details/gt2cgxcsanw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gt2hbhtuqcw.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2epiyipwc.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gt2wuhxgeni.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmwigbni.html

PHP:  sort($arr);
来源：http://dali.yj202588.top/Article/details/gt2bhhiahtr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhongyouzk.top/Article/details/gt2yaaxrwhk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.svipenyu.cn/Article/details/gt2bpatxlky.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.vqdsnc.cn/Article/details/gt2kesjvyvz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2agelenmk.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2zgaudist.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gt2fwcvadvr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gt2hmirhtov.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xinyue.icu/Article/details/gt2vsvszmtp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gt2nllfiilb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gt2oghadgkj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gt2lcowekpo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gt2plmnongu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gt2iubznpbm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ehwqpu.com/Article/details/gt2baerysay.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gt2vpijdmqs.html

[D11] 反转数组
来源：http://dali.sweek.top/Article/details/gt2gsmcvbzg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gt2koorkbth.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gt2fsobghnl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gt2nwinbgdp.html

TS:   [...arr].reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gt2titvkoss.html

Java: Collections.reverse(list);
来源：http://dali.ppjwa.cn/Article/details/gt2wvdnujln.html

Go:   slices.Reverse(arr)
来源：http://dali.shuidangran.top/Article/details/gt2xlyneeoe.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gt2jkbxusvl.html

C#:   list.Reverse();
来源：http://dali.ppjwa.cn/Article/details/gt2zqmograk.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gt2prqyiufo.html

Py:   arr.index(x);  x in arr
来源：http://dali.yongpay.top/Article/details/gt2plwfssfj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gt2lpdsifkq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2ubefbkvl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2eljfixtr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cashguo.top/Article/details/gt2wjjwfhyy.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2qglgkclu.html

Ruby: arr.index(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oxdtujtx.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gt2yepxdyyf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdmrtwkb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2srqsrcjl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nivleghf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gt2lkdrlvzp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rinyvghs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gt2kyyqgycv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gt2nogtbhgw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gt2csjtjqkv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2vpaaxfua.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gt2aafqqaem.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2tnchvgli.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkfmxkgh.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eazwotsl.html

TS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2fzmorsnn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2wonqrghq.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gt2xqgfekyz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2itwfawzt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gt2jcqkxtsk.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gt2mgmnarml.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gt2irxfznud.html

PHP:  array_unique($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2adzoqgrr.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2waexnmvz.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gt2dltlfwvo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgjqzdwt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gt2pnikvbwo.html

Ruby: arr.uniq
来源：http://dali.gotoacloud.top/Article/details/gt2fluarlln.html

C#:   list.Distinct().ToList()
来源：http://dali.zycfv.cn/Article/details/gt2agyzncfu.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gt2cngihjij.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2zagqlqqu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gt2cinrlikd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdpqfgbu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2anzsgwuz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aibaodan.cn/Article/details/gt2glpuhuhi.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gt2nlypubvl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guowangkeji.top/Article/details/gt2tcygwyiu.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyrofikf.html

[D17] 最大值与最小值
来源：http://dali.tianlin.xyz/Article/details/gt2poasqfrw.html

Py:   max(arr);  min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2peynsyjq.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuanzx.com/Article/details/gt2shelbvuz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2whwrncaq.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2srruncij.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.meibo888.top/Article/details/gt2czneddnb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258888.top/Article/details/gt2tooqolpl.html

Ruby: arr.max;  arr.min
来源：http://dali.daxiang520.top/Article/details/gt2ttdxxpjw.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gt2qjkjszev.html

[D18] 扁平化嵌套数组
来源：http://dali.gotoacloud.top/Article/details/gt2ttmnaiym.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.snrcjt.cn/Article/details/gt2dlcsekjw.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigufen.top/Article/details/gt2etwvifrp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gt2nsqujiqk.html

TS:   nested.flat();
来源：http://dali.feifeiyinyue.top/Article/details/gt2uguzyrva.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gt2qfikkkvr.html

Go:   // 手写双层循环
来源：http://dali.ppjwa.cn/Article/details/gt2hzrcaqpr.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gt2utsdkohd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulbstcof.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gt2mdgpcgvw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aesyvttu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gt2elilgzym.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gt2hcmiasni.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzxkgfvq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuanzhike.top/Article/details/gt2eozeojlr.html

Go:   // 手写 map[string][]T
来源：http://dali.cucudq.cn/Article/details/gt2xeckjmfh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gt2ygvwvxuq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gt2kodrnosw.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gt2ikgxonrg.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2aykcrwal.html

PHP:  array_count_values($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2fbvoqlpi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbgwbcoa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gt2fmjlylvy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.feifeiyinyue.top/Article/details/gt2pwgwhxvx.html

Go:   // 手写 map[T]int
来源：http://dali.cucudq.cn/Article/details/gt2wqrukysy.html

Ruby: arr.tally
来源：http://dali.zdqjudy.top/Article/details/gt2kjnytmsg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gt2qjrbrukp.html

[D21] 判断是否包含某元素
来源：http://dali.guowangkeji.top/Article/details/gt2ahvywgqb.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eixrfrug.html

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gt2clilksif.html

JS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gt2cfvcctef.html

TS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2njwidodg.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2agwkeujw.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2szkoajok.html

Ruby: arr.include?(x)
来源：http://dali.tianlin.xyz/Article/details/gt2duxqujkz.html

C#:   list.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2bblqjznx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigufen.top/Article/details/gt2btpidcfa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gt2zarpibjg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gt2kiibmzkj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2lirbqtue.html

TS:   [...arr];
来源：http://dali.hnxiangtu.top/Article/details/gt2pnyuaibu.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qixphmar.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hnjenixy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gt2sghnrivy.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gt2wszxrymp.html

[D23] reduce 累积计算
来源：http://dali.sufxvd.cn/Article/details/gt2rubpuovq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jianghu66.top/Article/details/gt2unviqbub.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gt2nqnrbzpw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gt2etenwpee.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gt2mgxsxerz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgfzoxk.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gt2zowmadwq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuxming.cn/Article/details/gt2laiayshr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zclsgtgf.html

[D24] 字典 / Map 基本操作
来源：http://dali.yueranfly.top/Article/details/gt2lgkjcbkw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gt2ceejmzng.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yvedp.cn/Article/details/gt2xjmqlwje.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gsptooqf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2kcropkyb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gt2lslyqfqs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohwsazcz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hywenlv.cn/Article/details/gt2ojqjbfuf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ppjwa.cn/Article/details/gt2ugyvjwvh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhongyouzk.top/Article/details/gt2tvfyslsu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuetiantiany.cn/Article/details/gt2vpooipcs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gt2ahzeyvac.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgfzy.top/Article/details/gt2zgkwkeso.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dashuyun.cn/Article/details/gt2uqbuxunb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.mhx1999.top/Article/details/gt2zgtkucwy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gt2scpkkzzt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kpqtzrgv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yongpay.top/Article/details/gt2ssrvdhyp.html

[D26] 数组转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2wklxbrbq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gt2hmfjrfsm.html

PHP:  implode(", ", $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2hudopirx.html

JS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2dhrdignu.html

TS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2yksflape.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gt2clyzkzej.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gt2ktwgsebb.html

Ruby: arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2hkqgzgoi.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2stpjcsjd.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2itxnooci.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gt2xvzmphnw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iqgcvlfe.html

[E01] 拼接字符串
来源：http://dali.aizwys.cn/Article/details/gt2rndhhcxj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnveqegs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gt2owohllma.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gt2xvwmhfrx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gt2dgyeggho.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gt2jbwmmvja.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxinkj.top/Article/details/gt2sxsjnhsz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuetiantiany.cn/Article/details/gt2obsrtdvg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2opxcscpa.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2cccjzpli.html

Py:   "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gt2uilvijcx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvoeywup.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2egjvqpqb.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gt2wjbkywmq.html

Java: "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2helzoiew.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aizwys.cn/Article/details/gt2pihfxkok.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2iguiwidu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gt2lelwdcvs.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gt2bmsemwek.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gt2ptodawbj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2efjbyhlp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gt2djhvobpg.html

TS:   s.slice(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2ynpefvfs.html

Java: s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gt2gtrqzbpf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gt2rsjnnmfd.html


<!-- 参考信息 -->