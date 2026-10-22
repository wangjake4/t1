代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gt2zsmnhvgl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gt2wzavfugd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmwpbvbu.html

Ruby: # 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2tjeqzvde.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jianghu66.top/Article/details/gt2dgavfhqr.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gt2hskentou.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gt2adqwxiew.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vpzgeoft.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ccsiirvu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gt2tmeufrwy.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2dciyijyb.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gt2vbxpzhbz.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gt2fuzcacyo.html

C#:   var (a, b) = pair;
来源：http://dali.tanke756.top/Article/details/gt2omydsbcw.html

[C16] 函数 / 方法重载
来源：http://dali.fengsongda.top/Article/details/gt2plqsikuv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gt2pzqcfvbb.html

PHP:  // 无重载
来源：http://dali.ivvv.top/Article/details/gt2crrrflkn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gt2fnqjpxil.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gt2egatnswz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gt2jegzagsm.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gt2fawuqiks.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sufxvd.cn/Article/details/gt2cwgpldoq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gt2mdahdegn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2xtpvuxry.html

D. 数组 / 列表 / 集合
来源：http://dali.ppjwa.cn/Article/details/gt2gawluwxc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2mtyzkduu.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgjoinnk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhixingplan.top/Article/details/gt2hykfclsl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gt2fbrzufdz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gt2ogcxxstp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gt2nswusmee.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gt2ejlzvacj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gt2witkdapq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2dkvufwev.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gt2ceckhogt.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypqaktti.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gt2atolpzxm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndzndico.html

JS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gt2ogdblpqw.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gt2txlpxyyz.html

Java: list.add(4);
来源：http://dali.gzhubu.top/Article/details/gt2yokpgmal.html

Go:   arr = append(arr, 4)
来源：http://dali.yueranfly.top/Article/details/gt2roagkyxk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxstirmq.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqmsejkg.html

[D03] 在指定位置插入元素
来源：http://dali.yvedp.cn/Article/details/gt2faydtepm.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2xlvkvzby.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bspshqxw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gt2adjqmdbb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2jbpfakyl.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppdmslrw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ppjwa.cn/Article/details/gt2mevdoelc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gt2vpcaullw.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2ertyqbte.html

[D04] 删除元素
来源：http://dali.jinqigfzy.top/Article/details/gt2ymynzhsd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2byfieumg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangdashe.top/Article/details/gt2yrdnrasj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yongpay.top/Article/details/gt2omzhkuxs.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gt2oyourxqu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jiagoushi.top/Article/details/gt2irbmiggl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.0kj1m.cn/Article/details/gt2hnwmeqib.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.9152youxi.cn/Article/details/gt2hctlgzid.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gt2vtrnhyhw.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gt2rqdmztjf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gt2qzusbroz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2hqrpqhbz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gt2tzyquvki.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lemfutrj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aizwys.cn/Article/details/gt2mumwqwlr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gt2goiugqiu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gt2aaxoemzv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hammf.cn/Article/details/gt2xsrvxsar.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gt2ditrjnkw.html

Py:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gt2fjqnfffu.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2hoqberlg.html

JS:   arr.length
来源：http://dali.yonumen.top/Article/details/gt2mvwybbjg.html

TS:   arr.length
来源：http://dali.tanke756.top/Article/details/gt2uxpadqmb.html

Java: list.size();
来源：http://dali.jinqigfzy.top/Article/details/gt2xagwkgrr.html

Go:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gt2doitgnhu.html

Ruby: arr.length; arr.size
来源：http://dali.yonumen.top/Article/details/gt2ybiaszea.html

C#:   list.Count;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdykgkkx.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gt2fazxmfon.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhengqikj.top/Article/details/gt2wzkipndl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gt2jmlcsxyd.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2uqcwcxuc.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2yhqzvabc.html

Java: list.subList(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2zwnawslf.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfjmanzl.html

Ruby: arr[1, 3]
来源：http://dali.wangdashe.top/Article/details/gt2sqaorbps.html

C#:   list.GetRange(1, 3);
来源：http://dali.shuidangran.top/Article/details/gt2vxvddmtj.html

[D08] 合并两个数组
来源：http://dali.xinyue.icu/Article/details/gt2ffnqlflc.html

Py:   a + b;  a.extend(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmhtretn.html

PHP:  array_merge($a, $b);
来源：http://dali.jianghu66.top/Article/details/gt2hvgybvgm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aizwys.cn/Article/details/gt2klrooeie.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gt2szhzejxv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2kjrfljqo.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2msqrqnkg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwmhgukw.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gt2fuvjakah.html

[D09] 排序（升序）
来源：http://dali.daxiang520.top/Article/details/gt2vbvealpm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2rowgyqyx.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2iypvqwam.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gt2pxqpozpw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gotoacloud.top/Article/details/gt2edlqhkfz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gt2tgepyppw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gt2xhdzwgme.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gt2ptcanzsv.html

C#:   list.Sort();
来源：http://dali.jyoumei.cn/Article/details/gt2mipqjcjx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cqqwz.cn/Article/details/gt2mjicbhsx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gt2ahqsawcx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gt2rfgcqmqb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gt2xykdihps.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gt2rvmyswpx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhixingplan.top/Article/details/gt2djbcihmb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yueranfly.top/Article/details/gt2vyvisrxk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guannengcc.top/Article/details/gt2mynaeeqv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gt2hrdvoymf.html

[D11] 反转数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxedlizz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gt2zkeyorxl.html

PHP:  array_reverse($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2tfslnnia.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gt2muivdjyl.html

TS:   [...arr].reverse();
来源：http://dali.xylfe.cn/Article/details/gt2nyueaqjr.html

Java: Collections.reverse(list);
来源：http://dali.xuanzx.com/Article/details/gt2mjiqibrh.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gt2gpmsqtld.html

Ruby: arr.reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2xzgpetpq.html

C#:   list.Reverse();
来源：http://dali.yuxming.cn/Article/details/gt2pyccpakf.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2envtcjpy.html

Py:   arr.index(x);  x in arr
来源：http://dali.iojbl.cn/Article/details/gt2pgksgsym.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tian-w.cn/Article/details/gt2amjurqrw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2pfbuxxio.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2cfvzeigh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gt2tkiuvviv.html

Go:   slices.Index(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mucizeyu.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gt2bwwnswie.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gt2uczvgdfa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gt2qwjnkiyh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gt2ddoglbyc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2fhixhjbj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gt2zsxudsdi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2obhfcyes.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2gzccwkoo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gt2rifbqahh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gt2xzgrrmuw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtwpkfkx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gt2zfahzyny.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2ywjhxvko.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.iojbl.cn/Article/details/gt2lelttxow.html

JS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gt2nfjstkam.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gt2fozrkcie.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmhxcgkc.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gt2dnnmpiic.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gt2nociibvc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2eshemjhr.html

[D15] 去重
来源：http://dali.zycfv.cn/Article/details/gt2eniztwuq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwkmqyvm.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2qrdeyjuu.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2jrbnetrt.html

TS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gt2cqwwvwia.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gt2pvuvhthb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gt2gqqshuxh.html

Ruby: arr.uniq
来源：http://dali.ivvv.top/Article/details/gt2zbwczpvh.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2tvehvdzi.html

[D16] 求和与平均值
来源：http://dali.cdnleiting.top/Article/details/gt2glmittuo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuxming.cn/Article/details/gt2pmvfkyzg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2ekgtydxm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2nnuiztvr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2qlcnmkxt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gt2esltbkaw.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gt2bmzyeqja.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gt2ltpxguto.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gt2rckvyany.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gt2ghdqeulu.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2juzjjbph.html

PHP:  max($arr);  min($arr);
来源：http://dali.havefunace.top/Article/details/gt2kjosmhfq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gt2nqnrbcib.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gt2cbrowgal.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gt2jgdhhhvj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2odgcapmc.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gt2tzpxdgpo.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gt2gpitwwjw.html

[D18] 扁平化嵌套数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2qotdbrzc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gt2wfjhmwlh.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gt2cbtyteab.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zsveyzjb.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gt2qqntcvll.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuanzx.com/Article/details/gt2nuvvnlar.html

Go:   // 手写双层循环
来源：http://dali.bjfxy.top/Article/details/gt2zsqftsik.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gt2ludmmwrl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2oepdagen.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gt2eqgacndd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gt2xhzdwxoq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gt2hbbkqysm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqlxlakx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gt2eqsipefk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gt2jqgpvzpd.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gt2ursbsvxg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gt2uthxvuho.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cheryme.top/Article/details/gt2beqajlcs.html

[D20] 统计每个元素出现次数
来源：http://dali.cheryme.top/Article/details/gt2lknxatqr.html

Py:   Counter(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2phgysdrr.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gt2mudxeksi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gt2icbfgddx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gt2uudsnako.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gt2mvxwffnz.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygkdgpfw.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gt2zucbnuss.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gt2ttudeybi.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gt2lbxppieu.html

Py:   x in arr
来源：http://dali.sweek.top/Article/details/gt2mbuxrcaq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yongpay.top/Article/details/gt2tffeedxe.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2ehwoieph.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2ciliunst.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2hgbbepxy.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2fexyibbs.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gt2eqpujqho.html

C#:   list.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrrpzaby.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gt2bujxkzpv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2jtadopvs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gt2tegeragz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2tajgsnns.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gt2ihtscdfh.html

Java: new ArrayList<>(list);
来源：http://dali.nwbrower.top/Article/details/gt2igdmesyr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ydzc1.top/Article/details/gt2awkhxdmk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gt2lfiktbfh.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gt2livhpmtf.html

[D23] reduce 累积计算
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqzobifl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2shalkeva.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shuidangran.top/Article/details/gt2yvrxxjhh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2aeiepuyz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2rnbqzgcv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.snrcjt.cn/Article/details/gt2sykpeqcx.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gt2hirkxhay.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gt2pgxiyqxe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfzthebo.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxhwiknr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gt2udlzxubw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gzhubu.top/Article/details/gt2nvhxekgy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gt2anppmkof.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ftrkmbox.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2ylzzedzb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uldzjjni.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zycfv.cn/Article/details/gt2iqvdjfcg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gt2wlcmzbzi.html

[D25] Set 集合去重与交并差
来源：http://dali.gogol.net.cn/Article/details/gt2yxswsoce.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gt2zmapmsby.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gt2hbwdxlcj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gt2yzbnvknt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gt2cioespyc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gt2unalherk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yueranfly.top/Article/details/gt2eftzurun.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gt2ihsbnqpu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gt2yjddmiup.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2rralxluj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aibaodan.cn/Article/details/gt2ngbqrlku.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gt2fslabdly.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kyfndjzs.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gt2evypyjak.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gt2vfiugxeb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gt2kggfnslw.html

Ruby: arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gt2ouzgrpwv.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gt2vczwilcp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2wszyccvy.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gt2xqhfjhrn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2fpgpsoui.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2kglguyib.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gt2libgnqhg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gzhubu.top/Article/details/gt2zdnexkva.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gt2ozzfmcji.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gt2xtelypub.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgrirpnh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj202588.top/Article/details/gt2tsdgqmcu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gt2ifyahcmt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2wiwijwsv.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gt2iefbfbzt.html

Py:   "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gt2xrhvqkea.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2gmpkxere.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlwbegen.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2rjjupfln.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2xqzgfrqq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hfpthk.cn/Article/details/gt2htpoqsmr.html

Ruby: "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oyzjdvml.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gt2wtxkthht.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gt2bdxwcmcc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gt2vzprufvd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2htuhfshb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hpwtiwhv.html

TS:   s.slice(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2afejjtna.html

Java: s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2bcdspfnt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.9152youxi.cn/Article/details/gt2euvhdite.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yvedp.cn/Article/details/gt2dpubvvfi.html

C#:   s.Substring(1, 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2pxxyvvcv.html

[E04] 查找子串位置
来源：http://dali.yongpay.top/Article/details/gt2tuiqkgyi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gt2zwhcydqy.html

PHP:  strpos($s, "x");
来源：http://dali.0kj1m.cn/Article/details/gt2qhxyoqxr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gt2hmptmhen.html

TS:   s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gt2amxbjwud.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2cqffblfi.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gt2uprbbjne.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gt2hfniwwun.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gt2nhuoqwiq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pengpengdd.cyou/Article/details/gt2sntzznit.html


<!-- 参考信息 -->