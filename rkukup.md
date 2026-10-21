代发 wailian999

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gtxfdmzxfr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuanzhike.top/Article/details/gtaurpcytw.html

PHP:  // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtpgefzvhj.html

JS:   // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtivgjthqb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daxiang520.top/Article/details/gtxwlcxdoq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtcslgrige.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cucudq.cn/Article/details/gtglcjgiwy.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtfjusedwb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sxryk.cn/Article/details/gtbcumhphg.html

[C15] 解构 / 展开参数
来源：http://dali.zycfv.cn/Article/details/gtncldaynq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gtzoyqwjte.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daria6918.cn/Article/details/gtqcbssgsj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gteyykrqxc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtkinmjhjz.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtbpfsemwf.html

Go:   // 无解构
来源：http://dali.dianchejie.cn/Article/details/gtoduvotub.html

Ruby: a, b = pair
来源：http://dali.jianghu66.top/Article/details/gtiqkexxtu.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gtunzwxrzt.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gtebnwoddj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gtkorblkfi.html

PHP:  // 无重载
来源：http://dali.dianchejie.cn/Article/details/gtqnvhqbmb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cashguo.top/Article/details/gtdsjiiqiz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fengsongda.top/Article/details/gtisdxbdrk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daria6918.cn/Article/details/gtrofofwlf.html

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gtfusuukkt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guowangkeji.top/Article/details/gtqdhwwvvr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkkmutabh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrkfmerxw.html

D. 数组 / 列表 / 集合
来源：http://dali.ybcxt.top/Article/details/gtaidzprxi.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqvcownf.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtohbgqzqw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zycfv.cn/Article/details/gtcpzbbcac.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtvbcvewyh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtyhadhrfs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gtopcwnwkv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj202588.top/Article/details/gtrigeswta.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258.top/Article/details/gttqrqpvsa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.iojbl.cn/Article/details/gtglugdoac.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtybkuwnft.html

[D02] 追加元素到末尾
来源：http://dali.mhx1999.top/Article/details/gtqhlxmnhd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuxming.cn/Article/details/gtietxkbhx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtbfscqaaz.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtwixjsten.html

TS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtjbpatvsh.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gtnffigdgp.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258.top/Article/details/gtvhffphsz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgfzy.top/Article/details/gtxotlschc.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gtevueocoi.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtwllaxttd.html

Py:   arr.insert(0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavklctbf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258.top/Article/details/gtpbbqptce.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhiwuduotai.top/Article/details/gtwwcfntph.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gthcmidvwx.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gttsscxcsg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtcznfziwe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.smart0.xyz/Article/details/gtdtmhotvg.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtkvmmxeoz.html

[D04] 删除元素
来源：http://dali.nanxuanxn.top/Article/details/gtrronxvcx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dashuyun.cn/Article/details/gttczytsjb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtbmsjpqzn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aizwys.cn/Article/details/gtazcnffyv.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gtthrsrjds.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gtsnionlss.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yanxiufei.cn/Article/details/gtrdwsxdzo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgufenzy.top/Article/details/gtxipnhqfx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobfghhzj.html

[D05] 访问与修改元素
来源：http://dali.daxiang520.top/Article/details/gtvyaqbdal.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtrfnecwhu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtqagrczdu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtxsjrwzsn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gtxxheklgq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gtjrihlywv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gthylcfmdr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtoxnermtd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtwatsmxkm.html

[D06] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtctfkagvb.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gttofddxpj.html

PHP:  count($arr);
来源：http://dali.ehwqpu.com/Article/details/gterkwayqs.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtotngkhug.html

TS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtgpoajouc.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gtfktscyny.html

Go:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtavrtuziq.html

Ruby: arr.length; arr.size
来源：http://dali.yuanzhike.top/Article/details/gtmjwervid.html

C#:   list.Count;
来源：http://dali.gzhubu.top/Article/details/gtyrpzfjoc.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gtonfrtzeu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.smart0.xyz/Article/details/gteqtdnlqf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwsxdpdi.html

JS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtcndsvmhw.html

TS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtlyvvanjn.html

Java: list.subList(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtgunwxjyn.html

Go:   arr[1:4]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwtgkdbb.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtqpzvvnbl.html

C#:   list.GetRange(1, 3);
来源：http://dali.zycfv.cn/Article/details/gtweohkdcv.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gtwrniynmf.html

Py:   a + b;  a.extend(b)
来源：http://dali.yvedp.cn/Article/details/gtjlwihtpn.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gtksmerymq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gtewqevrgy.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gtxbzafzxh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gtvpqppslq.html

Go:   append(a, b...)
来源：http://dali.dashuyun.cn/Article/details/gtewiumtav.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigufen.top/Article/details/gtmkeyntup.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtewcwkobn.html

[D09] 排序（升序）
来源：http://dali.pycfn.com/Article/details/gtqfcibgrs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtwnvfhfhr.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gtfzaaeoyq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gtzjfjdyzq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gtrdyygxpk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yongpay.top/Article/details/gtkouhyexa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtvggtpvwr.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtdjevjskx.html

C#:   list.Sort();
来源：http://dali.zhengqikj.top/Article/details/gtbfpvudlu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gtknlndadm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodhyumvy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daria6918.cn/Article/details/gtfobaabbi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtzkccofgh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtditgcbvh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gtqroedbmf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykjqbbee.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gtkmsizpfp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.c1oappe.top/Article/details/gtvdxpgnru.html

[D11] 反转数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtaeybybtx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gtphwlxhvu.html

PHP:  array_reverse($arr);
来源：http://dali.yuxming.cn/Article/details/gtalhmaifb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gtnewijnuy.html

TS:   [...arr].reverse();
来源：http://dali.chenzaomai.com/Article/details/gttfgysjpd.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gtrvvbmylc.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gtafxcbrmq.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gtlqabfgka.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gtqhojkqwb.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gtjvufqdoq.html

Py:   arr.index(x);  x in arr
来源：http://dali.ybcxt.top/Article/details/gtcbeltbrk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobfilrrr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gttxoouqpx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gttnwhtufr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.havefunace.top/Article/details/gtkyufplmz.html

Go:   slices.Index(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtvlefykeb.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gtqmaevdnz.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtwnksiwtu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtlpjpvevq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gtezyfpwdr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.bjfxy.top/Article/details/gtduqwsvcf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gtpuyahsak.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtugqkxlih.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gtjugkmnth.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gtxufoskyk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gtmxnrcaft.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gtsulpitzt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yanxiufei.cn/Article/details/gtndpbnvji.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gtawipgwwt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtamuauxvm.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gtglidtfxd.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtlfxhzjph.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtetxtxjbo.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gtxvpqksnh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gttsskmjco.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gthskcbvyh.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdanhmuxs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtptojhmpc.html

PHP:  array_unique($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqwwyfhm.html

JS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfktovmvs.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtnqtmaccl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258.top/Article/details/gtjvfmlzil.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpbctxdx.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtqtxmyawz.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxinkj.top/Article/details/gtponxpqyx.html

[D16] 求和与平均值
来源：http://dali.zhongyouzk.top/Article/details/gthzwjlwdo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtfnldxwna.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gzhubu.top/Article/details/gtlsyxgzoi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gtfiowecak.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gtafxqwovj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtjoogsmwg.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gtmnkgpcfq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtqlzsuppl.html

C#:   list.Sum();  list.Average()
来源：http://dali.birdmap.top/Article/details/gtwymjouih.html

[D17] 最大值与最小值
来源：http://dali.zhixingplan.top/Article/details/gtwjnuagob.html

Py:   max(arr);  min(arr)
来源：http://dali.c1oappe.top/Article/details/gtxqrvllnj.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gtthdgvgls.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj202588.top/Article/details/gtxwwlgwba.html

TS:   Math.max(...arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtatizwexz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gtukvtomyi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gthmbwxbkv.html

Ruby: arr.max;  arr.min
来源：http://dali.tanke756.top/Article/details/gtxwtzcocq.html

C#:   list.Max();  list.Min()
来源：http://dali.cashguo.top/Article/details/gttzbxhlry.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gtaknnxodo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.andypj.xyz/Article/details/gtqlvsqawn.html

PHP:  array_merge(...$nested);
来源：http://dali.snrcjt.cn/Article/details/gteljgrqlt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gtcjqvwptk.html

TS:   nested.flat();
来源：http://dali.redwolf501.top/Article/details/gtsrunxugr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gtexlzhmjy.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gtvpywxpvq.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gttehztrbg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtwstgbpyq.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gtmeqynauo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.snrcjt.cn/Article/details/gtwqmqbmca.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gttnjbfchb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrvxsvyk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtmgigmmsg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gtgrxjzaih.html

Go:   // 手写 map[string][]T
来源：http://dali.yvedp.cn/Article/details/gtiwjbeeme.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtlvhargva.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gtrpzslpse.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gtjjvydeko.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxtjrvcg.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gtwvmydmax.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtdvvzdigc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gtvwbaxesx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gtipfwlhvl.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gtbryayico.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gtffsopdum.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tianlin.xyz/Article/details/gtdqfqguht.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gthtmwpunv.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gtxxgmjdld.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yongpay.top/Article/details/gtkafzisab.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtzruzaigm.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtdoeayane.html

Java: list.contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtyoygwkib.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlmtjvpx.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtijswgfvm.html

C#:   list.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtnsjmckmq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gtxxszmede.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.meibo888.top/Article/details/gtfxerycic.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ehwqpu.com/Article/details/gtfbpoydbx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sufxvd.cn/Article/details/gtqwshiupy.html

TS:   [...arr];
来源：http://dali.wangshuangyany.cn/Article/details/gthtfmbbsd.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gtsmxrcsyi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hammf.cn/Article/details/gteltjpyhn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gtddcryhpt.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gtvoytkwbd.html

[D23] reduce 累积计算
来源：http://dali.hongshengwenyu.top/Article/details/gteyyzkuxa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gtssfzxbot.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsatabza.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtoimwnqal.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtfqnqlssk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.smart0.xyz/Article/details/gtzmsnwitw.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gtvlizehbk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gtqnnqeang.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gtomgicbgg.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gtvryiphhf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.c1oappe.top/Article/details/gtndzxkhfb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jlsjyb.cn/Article/details/gtettzwxox.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmgpxucd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gtwdoywuhw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnxiangtu.top/Article/details/gtwanhkysz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangshuangyany.cn/Article/details/gteabsnarb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtkvihdodn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gtjvyqwuos.html

[D25] Set 集合去重与交并差
来源：http://dali.xylfe.cn/Article/details/gtwgajeskg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gtkqcuotel.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gtchnhnjll.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hammf.cn/Article/details/gtfabvctdj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtpgpcqwxa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtjyxqcqix.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhiwuduotai.top/Article/details/gtfczzxroo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gthtldjqfw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuolsrfpf.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtyperppby.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtqmovvxaf.html

PHP:  implode(", ", $arr);
来源：http://dali.xziqi.cn/Article/details/gtbwlwjbml.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtnczmircj.html

TS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtdynakylf.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtjsprbbfg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gtrfifmbww.html

Ruby: arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtzzxrbnoc.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtwyzzuxod.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtbhokzkco.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gthivpxfdw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlxstbnfw.html

[E01] 拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtetugrjry.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gtnqubqsjh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gtemftpolg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtdnthpbsm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtcdftsjcf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnxiangtu.top/Article/details/gtbkbruxoy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gtflurrdjj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yanxiufei.cn/Article/details/gtgchcbjdr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtgttovire.html

[E02] 重复字符串
来源：http://dali.tian-w.cn/Article/details/gtoqmivqaz.html

Py:   "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtqlogqmkw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gtmxfznrtt.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtguvckeso.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gttqvnbtob.html

Java: "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtveruzsiw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gtbazmegrq.html

Ruby: "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtsrnyzfoa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gaohongyu789.top/Article/details/gtxslvhukt.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtxvzhszjy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gtrbxfargu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtvsxjwfrm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtmuyyddjn.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtdfmogvnb.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtaonxtjfo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gtdyyfugsc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shuidangran.top/Article/details/gtqsuqafhx.html

C#:   s.Substring(1, 3)
来源：http://dali.sweek.top/Article/details/gtkeahkdtd.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gtyjunevah.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtxoxfjgwd.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gtxwnpywsf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nwbrower.top/Article/details/gtwffaedrz.html

TS:   s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gtemcpqwpe.html

Java: s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtyfrzbhgo.html


<!-- 参考信息 -->