代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gt2pmuwxqdz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgreeowy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuxming.cn/Article/details/gt2moaimajl.html

Ruby: # 无泛型
来源：http://dali.dashuyun.cn/Article/details/gt2qvhqhznr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gogol.net.cn/Article/details/gt2rpvrcfqv.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2egxsedww.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzdpvnfs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2loqqptsi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbcnpztg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2wvmcqujn.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2ydppisva.html

Go:   // 无解构
来源：http://dali.ehwqpu.com/Article/details/gt2zxgjkckf.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gt2uvhynjjt.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gt2kdqqxyik.html

[C16] 函数 / 方法重载
来源：http://dali.aizwys.cn/Article/details/gt2zpzkvgsh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gzhubu.top/Article/details/gt2fsluruxv.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gt2melreacw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gt2yngmbpks.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhizddxg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yzxfbjyh.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmxzrhdu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jiagoushi.top/Article/details/gt2irfwpdff.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2nylwppgw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2wxfetbcm.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwnekptd.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2bdfvhaua.html

[D01] 创建数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gt2myvxaubj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jlsjyb.cn/Article/details/gt2hchdohhx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gt2pmezrwjs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gt2hypnentk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ybcxt.top/Article/details/gt2cqkkkrvj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yongpay.top/Article/details/gt2zudzpvlu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gt2pzqbupgu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gt2rapikfkx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hammf.cn/Article/details/gt2stqbzart.html

[D02] 追加元素到末尾
来源：http://dali.aizwys.cn/Article/details/gt2algqludp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gt2fsdevlda.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuanzx.com/Article/details/gt2bbflucom.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gt2scwtiasu.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gt2zcasbfrd.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzuiozqh.html

Go:   arr = append(arr, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vrsqqnfn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sufxvd.cn/Article/details/gt2dzbxztmr.html

C#:   list.Add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2apugcfec.html

[D03] 在指定位置插入元素
来源：http://dali.zhixingplan.top/Article/details/gt2fwhqanzw.html

Py:   arr.insert(0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2gopikytm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gt2roayauzz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gt2scpyeezl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2eadclrjy.html

Java: list.add(0, 0);
来源：http://dali.yueranfly.top/Article/details/gt2eimbuuwg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gt2xnoylrhy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hysaishi.cn/Article/details/gt2oecuvxux.html

C#:   list.Insert(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2hynqxvam.html

[D04] 删除元素
来源：http://dali.dianchejie.cn/Article/details/gt2grhakkif.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gt2tcezvkif.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2hkbtsjid.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gt2xmmxvdhk.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gt2chkrdgtr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gt2qdvscloe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2polfkqkh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daria6918.cn/Article/details/gt2vrezoywq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gt2jsuruuez.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gt2srcqfnku.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2ltslzbcn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2othwbfur.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvxyrzhc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jlsjyb.cn/Article/details/gt2hbyvtkoi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gt2skgcpzlz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gt2exjgmrco.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2logidcpw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2mtxvdwmn.html

[D06] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdmzoglf.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2owuuosdr.html

PHP:  count($arr);
来源：http://dali.yvedp.cn/Article/details/gt2cbbjbbnn.html

JS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gt2dxxkhefm.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gt2mhmdwqeq.html

Java: list.size();
来源：http://dali.daria6918.cn/Article/details/gt2tqevulbz.html

Go:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gt2wwooeemg.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gt2cwehexxg.html

C#:   list.Count;
来源：http://dali.shuidangran.top/Article/details/gt2ypxxxiho.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigfzy.top/Article/details/gt2kbvhlzcl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gt2rjdswukb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yueranfly.top/Article/details/gt2qokupwsg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpnmfnfy.html

TS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfropaiy.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fosryevo.html

Go:   arr[1:4]
来源：http://dali.gogol.net.cn/Article/details/gt2elebnenh.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxbxbsdf.html

C#:   list.GetRange(1, 3);
来源：http://dali.yongpay.top/Article/details/gt2wrfbymhx.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqfwtzzy.html

Py:   a + b;  a.extend(b)
来源：http://dali.mhx1999.top/Article/details/gt2niwsdgfp.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gt2zpkvccqs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lcmfsmmm.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gt2rccthxuc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgmonqvl.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gt2lwcfhuez.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swqtipzb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2ppzguilo.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gt2jlrhcxpl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gt2gjgiyifn.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gt2gqsmzjgi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztgvkxnu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenlongwang.top/Article/details/gt2izzgggbf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gt2cymgezbt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjyvbpt.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gt2nldfwtpa.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlbwoet.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258.top/Article/details/gt2emfvswqc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xinyue.icu/Article/details/gt2fqkqwzhs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gt2kyztswfa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gt2plyanenw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gt2pocmecrp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gt2jcmsjfka.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gogol.net.cn/Article/details/gt2evguzeed.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jlsjyb.cn/Article/details/gt2qghpwwkn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gt2vpciqhlk.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gt2jwtmmmkd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qcapfwug.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gt2ryrikthy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xziqi.cn/Article/details/gt2lntuxzcz.html

TS:   [...arr].reverse();
来源：http://dali.sufxvd.cn/Article/details/gt2wiomrfuc.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdzoaure.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gt2catpzjqy.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gt2ubidycrk.html

C#:   list.Reverse();
来源：http://dali.jinqigfzy.top/Article/details/gt2kzdtovzf.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gt2thoiwzpu.html

Py:   arr.index(x);  x in arr
来源：http://dali.ivvv.top/Article/details/gt2ybbyjbhu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gt2luyoislj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gt2wrqrhcrr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gt2dykblatv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuetiantiany.cn/Article/details/gt2dufhcnce.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2tgerlavl.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gt2dabvbtvd.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvywfrsd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aibaodan.cn/Article/details/gt2unasxbgy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gt2rrihbzcw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gt2diamxpgj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2urtgtddc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2ksdhohal.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjnnybbu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gt2ivdnfpxw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gt2cztwswzy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2nbfcogaq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.snrcjt.cn/Article/details/gt2cqrrghdo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2vimsmsuj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xoolsygb.html

JS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gt2fkttufji.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2rzrmgbxs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2gcrpieux.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gihorjcr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2fwkuxtxu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gt2unujhipo.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gt2agtzyzfb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2nwlessif.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2smhyttfe.html

JS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2ejcezyti.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gt2ikyxiujt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gt2qxwkvwtm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gt2ezaoumem.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gt2kpyxvrqs.html

C#:   list.Distinct().ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdbvzmpq.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aapbmwrf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2fejogkdl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2whgoitsw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gt2rofhuvjv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gt2yfacpzae.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gt2kyabithw.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gt2vgfbxhqa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sufxvd.cn/Article/details/gt2kgpoyziy.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gt2zpwoijnd.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gt2dmchukrh.html

Py:   max(arr);  min(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2lfqenjrw.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2kiljowtw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yvedp.cn/Article/details/gt2gjdimdsq.html

TS:   Math.max(...arr);
来源：http://dali.tanke756.top/Article/details/gt2smawopxm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.bjfxy.top/Article/details/gt2ycciuhxl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2ejjjepee.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gt2xydovjxw.html

C#:   list.Max();  list.Min()
来源：http://dali.hammf.cn/Article/details/gt2btuaozsp.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gt2nbyyuuob.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.snrcjt.cn/Article/details/gt2mtojmslo.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gt2vfibqrtm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.iojbl.cn/Article/details/gt2vtdkodnk.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gt2nbdoyheu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gt2xztabzxg.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gt2whkkxuku.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gt2lxrefyjw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2rlmmpzmo.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gt2ynuopwwh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yvedp.cn/Article/details/gt2zoiguvfq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdoqzpdv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gt2gsbgskrw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gt2jkafvxzw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gt2hlhibqve.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gt2xrvjytin.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gt2eoblhvjp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gt2qtxrbbxv.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gt2gnlhxxdr.html

Py:   Counter(arr)
来源：http://dali.yonumen.top/Article/details/gt2uphthevn.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gt2cdzaexpu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gt2zrfbhhlr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gt2exbztpkr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cdnleiting.top/Article/details/gt2sakvhtau.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gt2nrtssioj.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gt2brmmvjgf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gt2gsdoowlq.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gt2kadgvwtb.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gt2gcjbzpry.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fuxdkucm.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gt2ovsklsnk.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2hvpcirdo.html

Java: list.contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2azqpuyre.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsheftgw.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gt2obkdrgip.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2mumlefvm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sufxvd.cn/Article/details/gt2yhyfkwln.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2yrrcviif.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gt2kzmhzjsn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2scvfrrgs.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vjimkvna.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gt2kgdgmadw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cashguo.top/Article/details/gt2samxjswu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.kuanghao11.cn/Article/details/gt2itbcskjl.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2krzyhsdt.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmxvxzuz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cashguo.top/Article/details/gt2szwqtygd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.bjfxy.top/Article/details/gt2mnbguvrj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2kzigqfyx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gt2muvsiqhn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gt2kamagipj.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2rfuyaikt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cdnleiting.top/Article/details/gt2gpmnhxxc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ydzc1.top/Article/details/gt2deyaghnv.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gt2zupfwwxq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj202588.top/Article/details/gt2xdaoqzjv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gt2rxfbihth.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258888.top/Article/details/gt2nouuhdei.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2folyibng.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cqqwz.cn/Article/details/gt2jsutqvvw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhoulong.xyz/Article/details/gt2znfilbkn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgfzy.top/Article/details/gt2ljpwyydk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.haohaochexian.top/Article/details/gt2phckreys.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gt2azpbkohf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gt2uzjrsuke.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.bjfxy.top/Article/details/gt2svqjfrrp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xinyue.icu/Article/details/gt2tuvxpqal.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gt2gknqfnkh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hysaishi.cn/Article/details/gt2rlfhenjq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqihgkhf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxvrtgya.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yangfankeji.com/Article/details/gt2lrvczyhd.html

[D26] 数组转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2pkxiuuqg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gt2ehslfffo.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2fniaofne.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2xtufczau.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2ehajwuuk.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gt2dcfwuiof.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258888.top/Article/details/gt2kpwzfrwx.html

Ruby: arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2azbnnzbe.html

C#:   string.Join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gt2cojpaliw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ghwdvlvj.html

E. 字符串处理
来源：http://dali.gotoacloud.top/Article/details/gt2exusbtrf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2dkqcrvel.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gt2yyxhdzzv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zycfv.cn/Article/details/gt2napixxyn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gt2ixopsklp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2gpapaumn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xscpxywl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gt2gxmwagrn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gt2qetudxgn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gt2mqhgoqri.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2zaucinfu.html

[E02] 重复字符串
来源：http://dali.yueranfly.top/Article/details/gt2unymehlj.html

Py:   "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2zktrobde.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gt2gsxcxglz.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2rhqqbemz.html

TS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2mylbnlgq.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2yryqzdhm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhengqikj.top/Article/details/gt2qkvrphqg.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2feyfuawz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hysaishi.cn/Article/details/gt2naekbsmk.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gt2uzdjecay.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gt2yanwjbfw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2xcdlfxpf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gt2jkioydrl.html

TS:   s.slice(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsyglouv.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erilxojl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2txkaibeu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fzhhl.top/Article/details/gt2agrobqaw.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gt2xrljexae.html

[E04] 查找子串位置
来源：http://dali.hnxiangtu.top/Article/details/gt2zufvghiv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gt2atdsbpbe.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gt2zveopdvz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.smart0.xyz/Article/details/gt2vmhasdsx.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gt2irmjtqcp.html

Java: s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2rjvabtyd.html

Go:   strings.Index(s, "x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mksvlhqi.html

Ruby: s.index("x")
来源：http://dali.tian-w.cn/Article/details/gt2fimyjsrw.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gt2ruudmxwr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szililmw.html


<!-- 参考信息 -->