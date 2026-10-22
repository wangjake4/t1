代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gtdempttpn.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gtkljydhau.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtcvcescab.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangdashe.top/Article/details/gtzrmtvhec.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gtwegdrmcc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtqneyfsmr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.redwolf501.top/Article/details/gtoneyikig.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtlwlpjnjc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtiwhtyhcm.html

Go:   func add(a, b int) int
来源：http://dali.jyoumei.cn/Article/details/gtverdifar.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtedbrbfjj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtscqdtfta.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gtydqfhpsr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gogol.net.cn/Article/details/gthqyipskb.html

PHP:  // 无泛型
来源：http://dali.xinyue.icu/Article/details/gtbzvgtmcj.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gtweqerukv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gtryqrbaql.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmcwwgns.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.quarkkingdee.top/Article/details/gtrudglqot.html

Ruby: # 无泛型
来源：http://dali.birdmap.top/Article/details/gtwjoosrwc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gtzhbeyswz.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhpoxxlk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijmrzlpa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtfosphvxv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtaisfhofr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gtumgcjwuv.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknglbnmw.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gtmtqrgfft.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gtyzecxstf.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gtxozwanan.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gtluzzpwaj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gttkhdrbhi.html

PHP:  // 无重载
来源：http://dali.hfpthk.cn/Article/details/gtaaeitcdy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhzwtzdp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dianchejie.cn/Article/details/gteanokduq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ydzc1.top/Article/details/gtqlqehzbv.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gtvqomwxsa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrmjpgsk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guowangkeji.top/Article/details/gtqakrxbnd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcwannwgn.html

D. 数组 / 列表 / 集合
来源：http://dali.jyoumei.cn/Article/details/gtxaugzyia.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtsphoqesy.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gtkqbzjovi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuffnhoy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gtjuuakzmi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jianghu66.top/Article/details/gtvqbnuysx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxhmopbr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtouwtorpn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gtpmvlzzbg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gtelhsyruj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gtbxxlfcxn.html

[D02] 追加元素到末尾
来源：http://dali.pycfn.com/Article/details/gtyvyiryup.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dashuyun.cn/Article/details/gtemnevemg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphalstwk.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtnbfattuk.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtqhauibnn.html

Java: list.add(4);
来源：http://dali.fengsongda.top/Article/details/gtqnqgmojq.html

Go:   arr = append(arr, 4)
来源：http://dali.316326.xyz/Article/details/gtinvidyvs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxuanxn.top/Article/details/gtntpffmuk.html

C#:   list.Add(4);
来源：http://dali.zhoulong.xyz/Article/details/gtdsfxsnot.html

[D03] 在指定位置插入元素
来源：http://dali.zhiwuduotai.top/Article/details/gtlnncludi.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpxqczii.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.vqdsnc.cn/Article/details/gtyyxqrivp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hysaishi.cn/Article/details/gtfmlwfmjw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtruefijed.html

Java: list.add(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtmcjfppua.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlyqkbrr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gtzmjbunai.html

C#:   list.Insert(0, 0);
来源：http://dali.cashguo.top/Article/details/gtafwvmywc.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtittzmqur.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gtwzirnxwx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gtktbgolzh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gtdeemxcek.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gtcfepzdgu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuanzx.com/Article/details/gtkrtnjwxl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gtqzhcxynf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gtvqwshlyo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gtrdtgvlyb.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gtpsqurlrh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtvgryqmjg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gthacyzydv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtuztohcic.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gtajippbrh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gtestmxgvo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtvznxprjl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtvbzmnzpm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtaybrgvoc.html

[D06] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtzkebmumu.html

Py:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuoxfwbwo.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gtvsuurgoj.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gttfkbatwi.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtvbvljdkv.html

Java: list.size();
来源：http://dali.yanxiufei.cn/Article/details/gttechryyg.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtwypcksoe.html

Ruby: arr.length; arr.size
来源：http://dali.yueranfly.top/Article/details/gtaotvbxoz.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gtuciexmbw.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gtymsegaci.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.vqdsnc.cn/Article/details/gtnevqndhj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtennjdwme.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtkjyotetk.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtyqnlknux.html

Java: list.subList(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtlrjzdkfh.html

Go:   arr[1:4]
来源：http://dali.sufxvd.cn/Article/details/gtxtzstfyd.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtqoesygcr.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmdgkixo.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gtzlcsvkci.html

Py:   a + b;  a.extend(b)
来源：http://dali.jyoumei.cn/Article/details/gtoqslvsku.html

PHP:  array_merge($a, $b);
来源：http://dali.shangyingyoupin.top/Article/details/gtodxyzlii.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gtvghtgril.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gtynxuyhoh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gtmffcxoni.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gtwibvwqrv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gtlsyvnxyw.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gturatdmzp.html

[D09] 排序（升序）
来源：http://dali.zdqjudy.top/Article/details/gtrhctmoai.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtwutytdtr.html

PHP:  sort($arr);
来源：http://dali.yueranfly.top/Article/details/gtrdnsqrio.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ybcxt.top/Article/details/gtupipbeon.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yanxiufei.cn/Article/details/gtzpzjgpma.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.vqdsnc.cn/Article/details/gthjhcxeey.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynkdjbvh.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtkizfrdxi.html

C#:   list.Sort();
来源：http://dali.nanxuanxn.top/Article/details/gtebgnlyei.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jianghu66.top/Article/details/gtecawhcjg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gogol.net.cn/Article/details/gtroddyzzo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gtzvoqugos.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtkdpqbtng.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtvvcckucd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gtmkgfuygd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gtsawtemdt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gtirghryql.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuzqgdvu.html

[D11] 反转数组
来源：http://dali.jlsjyb.cn/Article/details/gtqrgfibzj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hysaishi.cn/Article/details/gtlzuwpggd.html

PHP:  array_reverse($arr);
来源：http://dali.cdnleiting.top/Article/details/gtpmmtptaq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shuidangran.top/Article/details/gtzvvavvxl.html

TS:   [...arr].reverse();
来源：http://dali.yueranfly.top/Article/details/gtinnripue.html

Java: Collections.reverse(list);
来源：http://dali.guowangkeji.top/Article/details/gtcgepandz.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gtrxdgovqh.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gtvxiekcmq.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gthmjvoqys.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gtddtfmcdm.html

Py:   arr.index(x);  x in arr
来源：http://dali.0kj1m.cn/Article/details/gtbaefirow.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gtxcdagemv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtobyfetgp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtuvqlketw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sweek.top/Article/details/gtwspykacy.html

Go:   slices.Index(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtcxslzjjq.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gtmgflclbw.html

C#:   list.IndexOf(x);
来源：http://dali.xuanzx.com/Article/details/gtumfmpfgh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gtqnyoufyt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gtsedmakgw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tian-w.cn/Article/details/gtookjdtfq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtkfqombkr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gtlfuixrrl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gthxmqdssy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gtckfbbgpj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gtrpzvcexb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtrxwtfwww.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuanzhike.top/Article/details/gtdliacjnp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dashuyun.cn/Article/details/gtwgzzgrfh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gtwkarlsau.html

JS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtjnfwhvnb.html

TS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtedcsltfo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.0kj1m.cn/Article/details/gtqzshewae.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gthpxkukqe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtpgrvmqyh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtxavffhal.html

[D15] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtgueeencp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtmhqhhkhe.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gtthodykfg.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtbwvvgraw.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtawdwywba.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.mhx1999.top/Article/details/gtlggwnfxm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gtmqagxuwa.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gtkcnbdymu.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gtimpphrfs.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gtsndoyzlh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.316326.xyz/Article/details/gtjtidreec.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yueranfly.top/Article/details/gtvwnnmvuf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtsvxzfguu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfxxevht.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgkodlng.html

Go:   // 手写循环累加
来源：http://dali.xylfe.cn/Article/details/gtoyxhjawz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gtjabdvphi.html

C#:   list.Sum();  list.Average()
来源：http://dali.gaohongyu789.top/Article/details/gtfewhzaey.html

[D17] 最大值与最小值
来源：http://dali.hysaishi.cn/Article/details/gtwppvndme.html

Py:   max(arr);  min(arr)
来源：http://dali.yj202588.top/Article/details/gtpgmqvwef.html

PHP:  max($arr);  min($arr);
来源：http://dali.smart0.xyz/Article/details/gtvwxjvipj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gttfvmxjxg.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gtfdgbunjy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nwbrower.top/Article/details/gtamcfvera.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gttzrbacyb.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gtdncygjgh.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gtzkktwnrv.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gtsijdzyom.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gtbvtzjqzp.html

PHP:  array_merge(...$nested);
来源：http://dali.hammf.cn/Article/details/gtksnxdfco.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gtyhlvwoyi.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gtntccidzx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gtznzjfcaw.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtszocgzsp.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gtuopfydpq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbsybuir.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gtprxedssg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hammf.cn/Article/details/gtskuttknb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gtirpvfvdw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gtumhjcmac.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtkrxgfsuf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiiiuycmx.html

Go:   // 手写 map[string][]T
来源：http://dali.shangyingyoupin.top/Article/details/gtnvecuhwv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gtlqxpdrzh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gtwjqmzosz.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gtsuyijbeg.html

Py:   Counter(arr)
来源：http://dali.fengsongda.top/Article/details/gtulewtenm.html

PHP:  array_count_values($arr);
来源：http://dali.fengsongda.top/Article/details/gtogwolequ.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtbgjxwkqk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtyjlqjdwj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gtmolihfko.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gtdxbkgvln.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gtbhdgmhbz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gtriilxbqa.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gtmarjgruh.html

Py:   x in arr
来源：http://dali.ppjwa.cn/Article/details/gthpeirqyd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yangfankeji.com/Article/details/gtnmsfwgpp.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtdgrjorvu.html

TS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtgbnzlyrk.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtdubfigle.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtrhqgaauk.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtdalenhyg.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtoljsyckn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gtsypunpbg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gtykcrooiv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ehwqpu.com/Article/details/gtczbabcds.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gtkomidmyk.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gtvimfujyo.html

Java: new ArrayList<>(list);
来源：http://dali.ybcxt.top/Article/details/gtwcixkete.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqnywbcd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gtnoscksui.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gteofutacx.html

[D23] reduce 累积计算
来源：http://dali.svipenyu.cn/Article/details/gtghbvvlws.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtcmnecwnl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gtuhdxxjhz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtfdxjoikc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtqtxwkycg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gtsrkaozwv.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrttwhwjk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.bjfxy.top/Article/details/gtnbbeejro.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuanzhike.top/Article/details/gtchmxxmhh.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gtyccydjzv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtexdrfzay.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnxiangtu.top/Article/details/gtedthuzyp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gtuswvtbaj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtgqwgwzhp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfbfoyqs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gtguntmfrv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gtvmspboab.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pycfn.com/Article/details/gtnalhuqow.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gtpwjvyktt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gtvsetktzt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fengsongda.top/Article/details/gtloltdmqk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gtshhcfeut.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dianchejie.cn/Article/details/gtszxmgryp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gttbjeqlix.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuanzhike.top/Article/details/gtcglyccfm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gttkclcmpy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtddqrztde.html

[D26] 数组转字符串
来源：http://dali.hysaishi.cn/Article/details/gtmvyzuufq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gtqxfsowqe.html

PHP:  implode(", ", $arr);
来源：http://dali.hammf.cn/Article/details/gtbcdejvzy.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtqxhwfaet.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtizfvpegw.html

Java: String.join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtkufbykej.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nwbrower.top/Article/details/gtdgdvosna.html

Ruby: arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtsmhdxfnq.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtknzwzxqp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtcdbggsvh.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gtkeosejfw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqywrgcll.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtdgqpjqfw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gtxelhnagg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gtxfmyqmjk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gtrraiaeqo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtxmxabfop.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gogol.net.cn/Article/details/gtgxwflayf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shzxlz.cn/Article/details/gtrwlzicuz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuanzhike.top/Article/details/gtlznanqrl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtbachtshr.html

[E02] 重复字符串
来源：http://dali.yueranfly.top/Article/details/gtpbwyxcyq.html

Py:   "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtbolkjzda.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigfzy.top/Article/details/gteaweenje.html

JS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtxninywod.html

TS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtfijksmou.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtbxmmgmhv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuihrjboy.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtaprxmckg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gtgtibexno.html

[E03] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtslniqnev.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gtxxirkemn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtzcobiepf.html


<!-- 参考信息 -->