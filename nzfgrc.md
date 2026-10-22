代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gt2uolrpdiq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tanke756.top/Article/details/gt2nrzthzur.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgufenzy.top/Article/details/gt2rvbtunwl.html

Ruby: # 无泛型
来源：http://dali.guowangkeji.top/Article/details/gt2omddfcnv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ehwqpu.com/Article/details/gt2sotxppjg.html

[C15] 解构 / 展开参数
来源：http://dali.yangfankeji.com/Article/details/gt2mxmhprcp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gt2wlcobjxn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gt2eiklkwas.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gt2wuzlbgdt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.9152youxi.cn/Article/details/gt2nhljydlg.html

Java: // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gt2hhtxdhnb.html

Go:   // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gt2tgjsqmbx.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gt2kcxchsyn.html

C#:   var (a, b) = pair;
来源：http://dali.ydzc1.top/Article/details/gt2pxuhcbkw.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gt2bbchsifz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigfzy.top/Article/details/gt2tixmmhdm.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gt2sbshwsfq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucruvltf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fengsongda.top/Article/details/gt2rtfbxpzs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2spnsmeuo.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gt2xdpimriz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj202588.top/Article/details/gt2xzcxmgco.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gt2ejoqqvnx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2mfqxlhya.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gt2rcspydwv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2hlduqjrh.html

[D01] 创建数组 / 列表
来源：http://dali.jianghu66.top/Article/details/gt2lyuswzik.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jianghu66.top/Article/details/gt2hevgnaln.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzeoaoso.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258888.top/Article/details/gt2rggfqsuw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjgiscza.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gt2xjvpufuh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gt2mlsntahi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhongyouzk.top/Article/details/gt2pmsokmse.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjciuggn.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbpzpbw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zffiwopa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.redwolf501.top/Article/details/gt2srrhlzqn.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hujjpdcg.html

TS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gt2gbkkmbxa.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gt2brioriha.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjspkfue.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xinyue.icu/Article/details/gt2huixpswk.html

C#:   list.Add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yktophja.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gt2njbwhqdh.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2mesaowqw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fzhhl.top/Article/details/gt2jaesuyix.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tianlin.xyz/Article/details/gt2bprvtxzy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2ojaywovb.html

Java: list.add(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2lvwecuxv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shuidangran.top/Article/details/gt2xweaqrhr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhongyouzk.top/Article/details/gt2vxugkvba.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2siijunvh.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gt2xweejhoz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gt2gcjxgbbr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gt2doauxmsv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangdashe.top/Article/details/gt2vjdjtsel.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gt2esxuwwqb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2mhtikyzk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gt2aduuuiit.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangdashe.top/Article/details/gt2rgcjtoub.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yvedp.cn/Article/details/gt2zphnjzwl.html

[D05] 访问与修改元素
来源：http://dali.jlsjyb.cn/Article/details/gt2hgukqpwu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2gifmblvy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2wvfbcgqz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2hryelqpj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gt2ytgpdxxl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gt2oqgkebng.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gt2zebmttzg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2tffdobid.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2ohxkbwkc.html

[D06] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhjpntvr.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2entakgsf.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gt2htauhdde.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gt2vuulauzx.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gt2jezschkj.html

Java: list.size();
来源：http://dali.ppjwa.cn/Article/details/gt2pyqawjje.html

Go:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gt2stqmfiah.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gt2phbrhiht.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gt2atasnbyp.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gt2wvvsmlaw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gt2rzpymsea.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cdnleiting.top/Article/details/gt2fpheubub.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2brrywrkj.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gt2ylwsaauq.html

Java: list.subList(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2fjlnmnhu.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gt2hflpdwxq.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gt2vuplesul.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gt2bznzhtaq.html

[D08] 合并两个数组
来源：http://dali.shzxlz.cn/Article/details/gt2jjzygebq.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gt2qkhtvzhw.html

PHP:  array_merge($a, $b);
来源：http://dali.chenlongwang.top/Article/details/gt2oikjrmcx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gt2ingwrkfw.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gt2bieumrqu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2xdneykci.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gt2ouvrexwn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xziqi.cn/Article/details/gt2tkbqoheu.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gt2kswprnuk.html

[D09] 排序（升序）
来源：http://dali.hongshengwenyu.top/Article/details/gt2kadycdir.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gt2ytdwyjly.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gt2pqstjlvk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.svipenyu.cn/Article/details/gt2xkbwagsp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yueranfly.top/Article/details/gt2vyjpjrix.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dianchejie.cn/Article/details/gt2icbunetv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gt2xddcnilu.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gt2bymxoohp.html

C#:   list.Sort();
来源：http://dali.ydzc1.top/Article/details/gt2xvpncezj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gt2acwtpbpa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gt2ojvpomun.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gt2nrhreorc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2vmnmesce.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gt2zxgakewf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shzxlz.cn/Article/details/gt2ceccwtpr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgfzy.top/Article/details/gt2wznkxnjm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.mhx1999.top/Article/details/gt2pkovande.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.kuanghao11.cn/Article/details/gt2qjzdpnaq.html

[D11] 反转数组
来源：http://dali.andypj.xyz/Article/details/gt2gqzgatlx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jianghu66.top/Article/details/gt2wzpnzjap.html

PHP:  array_reverse($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2mctnpmlk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gt2xvkexzfa.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gt2ljsjvfch.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttzuzcoc.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrlsiwo.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gt2qakionpd.html

C#:   list.Reverse();
来源：http://dali.andypj.xyz/Article/details/gt2qdhpbjoq.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gt2pkmlvkzq.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigufen.top/Article/details/gt2gnklmmuy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tanke756.top/Article/details/gt2jkbhrmiz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2dqtyxcvn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gt2cyrltpuq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gt2fwzxavgr.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2kfoyxwqb.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gt2ztnbojam.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zoyvxyri.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gt2ocepgaee.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2zswlbbrd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gt2ustajdps.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxhpxuje.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2esksllpn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2jdyrkjrv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gt2zabhblje.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangdashe.top/Article/details/gt2xkjwacwd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwiqexz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gt2hkbndbef.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aibaodan.cn/Article/details/gt2issijrkf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2kxxgyqut.html

JS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gt2fgformqn.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gt2mqvnaupb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gt2vjzujxbk.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gt2intxbfwm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2ppasbaub.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2ltttkucc.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2obcjilsy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2pywstxox.html

PHP:  array_unique($arr);
来源：http://dali.yj20258.top/Article/details/gt2vopomvvk.html

JS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gt2axqjpkxs.html

TS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gt2nbsymiza.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gt2izpjsukr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxuanxn.top/Article/details/gt2awfekcfe.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gt2udcmkmmp.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zaoiqlfy.html

[D16] 求和与平均值
来源：http://dali.wangdashe.top/Article/details/gt2wpwtwhuf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fengsongda.top/Article/details/gt2hgkgkrnh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2qjtsqscq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2aiiwgwgj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2osxgdoxf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gt2ryssoedx.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gt2ilbjyhxy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gt2uwdkbtdy.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gt2rncgtvbj.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gt2xckxysbv.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2fkihnppd.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuanzx.com/Article/details/gt2bkruoksq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jiagoushi.top/Article/details/gt2pndvrgrv.html

TS:   Math.max(...arr);
来源：http://dali.nwbrower.top/Article/details/gt2moihuhmh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gt2hxuxseex.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gt2frzrbzdq.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gt2ndihpkxj.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gt2gocavmmu.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gt2hhyucpxm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulgfnnpf.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gt2zjjxeixt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gt2glomqdnj.html

TS:   nested.flat();
来源：http://dali.tanke756.top/Article/details/gt2zdvtntye.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gt2rnzdslqx.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gt2eabiyuak.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gt2rymdaxfb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2rauvuloc.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gt2kblpphgz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnqzz.top/Article/details/gt2etaykouq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gt2ctyusqpk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gt2zikilzde.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gt2spbtkmmm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.vqdsnc.cn/Article/details/gt2xtszifmp.html

Go:   // 手写 map[string][]T
来源：http://dali.cashguo.top/Article/details/gt2rjcvijho.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gt2hpepfrvs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gt2usgxzfxd.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gt2skjhngka.html

Py:   Counter(arr)
来源：http://dali.sysykeji.top/Article/details/gt2zizymtcj.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gt2lqvqddup.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmqjipjm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gt2tadydlmz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gt2kfjlesxh.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gt2fjonxpeq.html

Ruby: arr.tally
来源：http://dali.xinyue.icu/Article/details/gt2xdtnnrph.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gt2nstfzqtp.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gt2ywsknbrk.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gt2iuycuxzu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gt2mjeevlgl.html

JS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gt2guombrva.html

TS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gt2dccutlxs.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2rsavotpq.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2qundxxdb.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gt2ynkopzej.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2fdfukhse.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258888.top/Article/details/gt2tcylizuf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2psciizsi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gt2gtsylheh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.andypj.xyz/Article/details/gt2efpqgjlq.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gt2irijssbn.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gt2vhacqyky.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhoulong.xyz/Article/details/gt2xtowquzw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cheryme.top/Article/details/gt2zbjkvfjv.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gt2augiyjzz.html

[D23] reduce 累积计算
来源：http://dali.vqdsnc.cn/Article/details/gt2pboymygd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2uwdsemdb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gt2kqkxqksv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gt2zrotwplg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2dfqyvnvc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjjtpdqj.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqqmspbt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258.top/Article/details/gt2navlmzjg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xinyue.icu/Article/details/gt2szlwfbaj.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gt2datlwrco.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gt2rwxxcsfl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gzhubu.top/Article/details/gt2wewvgsve.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2ydvopyvr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bohaivrt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2anibymxz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gt2ademvlpg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gt2zymfagmn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guowangkeji.top/Article/details/gt2vgpzycvw.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gt2kyoxcmze.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gt2aruvwxnx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sysykeji.top/Article/details/gt2viztdcwn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgknxjmj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2eaxgxzqp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hysaishi.cn/Article/details/gt2dvrarkty.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aibaodan.cn/Article/details/gt2klszgvse.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gt2fhwmtncd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.smart0.xyz/Article/details/gt2woujnkdv.html

[D26] 数组转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2foyhweto.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yonumen.top/Article/details/gt2cmlcffak.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2sdtitvus.html

JS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2fvywwwnm.html

TS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gt2pxhgevjl.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gt2apripmbc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gt2gfeluhlf.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2zqddebyo.html

C#:   string.Join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gt2akmsrorw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2kfgydkfy.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gt2cuqlgirs.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2jlyypqsb.html

[E01] 拼接字符串
来源：http://dali.shuidangran.top/Article/details/gt2xdykefye.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.vqdsnc.cn/Article/details/gt2szqwpllg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfkmgaua.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2srhmgsht.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2gxfnrtfu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.svipenyu.cn/Article/details/gt2arnlftdz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gt2lcmrvqds.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gt2debrxadc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2pdvreerh.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qninqqhz.html

Py:   "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gt2crwultao.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2ekuwydjq.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2wboumnhr.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vucmfojo.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2fenwoyfb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shuidangran.top/Article/details/gt2toalsjbs.html

Ruby: "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gt2zllueayk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gt2rqizliib.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gt2rgrrclwb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258888.top/Article/details/gt2vfvllmun.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2cvzejghe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqdoyivo.html

TS:   s.slice(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2cfvsttyv.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2mmhnwbht.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gownqvdz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ehwqpu.com/Article/details/gt2wsohfkob.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gt2zccvyfoe.html

[E04] 查找子串位置
来源：http://dali.gogol.net.cn/Article/details/gt2ftrnuija.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gt2spzxdoid.html

PHP:  strpos($s, "x");
来源：http://dali.wangdashe.top/Article/details/gt2zgokfmyh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gt2ktuvlaca.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2gezzhvoy.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gt2luelikip.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gt2kmcsfgus.html

Ruby: s.index("x")
来源：http://dali.guannengcc.top/Article/details/gt2hmyifbst.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2qfhmfmzy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gt2eefadieg.html


<!-- 参考信息 -->