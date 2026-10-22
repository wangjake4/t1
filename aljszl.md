代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujlfgpnc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.bjfxy.top/Article/details/gt2dlusenwr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shzxlz.cn/Article/details/gt2hvswcczy.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgzdpqhb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fengsongda.top/Article/details/gt2esebyzwk.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gt2fhrfcwjs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gotoacloud.top/Article/details/gt2lhhzzsxn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hysaishi.cn/Article/details/gt2pkvzhhah.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gt2sglrxdfk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fzhhl.top/Article/details/gt2bxkofetq.html

Java: // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otowxgrr.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zbvvbihs.html

Ruby: a, b = pair
来源：http://dali.meibo888.top/Article/details/gt2oqyafdyq.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gt2atgrhunw.html

[C16] 函数 / 方法重载
来源：http://dali.zhengqikj.top/Article/details/gt2tfzhrhgm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gt2jmqhahux.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gt2cpfxqybx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnqzz.top/Article/details/gt2weuvnsjt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gt2ztdbbhzj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnqzz.top/Article/details/gt2ukoifupm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhoulong.xyz/Article/details/gt2cqpdntkf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shzxlz.cn/Article/details/gt2gbuntgau.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2qplatcfs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2irfdtekf.html

D. 数组 / 列表 / 集合
来源：http://dali.ybcxt.top/Article/details/gt2hyzgdoee.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2fnlousek.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gt2bvvytzvd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.mhx1999.top/Article/details/gt2jilmirvc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gt2kijgykqu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gt2ggriibdr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gt2gedbghoe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ydwhptsb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gt2sialecnn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdwfcjqa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gt2ivcxzjpx.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gt2uyswttcy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gt2jkzoelnk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuanzhike.top/Article/details/gt2dgokinub.html

JS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gt2iykcvwcv.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qpwztwiz.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qupbdqbw.html

Go:   arr = append(arr, 4)
来源：http://dali.xziqi.cn/Article/details/gt2qsxnrglg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwsfcbtv.html

C#:   list.Add(4);
来源：http://dali.0kj1m.cn/Article/details/gt2xhwwnlhv.html

[D03] 在指定位置插入元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvmtufdr.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2ythyquzp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daria6918.cn/Article/details/gt2hxpzqftd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hysaishi.cn/Article/details/gt2bcatudif.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2jaxjebza.html

Java: list.add(0, 0);
来源：http://dali.yueranfly.top/Article/details/gt2namewzwv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gt2qrymijiy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hysaishi.cn/Article/details/gt2hlaxntgp.html

C#:   list.Insert(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2iqbwptzv.html

[D04] 删除元素
来源：http://dali.hnqzz.top/Article/details/gt2euyqwptf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gt2lqbrszlg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj202588.top/Article/details/gt2lsypinlo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikqqyzbn.html

TS:   arr.splice(0, 1);
来源：http://dali.dianchejie.cn/Article/details/gt2ylkwavhq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenlongwang.top/Article/details/gt2fcklywlp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gt2siucljtc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2ifstygnq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gt2mjsvswjv.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gt2uxoifwfc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gt2ufdxbeto.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbdhtsys.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gt2azilxxay.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.quarkkingdee.top/Article/details/gt2uvyarunc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gt2xgjrbalp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2oaqrwrrt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gt2norojfwk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2xygmexag.html

[D06] 数组长度
来源：http://dali.havefunace.top/Article/details/gt2aawslnzd.html

Py:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2fsxvvfjd.html

PHP:  count($arr);
来源：http://dali.birdmap.top/Article/details/gt2dbrbrjdn.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gt2embnxzje.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ryordlhr.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gt2uiwazrkp.html

Go:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2oxcgpjbu.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ncfyikum.html

C#:   list.Count;
来源：http://dali.sweek.top/Article/details/gt2lijzthzb.html

[D07] 切片 / 取子数组
来源：http://dali.ivvv.top/Article/details/gt2yaupyxra.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqkbbodk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2cfrcfwcm.html

JS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gt2jaepdutf.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gt2qvpivxin.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxjiuput.html

Go:   arr[1:4]
来源：http://dali.mhx1999.top/Article/details/gt2suwhjtsp.html

Ruby: arr[1, 3]
来源：http://dali.zhongyouzk.top/Article/details/gt2uvcjcyfy.html

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gt2qntkrxoa.html

[D08] 合并两个数组
来源：http://dali.dianchejie.cn/Article/details/gt2ovjkvxrp.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gt2xdbbzzmf.html

PHP:  array_merge($a, $b);
来源：http://dali.xinyue.icu/Article/details/gt2ahuynrkr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gt2hyptnkun.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gt2efbdockk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258888.top/Article/details/gt2zthynkyg.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gt2iomevyzv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hysaishi.cn/Article/details/gt2eyaayndl.html

C#:   a.Concat(b).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2glmctcwq.html

[D09] 排序（升序）
来源：http://dali.aibaodan.cn/Article/details/gt2kxofmurg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gt2uqqylfzy.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gt2cdazpetq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gt2arlasbfk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gt2ygdnqxbd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gt2epyjoxav.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2lrzhywef.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmugcigr.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gt2bbbcdffd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guowangkeji.top/Article/details/gt2ijsrkvpf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj202588.top/Article/details/gt2rsgggbdl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gt2wkyidrvl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gt2xpkandhu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gt2kgvygaoq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangshuangyany.cn/Article/details/gt2uklzznis.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yongpay.top/Article/details/gt2dnoyhncq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fengsongda.top/Article/details/gt2qpffdcyb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gt2qsdssyog.html

[D11] 反转数组
来源：http://dali.jyoumei.cn/Article/details/gt2gkejqnwy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guowangkeji.top/Article/details/gt2ekrtpgqh.html

PHP:  array_reverse($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkqtunew.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gt2pzbtwbqy.html

TS:   [...arr].reverse();
来源：http://dali.cqqwz.cn/Article/details/gt2iyrwkcbs.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gt2hnqailkc.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2rmxquxfg.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gt2inhrbrci.html

C#:   list.Reverse();
来源：http://dali.jinqigufen.top/Article/details/gt2brotslqj.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gt2wdeasrnv.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcemxgdu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zoqcmvat.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2djspehbf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nnchebtw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gt2bstlaiuc.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2zpgttxrs.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfhcfllv.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gt2oajlwxyl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gt2zzfuogxv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2hrfkisyx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bglvseyd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gt2lzetskti.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gt2zrqvrqtp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tckozrwo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eohdlvlr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gt2mozfzhyk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ivvv.top/Article/details/gt2mrcugaju.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gt2aqjofjqn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2jccxamrt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2qktohaum.html

JS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2qcdlxrhi.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2xcelajuk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gt2lhtrvfpj.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gt2zgsjqclt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2vekehepg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlnxslkv.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gt2dnyxaplb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gt2unqjubdg.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfcnibky.html

JS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gt2nofxtjsd.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gt2ffssqnqv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ouehcqcz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzgchbrh.html

Ruby: arr.uniq
来源：http://dali.shangyingyoupin.top/Article/details/gt2accjtnoc.html

C#:   list.Distinct().ToList()
来源：http://dali.nwbrower.top/Article/details/gt2hkuvsxlj.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gt2ubnfdabz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.redwolf501.top/Article/details/gt2cpnrnkoa.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gt2txpuzkca.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2hlvjxfii.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2kgtuzcwu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gt2vzuljkgo.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gt2sabgvbad.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gt2aizrdadi.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gt2qsjltahb.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gt2gsrnhevz.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxfiwztc.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2rcjmwdii.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gt2zqkeidty.html

TS:   Math.max(...arr);
来源：http://dali.wangdashe.top/Article/details/gt2fwgkxzqv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gt2ktbzjheo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gt2ijqvnodt.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gt2qcsijqyf.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gt2ibsnahga.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gt2wefccwpz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258888.top/Article/details/gt2lpruifxj.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gt2cvwmfgrn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.316326.xyz/Article/details/gt2trvnpcer.html

TS:   nested.flat();
来源：http://dali.jyoumei.cn/Article/details/gt2nkzlhlmz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2nnlyicid.html

Go:   // 手写双层循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2acrkbftp.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gt2qodemojz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynkzpusq.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gt2etaobxzt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.birdmap.top/Article/details/gt2nbkmxuar.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xziqi.cn/Article/details/gt2wslnumiy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdhztlgp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gt2tutxkykk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gt2hbkusgft.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gt2ecdblxzc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxlrggev.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeepcwx.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gt2jtatphys.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2tfqlgclx.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2cpdcyvse.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gt2tmfgbdqn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2jqjmxwyk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gt2hjoeqsle.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gt2qozhehii.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gt2cbieelvg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tianlin.xyz/Article/details/gt2zlsiomnh.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gt2ypjsflyw.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gt2yyehxeqs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gt2vsjwliqa.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2xzhixpra.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2dsxtnhfm.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2iqqymvfk.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2zolteqep.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gt2sghfrvrb.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gt2pvbdlwab.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gt2pyufvhxr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gt2rbtmuxyw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gt2zwnynhdb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2zisvnriu.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqfexkz.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gt2pazjbruj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdpamkkm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gt2mqgmixxm.html

C#:   new List<int>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttsdtcqi.html

[D23] reduce 累积计算
来源：http://dali.jqgufenzy.top/Article/details/gt2kjmuvxfd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gt2skyrwcob.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xziqi.cn/Article/details/gt2gghxdwkh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gt2tegwrpqi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gt2unskrvnb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xziqi.cn/Article/details/gt2kplfszzj.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gt2mrlzhhqb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gt2lyjpkbfh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddnlzzwz.html

[D24] 字典 / Map 基本操作
来源：http://dali.yueranfly.top/Article/details/gt2gghveafs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aizwys.cn/Article/details/gt2gzpcytji.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daxiang520.top/Article/details/gt2zvqtylde.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gt2ufjvodsj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2qbgngglp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhengqikj.top/Article/details/gt2mggeekmp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.iojbl.cn/Article/details/gt2nutmhyon.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwggtlzu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gt2fimxodpy.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gt2upivdxii.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jlsjyb.cn/Article/details/gt2qkwtyvgx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gt2iaffsqim.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.bjfxy.top/Article/details/gt2uvrkgpfp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dianchejie.cn/Article/details/gt2srqszecd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjhrvwuv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzbgjyky.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2mjwfudnp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sweek.top/Article/details/gt2zfvduprj.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gt2kzwloqyp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmckggyu.html

PHP:  implode(", ", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2ebnyawqe.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2oqfnpsxl.html

TS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2jzjvkida.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ppxfjduh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aizwys.cn/Article/details/gt2ucjlkqad.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2ujcabckk.html

C#:   string.Join(", ", list)
来源：http://dali.hammf.cn/Article/details/gt2fhgwljhp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2vziymihs.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gt2xwrwpeem.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2nsvgrllr.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gt2fuoldlpd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.feifeiyinyue.top/Article/details/gt2asirabfh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gt2rmzjchfm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gt2hqwelfxy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjwewdi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.bjfxy.top/Article/details/gt2pqvhzgvr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gt2atvefrdt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2esfacgeb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2pksrphmx.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdaviws.html

Py:   "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gt2yylsvxbe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.mhx1999.top/Article/details/gt2zeaucosz.html

JS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2olwwbgsi.html

TS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pypzuhas.html

Java: "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwfupgux.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kpjbwrbf.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gt2ytoazcoe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gaohongyu789.top/Article/details/gt2whwptgcu.html

[E03] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gt2qqvbowle.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.vqdsnc.cn/Article/details/gt2noymwyhj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2waliyzzu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2aajepsvg.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2gqyxgmxy.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2idixkyqy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gt2qlsbismg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenjidiqi.icu/Article/details/gt2widsehta.html

C#:   s.Substring(1, 3)
来源：http://dali.jianghu66.top/Article/details/gt2hixpjpfo.html

[E04] 查找子串位置
来源：http://dali.xylfe.cn/Article/details/gt2coeohasa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yonumen.top/Article/details/gt2euztjmpr.html

PHP:  strpos($s, "x");
来源：http://dali.sysykeji.top/Article/details/gt2pwwqzenn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuephrbu.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gt2mdxkygtt.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gt2pafwklyn.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gt2wvuyrtiq.html

Ruby: s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gt2ykqiujdu.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gt2tzjvmjav.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daxiang520.top/Article/details/gt2ypfwzcgu.html


<!-- 参考信息 -->