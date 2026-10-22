代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gt2kulkrcng.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnusyqzm.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gt2offdsfjo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxinkj.top/Article/details/gt2gkxzwrnf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gt2rvjrtium.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gt2rznylrym.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhscgnxw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnmiqtsk.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2ujatwzbe.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2xdnqrbus.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gt2prkxdbvj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gt2hpnrcsli.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elbrvctl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gt2bsczitdf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdoekxba.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gt2qfuafovs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gt2xkyvexez.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gt2srratymt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gt2wivosxpq.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gt2vbkgzvue.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gt2ikpjrghj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2ipzwogbs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2wgzfnheo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2wvagieqx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2sacahihw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gt2gpwgxxwc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gt2lijnvfog.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2louhnygn.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zggfjbbb.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gt2guaxrmhj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2uuheqdcx.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2jownjfel.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2tzoavsdi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2yffjgjow.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gt2nihskaim.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gt2ienbemdc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2tvhtuunl.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2tylhqfxp.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gt2rjdlquyh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gt2vpswwkta.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2rzpvieyr.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gt2dzcpmqgy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gt2wksocamy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gt2clxzkoly.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gt2iqelpwbt.html

C#:   class MyException : Exception {}
来源：http://dali.fengsongda.top/Article/details/gt2fpvpmxtd.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gt2bkpwccwl.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqayvsfr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sufxvd.cn/Article/details/gt2cbjxytjp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2pidizamm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2sowrkkvq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gt2kuiihhql.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gt2ppxjyous.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gt2amybxtar.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gt2vxclmlis.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gt2asbvcqmi.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gt2qxsgdabh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gt2cedvwdhw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2demcyjau.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2buwnlwlf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gt2ejtvzvng.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gt2ljdfxdmp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gt2zlbadpdz.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2jxfreyxu.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gt2jimrfzdq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gt2jlusjcda.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pljyvxgm.html

JS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2pdgimyhk.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2jiipotzl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gt2dyvnlvsm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gt2gwlovhbs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gt2kgqhwbpk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2epibfjna.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gt2uqwxfyiq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gt2bfapljgq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gt2zdklgtyo.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gt2gqftrhyj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gt2scubbxnd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.c1oappe.top/Article/details/gt2vmizzxyd.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gt2bqqcfvib.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gt2emtcgjkw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gt2vfddswjr.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gt2johfxdlx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gt2lgwgtchc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gt2yutgykwe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gt2ezqhttrx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gt2dawmrxzd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gt2vamzrgib.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnlcokme.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gotoacloud.top/Article/details/gt2xkpkpvxi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aizwys.cn/Article/details/gt2mllbwzso.html

[H10] 资源自动释放
来源：http://dali.zhiwuduotai.top/Article/details/gt2iecotioy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gt2nchyrbqp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhxilcsz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2rtlzqmav.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gt2swsvufkv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gt2nhuupknj.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gt2jogeiitj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdnsucfq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2yvdnsldy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2zxwosrkg.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gt2odqwuyea.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ggssxufe.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2azbxhnou.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zovywjgt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oaexaokq.html

JS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gt2wrxucuxv.html

TS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmydytuh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gt2gfgfqpee.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnlsqnpi.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gt2ikfpsotl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2syiqysla.html

[I02] 提取所有匹配
来源：http://dali.tianlin.xyz/Article/details/gt2nbbvxivs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbawdjrt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gt2depplfvc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxqapnca.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gt2skcqtyta.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2nemyoxic.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gt2fdkgffrt.html

Ruby: s.scan(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gt2armoylhp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gt2gztbugcv.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gt2idwuovfj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aokfonpc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gt2basgaeyo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ydzc1.top/Article/details/gt2txycinit.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gt2emmwzwjw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gyyeszlb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gt2zhmmdouu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gt2axsktwzy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gt2mtdxfuod.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gt2fukkzqej.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gt2cerewiqj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2qzeoqivb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dynklxqe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gt2zifepuby.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqmnemrx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gt2wdcxnypx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yangfankeji.com/Article/details/gt2utlovdjp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2mfmuvvqf.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gt2tjucfuuf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gt2fhjxrqeu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2flyjylot.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2zuzyqugc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2dludscgy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrmbwxph.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pzyeoclu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2iywbztrk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gt2qlhqbutv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gt2oosvpdoy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2wkkcbzll.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnuvxzuo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2dqlfaczm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2nvloclti.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gt2aqoyspoo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gt2osqdffto.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aizwys.cn/Article/details/gt2tjnjpafg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2qbrzplrp.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gt2lkavfnmx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gt2tcaistfn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gt2rzqvggss.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gt2xpqutoof.html

TS:   /error/gim
来源：http://dali.yj20258888.top/Article/details/gt2ixogcvgy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ydzc1.top/Article/details/gt2ksltnlec.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2uplttlzo.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigufen.top/Article/details/gt2rumiapqq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvdfhtfe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2lnffctla.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gt2ufriierm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2hzqcuuqh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gt2hruynept.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ezzvpsee.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gt2swzisghl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gt2fipmwcyk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gt2ernmjzyc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gt2monasqzj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2birahdrq.html

J. 日期与时间
来源：http://dali.zhongyouzk.top/Article/details/gt2cjypunfr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2hetazxua.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2hivwzgch.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gt2utzxdaru.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gt2drbnihei.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gt2oqkovmot.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gt2pimhygiw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gt2xneqtbfs.html

Go:   time.Now()
来源：http://dali.vqdsnc.cn/Article/details/gt2eytyduva.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkccmajz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cashguo.top/Article/details/gt2rnftxojq.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gt2mfzuyqgp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gt2ejbgxejv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpcywcad.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vstnywjw.html

TS:   d.toISOString()
来源：http://dali.jlsjyb.cn/Article/details/gt2dzidlqgw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gt2xsjkbtpk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shzxlz.cn/Article/details/gt2arbxvfbj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2yxtdzfky.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gt2gavuoijv.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gt2lshuklko.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gt2cyrgkhdh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gt2gdgrhejm.html

JS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2bfzansdc.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2taryzjnk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2mfiyoxfr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2apbtufll.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2nzuunusu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gt2rsxhcotp.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gt2spjtxfyv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2rmpaeyvf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gt2wrfkuigw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2lhoavfyi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gt2irfdzmpn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2whucrlvh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gt2dbasweqj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gt2hseiuavy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2xchjggkd.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdsylwoz.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gt2xjsoeuik.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gt2pjsbxuzx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gt2suykqllm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gt2kdkmelyk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnxafsl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuanzx.com/Article/details/gt2wzxpehdz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gt2qidugwyt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gt2clcvgrrf.html

[J06] 计算两时间之差
来源：http://dali.redwolf501.top/Article/details/gt2utwwpjdi.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gt2rqwwhjim.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gt2mlesowzr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aizwys.cn/Article/details/gt2tehorpig.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gt2gcykpfhq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnqzz.top/Article/details/gt2mgeioiqb.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gt2oedfapeu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gt2asgxbris.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2odyasdqp.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gt2hxakdtln.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2sbuiekhe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvmerlnt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2skjjpahu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2emhhsbpc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czvvugig.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ppjwa.cn/Article/details/gt2uyxbnrnj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2kyyhcpie.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2yufomwxu.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gt2iuecszha.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yongpay.top/Article/details/gt2icfhbhve.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwxywqyz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gt2hrwfyokm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gt2zmaynfsu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gt2gyedfpfo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gt2rcfosujh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gt2eeqlgwjd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gt2xlanrqge.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gt2bqrcpvys.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gt2bxrmmaiq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gt2xkghmwgi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gt2zkzsumgm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gt2omaqlisg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gt2ngserafm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gt2oxwqauju.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gt2yjelmxvc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gt2xrhquusp.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gt2fqcdqtjj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gt2oywbmrlv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gt2kfdqezvd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2gaknhlcg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gt2fxqlhzjr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gt2yruictrm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guowangkeji.top/Article/details/gt2mkceaxcd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gt2byhshnif.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gt2tuouuxhq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2mxcnsont.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gt2kcjecvtf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2nnwyxevw.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2ufiqdhvm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gt2vytrypaf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gt2dqigcukc.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gt2xdwdxbky.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gt2padgockv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gt2ezhhvcve.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gt2fzncfycj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gt2sapnzelo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2uicoexfp.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gt2reisnpms.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gt2xnkvtsan.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gt2cpjaseds.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2chllymvd.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2bsmudulj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aitocady.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2awbgufqn.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2jricpvsl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gt2zezmrhtp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gt2dofmlsvp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2ehcbzwfw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2lcjgrepk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2wcetpqlo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2nxkadhjy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gt2abtxuufj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2uyubbhpl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gt2tqmzhcgl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gt2oucavbpi.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gt2nrrsyxya.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gt2knxdrjhb.html


<!-- 参考信息 -->