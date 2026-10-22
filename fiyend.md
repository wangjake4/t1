代发 wailian999

[C14] 泛型函数
来源：http://dali.yj202588.top/Article/details/gtfyoelceb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jyoumei.cn/Article/details/gtxveogfqt.html

PHP:  // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtzdddnvng.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtimoohhdr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gtkmpjjevm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gtavpabuui.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gtbafhxkaj.html

Ruby: # 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtutmyptwr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yongpay.top/Article/details/gtmtfdupve.html

[C15] 解构 / 展开参数
来源：http://dali.jqgfzy.top/Article/details/gtgnsukbuc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gtiuummuor.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpkczvdl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gtynatvxyf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ehwqpu.com/Article/details/gtwmbqtmdn.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gtlokytkon.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gtqqukaecf.html

Ruby: a, b = pair
来源：http://dali.gogol.net.cn/Article/details/gtegsenrdm.html

C#:   var (a, b) = pair;
来源：http://dali.cashguo.top/Article/details/gtcbahuyqv.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gtebdzputp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cucudq.cn/Article/details/gtyvurpruj.html

PHP:  // 无重载
来源：http://dali.hongshengwenyu.top/Article/details/gtvsbcwtsa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gtkvbiawld.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdosvbszu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.havefunace.top/Article/details/gtxrtobajw.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258888.top/Article/details/gtuoxsnwtm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gtykjkvioa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gtjzdahjej.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtbglsymrt.html

D. 数组 / 列表 / 集合
来源：http://dali.birdmap.top/Article/details/gtlodysyet.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpmywnmll.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gtkvnevwlj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtngleibyg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtqlknrdmt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmynfblrh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gtexjnhroq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gtouihwkct.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhoulong.xyz/Article/details/gtbmijhxcq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258.top/Article/details/gtqdmbtwtq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gtagylsjrv.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gtuertnstg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zdqjudy.top/Article/details/gtvjanocyp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgfzy.top/Article/details/gtjhehyxss.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gtmwzssttv.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtxdshsmot.html

Java: list.add(4);
来源：http://dali.haohaochexian.top/Article/details/gtegaxoouf.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gtzeyshmqp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aizwys.cn/Article/details/gtoaggdzyt.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gtsgvzjeil.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gtmyueuety.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gtjgjftfod.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.redwolf501.top/Article/details/gtspbtewdm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hfpthk.cn/Article/details/gtsuuntvzo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtkeuetzfg.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtgpxjerlp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gtdrugkmco.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gthohyvldc.html

C#:   list.Insert(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtttnvfboh.html

[D04] 删除元素
来源：http://dali.guowangkeji.top/Article/details/gtpxwwldva.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetyuzbcl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ydzc1.top/Article/details/gthaucyfvi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gtznrjjlbf.html

TS:   arr.splice(0, 1);
来源：http://dali.ppjwa.cn/Article/details/gtjqhvrfvd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxuanxn.top/Article/details/gtfehavenj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gogol.net.cn/Article/details/gtrdbcfdzc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gtasblbpkq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.mhx1999.top/Article/details/gtgpyyrseh.html

[D05] 访问与修改元素
来源：http://dali.wangdashe.top/Article/details/gtssueerpm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtmtbspxug.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtxbcywmpd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtysdxgzxt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.havefunace.top/Article/details/gtafyiwtvv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gtrvcnaejy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtnmtwtfyp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtufunjxkv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtpeaeccxz.html

[D06] 数组长度
来源：http://dali.316326.xyz/Article/details/gtycdnfkdm.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsuvjwdyg.html

PHP:  count($arr);
来源：http://dali.bjfxy.top/Article/details/gteaiqfbdr.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdtibdtq.html

TS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtjpmhthym.html

Java: list.size();
来源：http://dali.zhixingplan.top/Article/details/gtorutemwy.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtcfrbcdro.html

Ruby: arr.length; arr.size
来源：http://dali.zycfv.cn/Article/details/gtancgzqbz.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gtngexhuud.html

[D07] 切片 / 取子数组
来源：http://dali.shangyingyoupin.top/Article/details/gtbowxneqj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gtvbmpnrrh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtctmltmqm.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gtnnldbwps.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtlwifymfv.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtfkrtjcdg.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gtqlvhxbjs.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gtqkwwumhv.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gtbwhmvfyz.html

[D08] 合并两个数组
来源：http://dali.havefunace.top/Article/details/gtxvzqkjep.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gttciztgrh.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtoecjjoxm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gtjxromupv.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gtwcohvdyw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sysykeji.top/Article/details/gtzhtqfhqt.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gtsngxyffw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnxiangtu.top/Article/details/gtzedqbtnf.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtnhkvilqh.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gttohzekvr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtotiqtyjz.html

PHP:  sort($arr);
来源：http://dali.aibaodan.cn/Article/details/gtzbskbeky.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dianchejie.cn/Article/details/gtrwekptsz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangshuangyany.cn/Article/details/gtvagfzjbj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gtxhuesfum.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtfldcjtjv.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtaduezhjp.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gtboxbntbq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gtatcmzrxc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangdashe.top/Article/details/gthdbguvkp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gtzblpkvwt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtacixshku.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxucinel.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnxiangtu.top/Article/details/gtupoozfgl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daxiang520.top/Article/details/gtblhjcfxz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gthnhqszni.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gtnxkhzifx.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gtjnvcwbbz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gtvqcyvawr.html

PHP:  array_reverse($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtpysisldw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gtqcwfwijz.html

TS:   [...arr].reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrzjyqty.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gttadakfwc.html

Go:   slices.Reverse(arr)
来源：http://dali.yonumen.top/Article/details/gtdpxxzenp.html

Ruby: arr.reverse
来源：http://dali.fengsongda.top/Article/details/gtywdsrmoo.html

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gtxcfbppvv.html

[D12] 查找元素下标
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrlgtmft.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtyppolamn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtydvjzwat.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtxziiutye.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtmgoxisjh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hammf.cn/Article/details/gtudqxgvgm.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gtdafaljbs.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gtcnzocvna.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigufen.top/Article/details/gtlosneqtk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gtiuxvugav.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuanzhike.top/Article/details/gtkqnfmvjt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gtakexstwu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtatzmgdxv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvesdggt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.redwolf501.top/Article/details/gtgneylbuw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.iojbl.cn/Article/details/gtwunhhvav.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtwcrmykld.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtfucieuip.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gtjovebkwd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtmecnccqe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gterulkjno.html

JS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gthariatpq.html

TS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtzetzcqmq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtgnfebhyl.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtavcmtjqq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gttlhtuwme.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtuzlnqhna.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gtuvgccblk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtczylifya.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gttcssjqyw.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gteuxnsscp.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtshuajjap.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gteibzxjue.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhiwuduotai.top/Article/details/gtygjdpzdq.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gtbcrhucpo.html

C#:   list.Distinct().ToList()
来源：http://dali.gogol.net.cn/Article/details/gtlxqkxvnf.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtqstffauk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtoodjmiyt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.smart0.xyz/Article/details/gtsrpreoip.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtyanmkndx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtvcnwxwcu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gtcgorinlj.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gtdodwbiso.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gtxoliivms.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gtbjfpgjad.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gtvbwxarff.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtmajdmabp.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gtweijzpzn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gtamymgrzh.html

TS:   Math.max(...arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtarlwjibx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tianlin.xyz/Article/details/gtkyssfkui.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtezniiuhu.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gtrbchmfih.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gtjzoyfnzt.html

[D18] 扁平化嵌套数组
来源：http://dali.xinyue.icu/Article/details/gthzjneqef.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhengqikj.top/Article/details/gtmshlikfb.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gtnnxplnfa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsquskqi.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gtvxdogyaq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrqrmqjx.html

Go:   // 手写双层循环
来源：http://dali.dianchejie.cn/Article/details/gttnxfuvdn.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcybjjvi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gtksppqihx.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gtxuqpkhyc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gtqmuwwjxw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dianchejie.cn/Article/details/gtbralecjg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gtuberwrrs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtnevzvajp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.vqdsnc.cn/Article/details/gtoiqamlvl.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtrartheod.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daria6918.cn/Article/details/gttdqaepcg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gtbohouqye.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gtcpevfoio.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gtqkpdaqfc.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtdcxleizw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtbzhlvtah.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtyvhfyevg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gtiodnsbjs.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gtfgkspdhd.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gtyoenlefe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gaohongyu789.top/Article/details/gthqnrkujx.html

[D21] 判断是否包含某元素
来源：http://dali.hnqzz.top/Article/details/gtphevfdny.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtqolaolor.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtfwwfbqcw.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtmgmhxunh.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtqcdxbegz.html

Java: list.contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgowpsnoa.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtcujnufcp.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtqouqwtjc.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtptqpkhci.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cheryme.top/Article/details/gtrzorkdfy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtzchzctjd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gtsmkslswj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gtzvlcuvnr.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gtbtwrwqbo.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gtlbbnnbqy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ybcxt.top/Article/details/gtxyqbacnl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gtnbxefqzq.html

C#:   new List<int>(list);
来源：http://dali.gzhubu.top/Article/details/gtqahucoep.html

[D23] reduce 累积计算
来源：http://dali.yueranfly.top/Article/details/gtmjugtwfg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gtvxmykevb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuanzx.com/Article/details/gtxopbpogl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtqrvxbszp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtgbnmcfwj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gtnlujetwy.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gtrcmhyhki.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gtlgwceoij.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daxiang520.top/Article/details/gtvdovbmrg.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtpmlrhtep.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sxryk.cn/Article/details/gtwotjacdv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gtdaeeqkbw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cashguo.top/Article/details/gtnwstonke.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtbroqkdvg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gtbtihtexq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hywenlv.cn/Article/details/gtygrsmdgb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gtyrwwxqfi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gtnezxlzsu.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gtjsbzlpcb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gtpnhtzych.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gtlhzopfid.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gtauxuttwy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gtqgdscslq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrthulcfa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gtbtjddoby.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gtkeendbdc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gtmqfyxngz.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmlpdzqp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xinyue.icu/Article/details/gtqschpdiv.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtcmsaakhi.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gttqargqjq.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtpmxahpei.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtxxpxhsvw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gtovnnzhyy.html

Ruby: arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtramyzzcc.html

C#:   string.Join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtjhgjuuii.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtolhhrslt.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gtgorpaqye.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtpwiqiany.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtgwqdwggy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtukzvtryd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guowangkeji.top/Article/details/gtweeqvaih.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtqruyjmia.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtttvzqalw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gtjlyayqan.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ydzc1.top/Article/details/gtydbpflvy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsfhyflg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtlgjgtwab.html

[E02] 重复字符串
来源：http://dali.hysaishi.cn/Article/details/gthqkhyvql.html

Py:   "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtlzotrynl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtfwtcbctu.html

JS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtkevubjvx.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gttjjdgerl.html

Java: "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtfkvpxidz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258.top/Article/details/gtonzatlwa.html

Ruby: "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtzvttegsd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pycfn.com/Article/details/gtmdslqwas.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtesxnmpxc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aizwys.cn/Article/details/gtxjrsncda.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtdidtzwvh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtnigbyart.html

TS:   s.slice(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtilkekhth.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtbkfgrmzc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtatdpjuqe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gtymmuscxo.html

C#:   s.Substring(1, 3)
来源：http://dali.sufxvd.cn/Article/details/gteqmffvos.html

[E04] 查找子串位置
来源：http://dali.daria6918.cn/Article/details/gtrctgkgxu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.c1oappe.top/Article/details/gtgponfflo.html

PHP:  strpos($s, "x");
来源：http://dali.guowangkeji.top/Article/details/gttpdsxord.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cheryme.top/Article/details/gtnakfhxyl.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtniwvwoxc.html

Java: s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtlbsggxiw.html


<!-- 参考信息 -->