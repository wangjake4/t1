代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gt2alycgesa.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gt2fwmopuby.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gt2yyhvxono.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gt2vgdexfsx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zcxrgjzv.html

JS:   toString() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2fvwqymno.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2qfhubnwz.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2vrcahcnf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2ouirwskf.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2gopvgkot.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gt2yxtsjfet.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gt2girtlksy.html

Py:   isinstance(u, User)
来源：http://dali.mhx1999.top/Article/details/gt2vlwklsrg.html

PHP:  $u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2rnjfwynq.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2mgkocoaf.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2cnhwhysy.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2jilxxlhn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gt2kdudcezo.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gt2xnjqclfw.html

C#:   u is User
来源：http://dali.ybcxt.top/Article/details/gt2byoypktk.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2khsnfwzk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gt2nxuvyagl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gt2csjgaoee.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gt2jtqsraev.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gt2komomgub.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gt2idmzlnsi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gt2xsbizaqk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gt2mhswtani.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gt2mxopapwh.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2fmyowcez.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2gdqoqrvf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gt2cmueiwtg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpvnuidv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxziuibu.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gt2eezsjedz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gt2xbsvpnqq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gt2azwgmsfx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gt2pdfrsvsy.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gt2zcathfeq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gt2oosmxzgb.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrtjyfvp.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2lmecqzdi.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gt2pdmrmrsa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gt2izeqlvyf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gt2jmdevsyz.html

Ruby: obj.instance_variables
来源：http://dali.jinqigufen.top/Article/details/gt2oqcqmuvm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2pcmqdtsv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2kzwkeunr.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gt2gnzklkib.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2dqfbxzzb.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gt2zqwptwup.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gt2gxchencw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2olcvtksv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2nwmsgzzp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2qmgtqyir.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gt2kbxtvzbk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gt2jghsnazo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gt2nylwrpmw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gt2wewqazrz.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gt2jcdzzqud.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenzaomai.com/Article/details/gt2iuwzmtch.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2cvlqazbo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smifqojl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xspsqetm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2qgfpnwbf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hysaishi.cn/Article/details/gt2nyncroye.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2eltqhwne.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2nwedlnay.html

[H03] 主动抛出异常
来源：http://dali.aizwys.cn/Article/details/gt2kothgqtz.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gt2pngoyhwz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2iobrszym.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgghszku.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2jhlesdye.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2hrpryhoh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ehwqpu.com/Article/details/gt2pcktdjcq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gt2pqtowbsb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2necqoqwz.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2azzegusu.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngenkkuq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2nkiumllj.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gt2wxgftnse.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbfmnksw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2wsdmkvwt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwpvjkda.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivqpfoae.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gt2etuswffs.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gt2roonmgcw.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gt2tnugalxp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gt2kqthtzwu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gt2czmvsezu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2kuorffiv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sxryk.cn/Article/details/gt2qhjmzkap.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gt2mfyqkxgg.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gt2gpbrlxfo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gt2tdwdjksg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgjztjy.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gt2jzjuwxxk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gt2hxqtkmwx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2ugkawtbm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gt2dqcgkzsn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gt2auvflmkk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ugcgfbfa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gt2ezfqloys.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258.top/Article/details/gt2piykimgn.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcczycay.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ehwqpu.com/Article/details/gt2xlbkmoxa.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2zdufyvef.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2lmdqeogp.html

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmidrdhm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gt2ygslgdoo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gt2wmbqaacm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gt2rxnrenew.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2kdlcjcix.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gt2kkjqeagi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gt2eurkxpzz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.svipenyu.cn/Article/details/gt2zlbcmlcd.html

JS:   e.message;  e.stack
来源：http://dali.0kj1m.cn/Article/details/gt2cwzcueki.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.snrcjt.cn/Article/details/gt2llhmvfzg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gt2dtbkxfyw.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nsdshgfy.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gt2rhcususp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gt2xsnqfrbb.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gt2dudoqnnx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gt2mbbrommq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gt2pwjtohkt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gt2ytcrhoch.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cqqwz.cn/Article/details/gt2gtrtagmp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gt2jovmoloc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gt2lgcdiynr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.birdmap.top/Article/details/gt2sjwnemzu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gt2mqmpuwgu.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gt2zbgxgxih.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gt2ydyuhjrc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hujgvpmj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2moyyrvud.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjkbybso.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gt2aihkzaia.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gt2kpwcrtlq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gt2lisuxybb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2grrepvbh.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2zeqchndo.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2milfgixa.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2bchmznmo.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gt2jkwawihu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zaxgdnjy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2vtzzmxcm.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2wumugvcs.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2fpnhosna.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gt2hrkaamuh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gt2zzligyuf.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2qadnopkp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gt2vksvllhm.html

[I02] 提取所有匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2immkknqe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gt2qtficeco.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gt2gwfhawpv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxuymnlc.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gt2gkpvvawm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqxdppbw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2jffgnjrh.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2acnrhoqc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2nqetmobh.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gt2xuwztvox.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gt2khcvfhaa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gt2zydfejnu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gt2cuohujvs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2bjczokiv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2iaxsauqr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gt2aejoahfj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2cswbuxbk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhengqikj.top/Article/details/gt2wowxhglo.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gt2ltmikgjz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gt2nxiwwgvu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2cocknfet.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2wlgsxccn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gt2plpxlanh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2nauepkdz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gt2uwfokgys.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2cuikpmhj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gt2vmzagzdj.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gt2nltimymu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gt2kfyylbcu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2bnzylxhf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2vnoyehwj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2yhuicglx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2qcdmajpg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gt2snbyouyg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2tyyuifug.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ipeqlmfq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gt2cgxswcei.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbxfhahz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gt2przwiqqn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gt2ueheeftw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gt2ouvcrrmi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2vqfqqeei.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gt2pdnunrbf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gt2qdatdqpv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kckyitae.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gt2pyfmnzjt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gt2kwdtbbpa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2zvfsqwxq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gt2mbfpdbik.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gt2zfqrllua.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gt2ilnjsoll.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tian-w.cn/Article/details/gt2jefkmfbh.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gt2phrzqoyo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jlsjyb.cn/Article/details/gt2ktvaglzl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gt2hlbliqti.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gt2ostrnoha.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2lvcfbpdw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxijvlxo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2kuafurny.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gt2isdcdebs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gt2yssukerc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gt2rxhyxclf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2zzsmkigz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2itsltvad.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2zlorldul.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2kgpekufq.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gt2nyxhccyb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gt2uziydmqr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gt2btrgibhu.html

JS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gt2wrhmvhqq.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2qysiccdf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gt2phbcdoxs.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gt2pesyudol.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gt2qpfowmit.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gt2jgabtbyg.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gt2dnrokiqp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2irkbjyus.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gt2bfkvcvhd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gt2vecoghcu.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhmtkzhu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gt2bxsoacrq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gt2pouxofdr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gt2gplctbrc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gt2qssnhwyk.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gt2mrmghdbh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jlsjyb.cn/Article/details/gt2agdbyxal.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sufxvd.cn/Article/details/gt2lenbhjyv.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nggupvqz.html

TS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2csgvokyq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2tqokevep.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwukkbij.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hmeuswro.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gt2xqrhnekh.html

[J04] 时间戳与日期互转
来源：http://dali.kuanghao11.cn/Article/details/gt2inneqjhw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gt2mxxagicr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gt2eqtoccxm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2aafytjtm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhpawhvd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gt2unxfyrxt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2bzwijqzb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuanzx.com/Article/details/gt2jxafnzjz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gt2pqgjcpql.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gt2eqqavuru.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gt2vkzhzykg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gt2fgzvndpq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gt2yqxoiwle.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2efplgchy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xinyue.icu/Article/details/gt2dmnrxwwj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gt2ylmwkfwp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gt2nvbbbosh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gt2vafmxzdz.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gt2idnulqae.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gt2nfoglixb.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gt2apxhwzxc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gt2lewjejev.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gt2ywkhzfyw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gt2bwtcajjd.html

Go:   end.Sub(start).Hours()
来源：http://dali.ybcxt.top/Article/details/gt2igbozwmz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gt2hievbbhm.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gt2nojgwzti.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gt2uoinlbkr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2vgnfwhkq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gt2pwovplvd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gt2umryazmp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gt2mkoowulk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cucudq.cn/Article/details/gt2ojevaxjq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gt2gcroliqq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2zlfbzyhc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2draaohvw.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gt2wfqpduqd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gt2hknudwda.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tanke756.top/Article/details/gt2ohliycbd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gt2ksiopuyo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eifxujoe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gt2sthckwkn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gt2sbgtyffx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpdzrds.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gt2vublkzpy.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gt2kabjfpya.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gt2zfrtnffh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gt2fziwfwts.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gt2vdkgeeut.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gt2kqkflwem.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gt2shjyfyjx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gt2iwtqvsco.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gt2tbssskix.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gt2wuazxhli.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gt2ioqbatkd.html


<!-- 参考信息 -->