代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.havefunace.top/Article/details/gtjlgjadrj.html

[C15] 解构 / 展开参数
来源：http://dali.nwbrower.top/Article/details/gteyrofdem.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yanxiufei.cn/Article/details/gtknspmrsx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tian-w.cn/Article/details/gtpqykzezp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gtezwbflqj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gttqeeoqrz.html

Java: // 无解构
来源：http://dali.ivvv.top/Article/details/gtgvubgwta.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gtsynkqdpg.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gtjaacewto.html

C#:   var (a, b) = pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtdwhcemjs.html

[C16] 函数 / 方法重载
来源：http://dali.svipenyu.cn/Article/details/gtosogbaeo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gtwzdusjfj.html

PHP:  // 无重载
来源：http://dali.iojbl.cn/Article/details/gtekpaamoz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cqqwz.cn/Article/details/gtuatexxif.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gtgycvhrzk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcopdrtly.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhiwuduotai.top/Article/details/gtqpnbxibf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.c1oappe.top/Article/details/gtihgaphed.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gtwfvzgcbx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtyctgwyrm.html

D. 数组 / 列表 / 集合
来源：http://dali.fengsongda.top/Article/details/gtzvfrtkew.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtyecreyol.html

[D01] 创建数组 / 列表
来源：http://dali.birdmap.top/Article/details/gtbskgrsga.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhoulong.xyz/Article/details/gtjxulstut.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gtcpsymruq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuanzx.com/Article/details/gtbqssgsqg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shangyingyoupin.top/Article/details/gtllsntkgd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gtlaskzxjx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xziqi.cn/Article/details/gtygxttwrz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gtfnxiyvdw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugcrakfk.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gtxamhfnoz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gtckzcqdna.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xziqi.cn/Article/details/gtyegkwenz.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtbekqvzgc.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwsltgjh.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtocttlupe.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtmlpxkbwv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gtjnwpiini.html

C#:   list.Add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbwgvwnu.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gtjxapcine.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtvsukumdn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigufen.top/Article/details/gtjirskxfv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gtoppshnxh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtcoubkkaq.html

Java: list.add(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtydttrzex.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cashguo.top/Article/details/gthrttzgnb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlodyordv.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtbyslctyi.html

[D04] 删除元素
来源：http://dali.redwolf501.top/Article/details/gtbqpnjbdf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gttihmemsb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtvkpjffsh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gtlufzafuk.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gtfvpvgouc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gtsfeqvfuw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gtqjdnqbty.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gtvqvbkipc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gtfbtbaaxy.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gtjfisyydn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtxlpoiwvj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtwdtmfjpj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtgwttdzly.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dashuyun.cn/Article/details/gtoteebzex.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gtaqrjforz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gttugwzolq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkaluyhxq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtiaauiagl.html

[D06] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtislkdjzp.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtqtphbwjw.html

PHP:  count($arr);
来源：http://dali.chenlongwang.top/Article/details/gtbikmxjhj.html

JS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtootsdzvc.html

TS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtholjqrbe.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmciwhlm.html

Go:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtwwdqhanf.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gtzxassqtj.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gtnmnjpjcw.html

[D07] 切片 / 取子数组
来源：http://dali.shzxlz.cn/Article/details/gtldezyebm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sweek.top/Article/details/gthbxvfqna.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ivvv.top/Article/details/gtuninotnw.html

JS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtfnwdefud.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtwxuuardm.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtmdbgnstw.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gtejicucao.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtoksopojg.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gtgipuaebo.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gtifxhlpks.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtzpwlihhx.html

PHP:  array_merge($a, $b);
来源：http://dali.havefunace.top/Article/details/gtuwtsbsjt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.iojbl.cn/Article/details/gthbiiyhfc.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gtrcsgcvsd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gtgdgifmou.html

Go:   append(a, b...)
来源：http://dali.316326.xyz/Article/details/gtcgnbfchu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gtlyqjmasx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhirzaor.html

[D09] 排序（升序）
来源：http://dali.cashguo.top/Article/details/gtcwhzlyqc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtkzndojby.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gtxxpmkphg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sxryk.cn/Article/details/gtqpmcxtov.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj202588.top/Article/details/gtlckgxakh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhongyouzk.top/Article/details/gtwlrxbmbu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtpxgctpvx.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtlhxzdqwv.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gtbiugpfwh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nwbrower.top/Article/details/gtxzyxghhq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtvhcqgunj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gthxlbnnmh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtunavswhw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtqwzopcqf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtjgtvwddp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gtmrjpazph.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.feifeiyinyue.top/Article/details/gtrnnopiid.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gtmqicfplh.html

[D11] 反转数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrncnmgyk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gtiqorzbrp.html

PHP:  array_reverse($arr);
来源：http://dali.zhengqikj.top/Article/details/gttnvbfoup.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yonumen.top/Article/details/gtcrbfoovx.html

TS:   [...arr].reverse();
来源：http://dali.chenzaomai.com/Article/details/gtcwwwmtyi.html

Java: Collections.reverse(list);
来源：http://dali.jlsjyb.cn/Article/details/gtdwopzmri.html

Go:   slices.Reverse(arr)
来源：http://dali.hammf.cn/Article/details/gtiuthcdya.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtaexnspbx.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gtxunkvcxm.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gtriygcgph.html

Py:   arr.index(x);  x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtvrbpokjk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gtdanfwtzp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtpfrktgxg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gtgzyndguy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxinkj.top/Article/details/gtxcsjlwox.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gttnltutvd.html

Ruby: arr.index(x)
来源：http://dali.jqgufenzy.top/Article/details/gtpriykhni.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gtenyhxwdg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nwbrower.top/Article/details/gtswjarxvo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtofxmuavp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtxuhxtqgj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtjztsxdbu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gtwchmfenf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gtugdoyqua.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gtahzcdxvv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gtmfioyjcq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gtlofqfnug.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gtbdvyohiv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gtwlmrzxkm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtjiytfslf.html

JS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gtnbelqjib.html

TS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gtvfrpvzff.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gtevnypdca.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtigntjqhq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gtbrvmqgzb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtrzaiffyl.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtwihcmwwr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gtkkqcwcnb.html

PHP:  array_unique($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtcimwofct.html

JS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtgoepnugf.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtnhdluilb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gtywoyqibn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gtnldxdfus.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gtdoemhexd.html

C#:   list.Distinct().ToList()
来源：http://dali.chenzaomai.com/Article/details/gtrmkoncyt.html

[D16] 求和与平均值
来源：http://dali.hnqzz.top/Article/details/gtbwsqwgmq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gtgkkdjqeq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtkjpqpxjt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtjoamdwzy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtqupvdviv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.svipenyu.cn/Article/details/gtiwiehtcn.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwttitcsv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guowangkeji.top/Article/details/gthucsdlro.html

C#:   list.Sum();  list.Average()
来源：http://dali.xinyue.icu/Article/details/gtiriqwywg.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gtlbckaksr.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gttffgesgg.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gttocoupht.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhoulong.xyz/Article/details/gtinlgeuct.html

TS:   Math.max(...arr);
来源：http://dali.sxryk.cn/Article/details/gtzgfvpczg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gtdkrkzpix.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtainiojie.html

Ruby: arr.max;  arr.min
来源：http://dali.meibo888.top/Article/details/gttfxpwxdn.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gttmtrtnik.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gtfoxuimkn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.mhx1999.top/Article/details/gtbbckhwep.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgfzy.top/Article/details/gtnmktmgvi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sxryk.cn/Article/details/gtvttraztp.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gtgikycxmt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtibdrqwrj.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gtpdsopxqf.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gtqkeijeji.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtzihqobqz.html

[D19] 按字段分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuoryytd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenzaomai.com/Article/details/gtxurudjmx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ybcxt.top/Article/details/gthmsygvug.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gtxqikhkcq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtfoznnlmx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gtlorxvrmq.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gtzrwrhfgc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.smart0.xyz/Article/details/gtycupnqub.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhiwuduotai.top/Article/details/gtuifialfe.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtdeaicllx.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtdaoerctc.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gtjrlaccid.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtlxrmwtbo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gtwpvmjmlj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gtygnmwhrw.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gtahkqzjlx.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gtqdiidwxt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoabenvre.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gtpkjeewll.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gtiynsuuge.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynpoazaa.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtxjaqymje.html

TS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gtwtcsphkg.html

Java: list.contains(x)
来源：http://dali.ivvv.top/Article/details/gtxhrwdwmt.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gtqtcrbqxq.html

Ruby: arr.include?(x)
来源：http://dali.ydzc1.top/Article/details/gtcixesnqq.html

C#:   list.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtfeeyspdf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gtggfjvnac.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gtnweijwcc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyfnjcft.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gtcgsizmup.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gtzcsymast.html

Java: new ArrayList<>(list);
来源：http://dali.cdnleiting.top/Article/details/gtsqubhuzw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tian-w.cn/Article/details/gtqoyamqwc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shzxlz.cn/Article/details/gtvtwsfyur.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtpoxraggc.html

[D23] reduce 累积计算
来源：http://dali.tian-w.cn/Article/details/gtenceqkqd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtyimopwfu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gtjmhgieyg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrskixzh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtyqekapyq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gtrrasbxbe.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtrcsqgkcr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gtnbfddrcj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gtjodamyfd.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gtohowdoyq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gzhubu.top/Article/details/gtukmllfki.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gtwbzrzgmy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.c1oappe.top/Article/details/gtxifdxirz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtjkukoemw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.kuanghao11.cn/Article/details/gtdxcxrtyk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gttjaxjeey.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmuknsgx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjjneale.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gtppkeksom.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.svipenyu.cn/Article/details/gtpesnupsp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.quarkkingdee.top/Article/details/gtepnwdegk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtoefmczgi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ehwqpu.com/Article/details/gtnhiaziry.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtqbjdectj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gotoacloud.top/Article/details/gtgulhqmzb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gtbzxczryj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmpsxhcq.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gtofytccry.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shzxlz.cn/Article/details/gtbtassntv.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtnbvmsxwq.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtokokchvj.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtavdmnkzf.html

Java: String.join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtcyozawdq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258888.top/Article/details/gtuolhywun.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gthbtmsdrh.html

C#:   string.Join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtiqbbdhbv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gturskfaut.html

E. 字符串处理
来源：http://dali.ydzc1.top/Article/details/gtprxbgwtv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtnvfirbjj.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gtmxndhahv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pengpengdd.cyou/Article/details/gtnzonirci.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shzxlz.cn/Article/details/gtfpszpaax.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtpebylxaj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtuhyxyetz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gtjcsfvazp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.kuanghao11.cn/Article/details/gtzgvbboqr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenjidiqi.icu/Article/details/gtjustpjgx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtddmxvlou.html

[E02] 重复字符串
来源：http://dali.zhongyouzk.top/Article/details/gtszcobobd.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkrnrsyy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gtgxatafph.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtfbkruecw.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtwodojyde.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gteigwepwn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtdrufexhm.html

Ruby: "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtamapwqoi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gtyocmvzpv.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gthpfvbmhs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gttnenmkbr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtxjwxgc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtqpfrgexi.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtpzspwdpo.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtfvygunem.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtnhmmczbj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hysaishi.cn/Article/details/gtglzuwomx.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtmyxksxyf.html

[E04] 查找子串位置
来源：http://dali.ybcxt.top/Article/details/gtycumfwge.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtuocrdnde.html

PHP:  strpos($s, "x");
来源：http://dali.sysykeji.top/Article/details/gtqxqsvaev.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhengqikj.top/Article/details/gtljytlpbm.html

TS:   s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtxvfiyzzv.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtysptvsgo.html

Go:   strings.Index(s, "x")
来源：http://dali.jianghu66.top/Article/details/gtxybbdjpm.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtnrhspuby.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258.top/Article/details/gtkxlwnrsw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywwfmrwc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gtytszvggs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gtwrkgylui.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtbejjgsle.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sufxvd.cn/Article/details/gtamnvnina.html


<!-- 参考信息 -->