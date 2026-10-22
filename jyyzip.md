代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.yueranfly.top/Article/details/gt2hqzvkodx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gt2kkapbcug.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gt2hwfrbeab.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gt2zkwbrbzs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mboatqxa.html

Ruby: -> { puts "run" }.call
来源：http://dali.tianlin.xyz/Article/details/gt2elgjoyvv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nwbrower.top/Article/details/gt2uttbrszv.html

[C13] 类型声明 / 类型注解
来源：http://dali.ppjwa.cn/Article/details/gt2admycdnv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywcpactz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gt2nnzcttbk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fzhhl.top/Article/details/gt2yirjklzv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2vdfcmoxe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2xqovlyfl.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gt2ndrnacvc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jyoumei.cn/Article/details/gt2jzxsfuaa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gt2qlcjwnlf.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgjjgdoi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gt2qyetspmj.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2nimfwtxz.html

JS:   // 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2hvpjpcvo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.kuanghao11.cn/Article/details/gt2gosuqvap.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2bshngqho.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuanzhike.top/Article/details/gt2iwayusrm.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gt2sowibvkw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gt2bmkkafhw.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gt2qogebikf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gt2qrhjnlno.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gt2htosgnru.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2oyetacyq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xziqi.cn/Article/details/gt2zygvjgva.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gt2vfmdonzn.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gt2olwprdej.html

Ruby: a, b = pair
来源：http://dali.aizwys.cn/Article/details/gt2bwyokdmv.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gt2tinlknkd.html

[C16] 函数 / 方法重载
来源：http://dali.aizwys.cn/Article/details/gt2yddrzrop.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gt2jjcwzhdg.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gt2ekrlpzep.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sysykeji.top/Article/details/gt2hopuzrhz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gt2nkdniccq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2lknjsnpa.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gt2mvziygso.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gt2ipbzawry.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gt2bqsniiie.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2afrtxvut.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gt2vopivszp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ymwtbyfb.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gt2tpsyabkj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gt2rdissxts.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gt2rmhjgrjk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gt2crbywndz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlblbmzv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gotoacloud.top/Article/details/gt2gopeqalf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fzhhl.top/Article/details/gt2tiuxeoup.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gt2kfstrprb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahlacqaz.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gt2yobtnyuf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gt2yixltcrj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tianlin.xyz/Article/details/gt2vgvygpok.html

JS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gt2bjwagsws.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2qghdamun.html

Java: list.add(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2ntpysuvd.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gt2sjagrnrm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fzhhl.top/Article/details/gt2rzdinvqc.html

C#:   list.Add(4);
来源：http://dali.shuidangran.top/Article/details/gt2mremuxkj.html

[D03] 在指定位置插入元素
来源：http://dali.9152youxi.cn/Article/details/gt2isklwzvy.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gt2oapwdrri.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cashguo.top/Article/details/gt2lqwilkiy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gt2hpwujkxm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2vrmkawmy.html

Java: list.add(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2nnicqnkb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gt2trfifeuq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gt2vqourhgp.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2ijlsjici.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gt2biqldzeb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.redwolf501.top/Article/details/gt2sasgxtmi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daxiang520.top/Article/details/gt2urhsrpfl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.kuanghao11.cn/Article/details/gt2oikebcft.html

TS:   arr.splice(0, 1);
来源：http://dali.xinyue.icu/Article/details/gt2dugcjyve.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuxming.cn/Article/details/gt2znrrvikh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gt2avmutlav.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.9152youxi.cn/Article/details/gt2hldjklwi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuanzx.com/Article/details/gt2aukxfuyt.html

[D05] 访问与修改元素
来源：http://dali.jlsjyb.cn/Article/details/gt2ysyabtpv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2rrodgwyl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2ljavmxgf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2llretlfa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gt2bwpuwsqe.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjzvsdma.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjuehjyd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gt2fbzydxad.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2rhaijfhw.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gt2tpssmsfq.html

Py:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gt2ibxnafpq.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2ltqhnfbu.html

JS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2ljbeetjr.html

TS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gt2qxaxdbjs.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gt2etmjnknh.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gt2yoakvxwj.html

Ruby: arr.length; arr.size
来源：http://dali.shuidangran.top/Article/details/gt2mbiskqoc.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gt2ebbasbmn.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gt2aomnkgou.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gt2oueobmlr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258.top/Article/details/gt2tioieump.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2zoluimed.html

TS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gt2bykcetha.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gt2vlblbjwj.html

Go:   arr[1:4]
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwdtmtcq.html

Ruby: arr[1, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmxktppo.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gt2apvqsjbd.html

[D08] 合并两个数组
来源：http://dali.bjfxy.top/Article/details/gt2hodliopw.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2vtbiwfab.html

PHP:  array_merge($a, $b);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbcvaghn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sufxvd.cn/Article/details/gt2iigjxhnv.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2elcwoett.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2ufdbwzgc.html

Go:   append(a, b...)
来源：http://dali.haohaochexian.top/Article/details/gt2ykmrjovd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daria6918.cn/Article/details/gt2zvgfgsur.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjmwnpes.html

[D09] 排序（升序）
来源：http://dali.chenzaomai.com/Article/details/gt2kxqavuwo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gt2nfwwbefu.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhlbzmzn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gt2xpxygedg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gt2mvnhopoi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ybcxt.top/Article/details/gt2bzkcwvyc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sskxiuuc.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gt2irzlxulz.html

C#:   list.Sort();
来源：http://dali.sweek.top/Article/details/gt2zsznqkmy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gt2phvulsxm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gt2jitnencq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2teobgriq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2wjzsgups.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gt2jpdvfnmj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gt2blccerpn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmqkjzwe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daria6918.cn/Article/details/gt2pijmfahp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gt2mosprsxw.html

[D11] 反转数组
来源：http://dali.yuanzhike.top/Article/details/gt2nxgwpfwm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gt2acbwjptm.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gt2zyxoxnbd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxrnzrkb.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gt2gvahtaos.html

Java: Collections.reverse(list);
来源：http://dali.chenzaomai.com/Article/details/gt2vvbcyndm.html

Go:   slices.Reverse(arr)
来源：http://dali.c1oappe.top/Article/details/gt2zfizhfrk.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2nmvpcsjr.html

C#:   list.Reverse();
来源：http://dali.316326.xyz/Article/details/gt2gekjdagx.html

[D12] 查找元素下标
来源：http://dali.316326.xyz/Article/details/gt2gtrkiklp.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gt2nkkrritd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2svilbnjm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2uxqzuqzz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulamaqrj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xinyue.icu/Article/details/gt2rmpkpxgu.html

Go:   slices.Index(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsxwuddh.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfadecwg.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gt2gwfmtueo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gt2hktukgjj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2oggfrrcd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gt2exokhjlq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2bolymria.html

TS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gt2vqlosvnu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmrivjpn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shzxlz.cn/Article/details/gt2voxiowxp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbkqsadx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2jwljmmel.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gt2hbyyfxbe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ppjwa.cn/Article/details/gt2edccblcn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2dhofnmgg.html

JS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gt2jgvhbscn.html

TS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2yeogdjon.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gt2ecuboxop.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gt2iuhrmipg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2txiaawjt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gt2uikqrdps.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gt2ygdxcixi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gt2luqvltvr.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2iachlwdl.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gt2fczgimhz.html

TS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2jeqxcsnb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhengqikj.top/Article/details/gt2hvfysauj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gt2hpsaejdm.html

Ruby: arr.uniq
来源：http://dali.xziqi.cn/Article/details/gt2wvuvsbgv.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gt2dxwzujru.html

[D16] 求和与平均值
来源：http://dali.gotoacloud.top/Article/details/gt2fzpoeqne.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbnoyamw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gt2awnksxmo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gt2mphauzri.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2pcwbxlnd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gt2xcwegtwc.html

Go:   // 手写循环累加
来源：http://dali.fzhhl.top/Article/details/gt2akczdkya.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gt2biavmmxe.html

C#:   list.Sum();  list.Average()
来源：http://dali.daxiang520.top/Article/details/gt2ndeuuldj.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gt2xzpyufde.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjuhhhtz.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gt2xvwtrkla.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2bfudufjv.html

TS:   Math.max(...arr);
来源：http://dali.nwbrower.top/Article/details/gt2gyenwpio.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gt2iuqqaslv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2suvnfkeo.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gt2jhhldxhi.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gt2tmbxvjbp.html

[D18] 扁平化嵌套数组
来源：http://dali.yonumen.top/Article/details/gt2hstydyjb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gt2xhejzikd.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzxhzqi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gt2tvljzuxs.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gt2xkwjdbtl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2dvxmsfki.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gt2afdxekjs.html

Ruby: nested.flatten
来源：http://dali.xinyue.icu/Article/details/gt2nhlymqqg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2zsfrlpca.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejhzmnmo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnqzz.top/Article/details/gt2rowrhnwb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.kuanghao11.cn/Article/details/gt2fayvqxjc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gt2rtinmjph.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gt2kegrryci.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tian-w.cn/Article/details/gt2ipfbwmdm.html

Go:   // 手写 map[string][]T
来源：http://dali.andypj.xyz/Article/details/gt2xuuxwgab.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.smart0.xyz/Article/details/gt2mfzhwxoj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gt2qgztuoth.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gt2tqhrofwr.html

Py:   Counter(arr)
来源：http://dali.yj20258.top/Article/details/gt2bdczqvsb.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gt2qavwbovq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2czfbuycp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gt2ofmadzxz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gt2iielxrfv.html

Go:   // 手写 map[T]int
来源：http://dali.hnqzz.top/Article/details/gt2rhnkpowl.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gt2rbqtaohw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shzxlz.cn/Article/details/gt2xwynhfyu.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gt2onmgmesl.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gt2jmwflafc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hammf.cn/Article/details/gt2xyuqaegb.html

JS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gt2zwqetzbf.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2lnbxhito.html

Java: list.contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2pzrzyaij.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2gqpamnip.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gt2gqjdfobk.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2uwkktxhz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gt2paugdafe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xziqi.cn/Article/details/gt2jsixnxjz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhoulong.xyz/Article/details/gt2ecgisloq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2wtvndwaw.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcfbcnj.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gt2jnrgeopp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gt2veezqjia.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gt2gbxcehqy.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gt2rxiktuih.html

[D23] reduce 累积计算
来源：http://dali.dianchejie.cn/Article/details/gt2aabaxhke.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gt2ckruvfew.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2xuaatbdl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2zsonsxsr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2sopaxhvj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gt2zlkcuccb.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2uiyodhch.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gt2byjsctmd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gt2keactyik.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gt2afrpzsdh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shuidangran.top/Article/details/gt2kpyzhqby.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2wkwhjuxp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2zogjwoqn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2esjrybsm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gt2qflpvszs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hywenlv.cn/Article/details/gt2tszmmdlu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nwbrower.top/Article/details/gt2zvmgrhwg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gt2gljgnsbj.html

[D25] Set 集合去重与交并差
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftiykpjg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dianchejie.cn/Article/details/gt2kmzvlfrh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gt2mfixtuuw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.bjfxy.top/Article/details/gt2tdazgerd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gt2zditqwjr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shzxlz.cn/Article/details/gt2gwpwnerv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gzhubu.top/Article/details/gt2ziwyytvj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gt2uqgiuqrb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lwbusktm.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gt2dvczdvyx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gt2upzegidi.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gt2rjqbyrfb.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2jyzhgzgn.html

TS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2cwvwvprg.html

Java: String.join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gt2xocnqqjj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gt2hzgwgizf.html

Ruby: arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gt2dvvkzatt.html

C#:   string.Join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gt2ncrmorpb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2euvpbfqc.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gt2pizogjup.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2gtzpnrgd.html

[E01] 拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gt2hzcpndtf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gt2csludqpq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xziqi.cn/Article/details/gt2zarxuqrc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gt2claekqos.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2jgfagnfg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gt2ksdymozj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.mhx1999.top/Article/details/gt2enfoztiu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.kuanghao11.cn/Article/details/gt2xnnaween.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajjxvtyt.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2jtvhkxqj.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gt2dqmkwnlp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gt2cxrlhllu.html

JS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gt2tjxfmisd.html

TS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2uodnfbxv.html

Java: "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2gkkooilc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenlongwang.top/Article/details/gt2lyawovgc.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gt2swcrkxen.html


<!-- 参考信息 -->