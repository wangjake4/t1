代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtcuwzxkzj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtfdxelefc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yangfankeji.com/Article/details/gttokencgl.html

Ruby: # 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtqkbrqzgf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pycfn.com/Article/details/gtraggvkta.html

[C15] 解构 / 展开参数
来源：http://dali.wangshuangyany.cn/Article/details/gtxerhlgvj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gtledixyuy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuxming.cn/Article/details/gtxeixlkug.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtquxygbwv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpplxbuy.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gtnfatnzvp.html

Go:   // 无解构
来源：http://dali.cucudq.cn/Article/details/gtuxcszrcf.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzojyatj.html

C#:   var (a, b) = pair;
来源：http://dali.xylfe.cn/Article/details/gtbjslgjkv.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gtejaozwrt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gtxnpjkvvi.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gtmvuejtke.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtbalqwaki.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gtjbudvkwh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gthybpdzhw.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gtdkxkpvsx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigufen.top/Article/details/gtmmzuhzvs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fzhhl.top/Article/details/gtzzcpvsng.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnlumaccx.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gtmvgpfqyc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtbscwmirh.html

[D01] 创建数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gtjfbijtyd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.c1oappe.top/Article/details/gtpirfsqvv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtzjcfiqvr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gtedmytmye.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhongyouzk.top/Article/details/gtrdkagzoh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gtzaeuzpzu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhixingplan.top/Article/details/gtbyayxuru.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sweek.top/Article/details/gthicfyila.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuxming.cn/Article/details/gtbkaxpicf.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gtidzngdnn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gtutsqhdrw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwlfrumd.html

JS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtehjjjarx.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtuhehsftu.html

Java: list.add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtovirqiay.html

Go:   arr = append(arr, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtzprdehcp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.bjfxy.top/Article/details/gtjycnhmjs.html

C#:   list.Add(4);
来源：http://dali.yongpay.top/Article/details/gtbwdjubrn.html

[D03] 在指定位置插入元素
来源：http://dali.meibo888.top/Article/details/gttzgaquyu.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtgtaqqaio.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dianchejie.cn/Article/details/gthgpiyjuv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nwbrower.top/Article/details/gtgkgyvcbh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gtjlqgzlwt.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtwzlbmtit.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangdashe.top/Article/details/gtlboqlsxf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gthvcfbkxd.html

C#:   list.Insert(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtzsghhyxo.html

[D04] 删除元素
来源：http://dali.gaohongyu789.top/Article/details/gtrzlaoghf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhoulong.xyz/Article/details/gtcovchvax.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.birdmap.top/Article/details/gtbszlswkb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdumuwtc.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gtnedkhwku.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gtncvjuelz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pycfn.com/Article/details/gtbsacmrli.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxuanxn.top/Article/details/gtrhxkekhr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.snrcjt.cn/Article/details/gtdfwscpya.html

[D05] 访问与修改元素
来源：http://dali.chenzaomai.com/Article/details/gtfgnqzzeo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtgulxlgwi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtajikzomn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjcdiirz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigufen.top/Article/details/gtmwcoddyo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gtkazrxkjx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtnydpcldq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtsrjhtaek.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtpcanlvmq.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtnasioghd.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtugmokxrl.html

PHP:  count($arr);
来源：http://dali.zdqjudy.top/Article/details/gthbgtekkf.html

JS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gtciwdoxqa.html

TS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtbbkdendo.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gtfenzsmuu.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtoicrnnrm.html

Ruby: arr.length; arr.size
来源：http://dali.nanxinkj.top/Article/details/gtclbexyjf.html

C#:   list.Count;
来源：http://dali.svipenyu.cn/Article/details/gtzkrvgcoi.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gtusesavlo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxuptwvd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gtbotinqak.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtdlzpimgq.html

TS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtrqczfupp.html

Java: list.subList(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtjnalrwcj.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gtuzacovek.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gtmmaemnaj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zdqjudy.top/Article/details/gthnhmugep.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttuhpdde.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhixingplan.top/Article/details/gtihayfvfn.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtkhlggpvn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.redwolf501.top/Article/details/gtoceqetvg.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gttbhepctl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gtgrydiekk.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gtwwqtjwjf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gtmbvuxefs.html

C#:   a.Concat(b).ToList()
来源：http://dali.cheryme.top/Article/details/gtonagnila.html

[D09] 排序（升序）
来源：http://dali.yj20258888.top/Article/details/gttuiwjuvq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtouwvgwxk.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtvfhgcpbn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jlsjyb.cn/Article/details/gttsqlowyc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shzxlz.cn/Article/details/gtodzetjed.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.vqdsnc.cn/Article/details/gtygtcpuwy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtzdyjntbi.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtwplgunge.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gtsnknnmbr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.quarkkingdee.top/Article/details/gtpruzuptd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gtgcslznsh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gtpeejftgi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtxjulyqny.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtszyghgux.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gtpdggrqje.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shzxlz.cn/Article/details/gtyotwngci.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ybcxt.top/Article/details/gtgmrzennp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocdkkjmy.html

[D11] 反转数组
来源：http://dali.jlsjyb.cn/Article/details/gtnqjgsunq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gtxaqtemnp.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gtbxfzragi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gttsjycmjp.html

TS:   [...arr].reverse();
来源：http://dali.yueranfly.top/Article/details/gtqwaiwsei.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gtsagpchek.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtnudkfkvp.html

Ruby: arr.reverse
来源：http://dali.jinqigufen.top/Article/details/gtqcgoioki.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvlhztbp.html

[D12] 查找元素下标
来源：http://dali.jinqigfzy.top/Article/details/gtfdonpldp.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxinkj.top/Article/details/gtgyympnit.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nwbrower.top/Article/details/gtwrfwqdxj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtevoedksr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtqlzbdxkq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gthcfekfcy.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtihtreeux.html

Ruby: arr.index(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnihkxynv.html

C#:   list.IndexOf(x);
来源：http://dali.yonumen.top/Article/details/gtasirhorw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gtdorrxarp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtosrzhvqw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shuidangran.top/Article/details/gtzxwbtzac.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrfyhbyc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtzlkmyzyl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtaijsbhvi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gogol.net.cn/Article/details/gtrwkltjlg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenlongwang.top/Article/details/gtmdxwbztl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtsiyuewtw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuanzhike.top/Article/details/gttdrlczbw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvizwnyvm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gtafqqziey.html

JS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtogbpvkkc.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyyibjwy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gthrktdnfs.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtzarkaaiw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtlcghsdde.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrqatkdy.html

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gttejkdlls.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtcmeootuc.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gtsfyplzbv.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtmiaixiha.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtvuopaggb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gtsbmeaafd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgfzy.top/Article/details/gttnanapax.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gtjozuznkv.html

C#:   list.Distinct().ToList()
来源：http://dali.daria6918.cn/Article/details/gtcadlmytu.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gtmbrhqxgx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gtznggeham.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gtdtcsxizi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtsqzcfmkb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtbpvgpowv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gtvwmxtdes.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gtwalfekub.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cheryme.top/Article/details/gtyunwefwm.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gtlgfpyypv.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtauhulygm.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtvunrowks.html

PHP:  max($arr);  min($arr);
来源：http://dali.jianghu66.top/Article/details/gtgspetamm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gtojpzcoia.html

TS:   Math.max(...arr);
来源：http://dali.jqgfzy.top/Article/details/gtiflalcan.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tianlin.xyz/Article/details/gtmpddcdho.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtulelysep.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gtaleinxiw.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gtalftdbfe.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gthzxsbadc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cqqwz.cn/Article/details/gtoqyysrkz.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gtihgqguzy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gtaqdfiqge.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gtuxzyptbd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gtvnehzlxd.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gtmbimujby.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gtvfpttadn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtjcqycfvb.html

[D19] 按字段分组
来源：http://dali.tanke756.top/Article/details/gttpnwptga.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gtvimimmsq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gtcbnxbolw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gtrvsgeqnr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtdjaedzit.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gtjbwdhexr.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gtwnedidln.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtxjywxwbj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gtlyiisold.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtgncgkbsu.html

Py:   Counter(arr)
来源：http://dali.jinqigufen.top/Article/details/gtseqtylxd.html

PHP:  array_count_values($arr);
来源：http://dali.ppjwa.cn/Article/details/gtddscnamq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gttvmvoqct.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtwtsunwxk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.mhx1999.top/Article/details/gtuvyjdjdq.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gtgyejfcdv.html

Ruby: arr.tally
来源：http://dali.tianlin.xyz/Article/details/gtqlxifzts.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.bjfxy.top/Article/details/gtcaddfpyo.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gtsbrcinxh.html

Py:   x in arr
来源：http://dali.nwbrower.top/Article/details/gtpnnrhljg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cashguo.top/Article/details/gtyqeopukl.html

JS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gteecuzmeh.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtojtwfcbh.html

Java: list.contains(x)
来源：http://dali.birdmap.top/Article/details/gtsnnzsndu.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtrmnmlqzp.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyyrjeln.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gtgwjjedhc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gtcbslfudv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gtewaawtdq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xylfe.cn/Article/details/gtanfkmfgx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gtsbounzzd.html

TS:   [...arr];
来源：http://dali.9152youxi.cn/Article/details/gtpejdebrz.html

Java: new ArrayList<>(list);
来源：http://dali.sysykeji.top/Article/details/gtrdpkhbwx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gtiziivlek.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shzxlz.cn/Article/details/gterbsjahu.html

C#:   new List<int>(list);
来源：http://dali.zycfv.cn/Article/details/gtntmbctpw.html

[D23] reduce 累积计算
来源：http://dali.jinqigufen.top/Article/details/gtexjfdqsh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtcearbcma.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtvpfwpycl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtkflouofo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtollosaoz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dianchejie.cn/Article/details/gthuihnynv.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtvghisind.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gtpajdlcav.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gtndsmjwoj.html

[D24] 字典 / Map 基本操作
来源：http://dali.meibo888.top/Article/details/gtcklujzsp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shzxlz.cn/Article/details/gtgfomprpx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cheryme.top/Article/details/gtzrxmqcjy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sweek.top/Article/details/gtcpkeubib.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtvvizyfat.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.feifeiyinyue.top/Article/details/gttmqsjfaf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gtepwqmkpu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gtxwxpknll.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gtfxhednkl.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gtjmscpzdn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.0kj1m.cn/Article/details/gtrkitgpwj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gtlurevmsy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmouebix.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shangyingyoupin.top/Article/details/gtsdyvuave.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gtbbxnzmsv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gtdxwlrdrq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gtjemjclsy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gtrjnilnlh.html

[D26] 数组转字符串
来源：http://dali.yueranfly.top/Article/details/gtvsmmxqgh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jyoumei.cn/Article/details/gtgetnmibo.html

PHP:  implode(", ", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtohrcqvqe.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtlsaeplny.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtbhdqlbvw.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gttewmznue.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gtdfvumnao.html

Ruby: arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtghrbyiut.html

C#:   string.Join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtzenjjctj.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrkmskkow.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gtjnirycpa.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtonlkddqr.html

[E01] 拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtcetcbhcy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gtnzwoxiuc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gtcvrpkedz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gtxujvyimn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtirdykors.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.snrcjt.cn/Article/details/gtvamnockf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gtkkutfgms.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cdnleiting.top/Article/details/gtsuqfwzwq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtjgkhemif.html

[E02] 重复字符串
来源：http://dali.yanxiufei.cn/Article/details/gtaxqliypq.html

Py:   "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gtbnkdgwhl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gtunulirmk.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtqtmgsval.html

TS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtudixppzd.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtaxqknhbw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pycfn.com/Article/details/gtfxkscxax.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtwjsgpwii.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gtebztjili.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtmfovtgzw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmuecsje.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtvpuzirnq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtmjndlvot.html

TS:   s.slice(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtmtldwaun.html

Java: s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtjdefhjxs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ppjwa.cn/Article/details/gttaymzrbw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daria6918.cn/Article/details/gtsyuincid.html

C#:   s.Substring(1, 3)
来源：http://dali.shuidangran.top/Article/details/gtwggaxhub.html

[E04] 查找子串位置
来源：http://dali.tianlin.xyz/Article/details/gtlpqmfvvf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtufecqmce.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gtnwcqwkha.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gtnkazvejq.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtselixfrx.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtzmksynxb.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gtjkbmmpwv.html

Ruby: s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtzvvmcxkb.html

C#:   s.IndexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtjrsoplib.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pengpengdd.cyou/Article/details/gtwjnmnjaj.html


<!-- 参考信息 -->