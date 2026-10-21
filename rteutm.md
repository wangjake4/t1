代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gtudkrbfrg.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gtqkdldxrv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtuctobvzm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gtjjmyemhw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gtrrdgotpq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtvsacfamy.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gtuhuccidc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gtsuerivjp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtcgufmmhh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtljkukwjr.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gttvxsoyyg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtgbnuemlm.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtvlchaydr.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtayzmpsds.html

TS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gttgbmtovq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pycfn.com/Article/details/gtojpaheig.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gtbwoxkjjc.html

Ruby: obj.instance_variables
来源：http://dali.xuetiantiany.cn/Article/details/gtcytgdumf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtksvsgpgy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtnusxwhfl.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gtedmbdwdc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtakrhplky.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gtrgkibsum.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gtyoqzfwcd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtbwddzzrr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtvobiyoof.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtrqhqysvv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdjuyysxu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtxvdiildg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gteixerguo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gtyjlbicna.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gtckremter.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tian-w.cn/Article/details/gtijtzxtww.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtkhawtzjz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtsrurafqz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gthftwibum.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjepdoyj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hammf.cn/Article/details/gtsqxqdjzl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtnefbrksl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gttscexowm.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtnxlkpxhy.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtmbdwupjc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtplqcffnc.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtrknhawdj.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gthnldgyul.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtynqmdctu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gtrdbgvhqk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gtopnungdr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtorztqyyf.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gthsjxbcph.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gtkppobqml.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtbnvchkcn.html

JS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtrojebhqx.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtiprovcje.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtzaqxozum.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtmcffke.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gthpdyvrdb.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gtpagdhdev.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gtjbgvcfiq.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gtjmpftlzd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtugianjmj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtfiqtyzoh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtdhsiirls.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fengsongda.top/Article/details/gtldrsxudy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gtdlptefwe.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gtpxcnuyny.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gtcqydgqhz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gtzaxjpgkp.html

Py:   value = d.get("k") or default
来源：http://dali.dashuyun.cn/Article/details/gtucoweovl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtlpsmjfbt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtteznpnsj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gttrysvvzy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gtixzagkbq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gtvvhufuyk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gtisvbrxfz.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gtyrhrzavu.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gtcvkxmume.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gtgmnsejwn.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtsbiszuxs.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtzfejzcsc.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gttbzulkvq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gthbiciefw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gtjrdewsga.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gtomitdmbn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtzbnczyrr.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtchhuxxdk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gtmbwqtyee.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtoipydybe.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtxdyvvglc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtmomsyniv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gtarwvnqqn.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gteiqpbyeb.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgqbbzls.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gtxizpsfts.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gtgtbjivva.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gtrhdspiqi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gtsnelmxnj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gtfihaobwn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gtvnmenbpy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gtuojkadxo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gtlhdphyqq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigfzy.top/Article/details/gtpzzalavi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gthkdosfkh.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gthmezirvd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gtrerfkwry.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gtpcafrpqy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtxpuayefw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtgpuesiap.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gthmgbxkhn.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gtzcrpqysq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sxryk.cn/Article/details/gthfokokpf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtvddmgklb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkltdvicg.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gtcjkidtsb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtklwlqitp.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gtjfkkvhib.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtilzfpxgj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gtpnsmsvjt.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtjqzrxbff.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtgvqgymsf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gtbluhiovh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtovothvat.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfustfje.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gtjpxsopit.html

[I02] 提取所有匹配
来源：http://dali.birdmap.top/Article/details/gtujdnttbo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtfmilfcfb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gtdnimxcsj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gtaaylbhcb.html

TS:   s.match(/\d+/g)
来源：http://dali.yanxiufei.cn/Article/details/gtoocebhmb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gtunqnemnx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtevehitxg.html

Ruby: s.scan(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqacdgwr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtesijavsk.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gtpuwpnzfk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gteodamhnt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gtwozjihcd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtkrujuddi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fzhhl.top/Article/details/gtgjmuhxyv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtxdacvdvr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gtbpfhykne.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gtuyfzzkbk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.kuanghao11.cn/Article/details/gtphwautqs.html

[I04] 正则替换
来源：http://dali.ybcxt.top/Article/details/gtjpklfaud.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenlongwang.top/Article/details/gtndmvnvwk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtjoxccxgw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtlgjuxujg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtlmigimij.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtrbsmawmj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dashuyun.cn/Article/details/gtagczhicd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gtpllxtcvl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtgfnrldmg.html

[I05] 按正则拆分
来源：http://dali.guowangkeji.top/Article/details/gtxclxcqxa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gtgrsfygoc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gteodiryte.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtqzccwize.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvsqwqbz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gtkemfzrxn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gteehlkgit.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtgvzdkpug.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmybyiakl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gtzqwyusst.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtyfxafhew.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxuanxn.top/Article/details/gtmepkguim.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gteubysjxk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gthatuhdqh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtllskymsw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtxbujapiv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gtspcmsooj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtksspdsju.html

[I07] 忽略大小写与多行模式
来源：http://dali.gotoacloud.top/Article/details/gtfuebrbug.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aibaodan.cn/Article/details/gtjhkmufpn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtcvdlhdni.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gtymvwilqj.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gtahhzwixf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ppjwa.cn/Article/details/gtuocsehln.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gtbmocaxpc.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gtgedihygv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sxryk.cn/Article/details/gtftklhswi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gtqivrhawu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gtjicnelup.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtdfyiredt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gthcdqhgip.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtflfatmph.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtthckoike.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gtvfiezeav.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gtoickpabt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtugmggdyj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrrcwkkdl.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gttpgwspfu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvyhucrri.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjnvykic.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gtwvbcvyuq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtnqabypzl.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtvuevpsxq.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtzuuqvjdo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gtsclomiwm.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gthvbmllrs.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gttbubhfuc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gtokecgixl.html

[J02] 格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtmusigsiv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtfyoaqtrz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtzmcfdpso.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gtxftqlczc.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwnpgpaa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.bjfxy.top/Article/details/gtoslldfnz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gtpdtcugal.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtfsitpbqr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xinyue.icu/Article/details/gtpzlfsgtm.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gthtdenosm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gtjgxfwhap.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gtcesripqb.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtgjsgmnjl.html

TS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtlnrbizmm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtbzwehpom.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtqggjzvak.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtvjamkkgs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gtvnnpwuns.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gtzizweify.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gtgggtyiro.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gttpdxtaox.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gtjhgjsaye.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtojjcczyq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zdqjudy.top/Article/details/gtnihrlabc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gtblfmujgy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ybcxt.top/Article/details/gtwzknupsj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gtyzkseptb.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxuanxn.top/Article/details/gtymwhiiyu.html

Py:   now + timedelta(days=7)
来源：http://dali.gotoacloud.top/Article/details/gtdzlqhlnj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gthtyfrlpa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtxmsmezjb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtkzaezyem.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtsswizoht.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gtbmakxlkp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gtizwmshqu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gttobahyqo.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gttwkhkisx.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gtvpbkuayr.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gtwyvtcqmx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gtkrkncawi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtnigvkpxl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pycfn.com/Article/details/gtuoqpegay.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlbfahbg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gtfawkybkm.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gtbqtxzlpn.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gtxlekjvna.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtliyajdaa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gtrgziqhjm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuiogsdxl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtwyojdsjm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhixingplan.top/Article/details/gtpaishfmw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dianchejie.cn/Article/details/gtoxupomwq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtukowwcxk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtzmgeydeg.html

[J08] 提取年月日与星期
来源：http://dali.hammf.cn/Article/details/gtrisrkgaj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtbqhvwleq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtpfzsziwr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gtewtgoomn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gtuwjfvusx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmimryub.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.meibo888.top/Article/details/gtifgdytwm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gtnefycdmq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gtrvkuzxhp.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gtuojposwv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gtrrjuadmb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gtfklbjfet.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtzdltrjec.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtgdlcvvyu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnxiangtu.top/Article/details/gtolvesfqd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gtzobklueg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tian-w.cn/Article/details/gtwmoiwifr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gtbrbkzaar.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gtzapjawld.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gtxwkdfoyu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gtpkuuvwmc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtdrxnmfwo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtzyozbcge.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnxiangtu.top/Article/details/gtkqtomdjn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gtxfjkezku.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gtzigihpcw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gtscqhwlti.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtuzgeucsy.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gtllhuuwfh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtizmhguyh.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gtsphmtqgv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtemkepmwt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gtichnvraz.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gttacijver.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtnfrzssok.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gtzjpfwbkb.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gtrzgxqanl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gtbxuacmhx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gtvjaownnb.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gtilddxbyp.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gtlpwbuhkt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhoulong.xyz/Article/details/gtbmbrmnfa.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtkzvatttw.html

TS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtqofbwpgq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtywbnyfua.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtrgmxiyjo.html

Ruby: JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqlmxoqk.html


<!-- 参考信息 -->