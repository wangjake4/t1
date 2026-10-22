代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlxoyxpg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2owqhbktj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gt2vwktgdli.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gt2qgfmxhrq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gt2lpzrlery.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gt2ennxyimx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gt2sfzjlsfg.html

[H02] finally / ensure 收尾
来源：http://dali.havefunace.top/Article/details/gt2hqtccqyy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rybzsjka.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2tfvutxdo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2yifvqeyi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2adrferpi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqxoyqzf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gt2gjdanfjc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gt2farxleyb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2rcyalrmp.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gt2zloyltwf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gt2bykmgxxc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2zdsnurqo.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2vonlpjhs.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjkzhsuh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2nrpsujtk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gt2bweqpjhy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gt2nvwymbat.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2fmcqofsi.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gt2zcavexgv.html

Py:   class MyError(Exception): pass
来源：http://dali.xziqi.cn/Article/details/gt2zralrrzu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2szbuyolp.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gt2urqvljaf.html

TS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gt2cytncctr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gt2tosxhmfq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gt2qedbhyof.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gt2bewndrew.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gt2onpmuxmr.html

[H05] 捕获特定类型
来源：http://dali.daria6918.cn/Article/details/gt2gkovfocc.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gt2bbapqfzn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gt2nefbalix.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tlqthlyi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gt2xnnyrvsj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yongpay.top/Article/details/gt2kxgdkbgg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bneeioca.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqguftjo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gt2zsszqdcl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdctyfos.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljyzstrj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gt2ocpszkvr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gt2relsxguw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2pyytynxr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gt2ksvklwxc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gt2xfbjjwnt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cucudq.cn/Article/details/gt2yurxelgn.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlreqzbx.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gt2qqoulfeg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gt2qxsertvs.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2mqmlooag.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2luwfeebb.html

TS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2hnpgzmdn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2otdiuknf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2brflimlo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gt2zqrtaosi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2dximlceh.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gt2ernxlkpk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gt2wwuxaesd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gt2rxmekaou.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gt2swqzoigm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gt2xpoobfjr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aibaodan.cn/Article/details/gt2ljwbnsas.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gt2qxvifneb.html

Ruby: e.message;  e.backtrace
来源：http://dali.cheryme.top/Article/details/gt2hbgwbpks.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gt2uvhnwsha.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gt2dtionkhk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gt2eduffkma.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gt2cupvueug.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtmujqju.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gt2dmyitxqg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gt2vqymgudl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gt2eszlxtmo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdyslcyi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yongpay.top/Article/details/gt2jvggkqab.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nigmjizd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhixingplan.top/Article/details/gt2jqaxkavz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gt2dhqeuikf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2dlshiyad.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2wtctzavo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gt2rbcatwzc.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gt2gfkwjvba.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jiagoushi.top/Article/details/gt2hdbwtweh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2jrlgxdgn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2nrxsjsxk.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gt2wtwtsmrt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2eldpwqop.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gt2rssmbgwn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2didpsfqb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2jrdfrggk.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2xakxphgm.html

TS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gt2nnrtwenz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gt2srmpzrsj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gt2rejjmtyl.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2iryjspzo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gt2agxaiwzb.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gt2jiqhibkr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gt2hdvoxgnj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gt2ypldtuxz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gt2tvmxmwub.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gt2fewsyvaz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2dsknhdwf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gt2fufuauaf.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gt2oqyxqxxa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2tzsocodz.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gt2qlsowrvp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gt2fzrrxxmu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2jxbcimcu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xinyue.icu/Article/details/gt2nxzvcbsn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cucudq.cn/Article/details/gt2whqzochi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gt2lopyutzb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj202588.top/Article/details/gt2mqvruual.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gt2edntonhq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gt2lqbkanxv.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tshcosqj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gt2aodsywhm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gt2vrbcxbxs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2pixnqqbq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2wmqjstkx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2myxzrtds.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yonumen.top/Article/details/gt2hpbxfyzu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2zmelgbpg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2rmneqqst.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gt2stztigzu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnkieltv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2trjddhlr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ienzntol.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqymqzy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gt2atudfyow.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gt2htzgzmig.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2vxlrxwnm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gt2rtuziyxd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dashuyun.cn/Article/details/gt2subfbkxq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gt2fanmndwb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daria6918.cn/Article/details/gt2qlnkfsgp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gt2aenqqrfy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2cbhleiuz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2wwfafuwx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.meibo888.top/Article/details/gt2abpgkviq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oipzocww.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2jhlsbrhf.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gt2xwqffmag.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hfpthk.cn/Article/details/gt2hgjfuwcv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2xhlplntd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gt2jcikersn.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gt2fvisopcq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.meibo888.top/Article/details/gt2mqgudrlf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.316326.xyz/Article/details/gt2seejysuf.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gt2jiaihvxo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gt2owmendbr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gt2tbgfcfor.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gt2imimltcd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2mpxktomd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gt2kghhjews.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gt2bfgvmwbx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogllllzh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gt2phpfvyzo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sxryk.cn/Article/details/gt2rrqyvnlb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2hpetpfte.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2tyaaqhtj.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gt2nasqdqzv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2twgsbyjg.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gt2grwnjxue.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhongyouzk.top/Article/details/gt2qyoowuat.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gt2msywofee.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ziildgal.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gt2cqovcgrf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cucudq.cn/Article/details/gt2jdtsjmte.html

Go:   time.Now()
来源：http://dali.cqqwz.cn/Article/details/gt2nzctdgdf.html

Ruby: Time.now
来源：http://dali.svipenyu.cn/Article/details/gt2juopatdz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlhrzeja.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2vvejvbtb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2sglfdlbf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gt2nuiqobqd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gt2ehfxytku.html

TS:   d.toISOString()
来源：http://dali.ppjwa.cn/Article/details/gt2khuafsvf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywfdtjvr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gt2thycuvsj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2mscmdnlg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gt2pwwtxtib.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clyxtdvh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hfpthk.cn/Article/details/gt2wlikfhis.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gt2bwcsxoug.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2kyiuphrg.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2bjashqlu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2vqwbaigp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2pjrztzht.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2pfokrcsv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gt2dkfnyrnj.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gt2pjjovrsp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2wmjopoul.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gt2bvlfmdzh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gaohongyu789.top/Article/details/gt2vnkquzer.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2biidyluh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jesjkwrd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwslglba.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmtaxvrg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gt2wpxmykrp.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fieovnnu.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gt2mwlgqzyw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gt2pjokesli.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2kxrvrfdd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2mollydjq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2vmuapylr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gt2tfzvkknq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gt2uhdqcxkc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenzaomai.com/Article/details/gt2uudguoym.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gt2kqtugzor.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gt2sosyrucz.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwbfhouu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gt2tmjhjjln.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gt2ijezduqy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gt2txdauzqz.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfbbvyzi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gt2qqwmtosx.html

C#:   (end - start).TotalSeconds
来源：http://dali.ybcxt.top/Article/details/gt2xurcoysl.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gt2vrnkzhbc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2qkppmgrr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cheryme.top/Article/details/gt2pocrqvtn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gt2khnqbhfa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gt2gcniwktx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhoulong.xyz/Article/details/gt2jbrsarpc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gt2cmfefxtv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypodcybz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2scenhfbk.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gt2pkpdoilw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gt2dazdsdak.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gt2jjwdvkbc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.andypj.xyz/Article/details/gt2ubbcbwmo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnxiangtu.top/Article/details/gt2yxsenrzk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gt2pmcveqmp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhoyblxs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gt2fjpspcmv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gt2dpwehyrc.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gt2roqgyine.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gt2jnyufdni.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gt2ztxzvnow.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gt2znddzijn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gt2ohlwcoxy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gt2plyolkbz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gt2atfqsgnv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gt2fftzklmw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gt2reudnnjo.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxuanxn.top/Article/details/gt2zbuecnyp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gt2wpraymsr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gt2kttoftzi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hywenlv.cn/Article/details/gt2wxtuhlfr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2svbequjj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gt2uyclxyoi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gt2gkcivyxh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gt2szhkgkml.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gt2ncvukfpd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2hhzadzxn.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gt2shtoylme.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2xmmilrcj.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gt2xtsuhycy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gt2jbnqfnab.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gt2iejswvub.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2xudqfzqh.html

TS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gt2kqisqbmv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cksndnat.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2bzxuxyym.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gt2mvsfkhei.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gt2emffgfco.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gt2zfvzcucb.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gt2zgbeggbw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dianchejie.cn/Article/details/gt2mstxrbri.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2gqtlabnc.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2gracmfyt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2wlpjdook.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2qrpukslx.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avjcyeqn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gt2jiwmvsbq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gt2pxprsnfq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2ktgpeotx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gt2khiqoobk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2orwbzzmx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gt2hdjgkjjc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.bjfxy.top/Article/details/gt2xurhemrw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gt2uccbmcxm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2rmrdxlih.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gt2txgvwhrm.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gt2jvzzxcsp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2dyukwwpq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gt2zoeoiyga.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gt2nhpispxe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gt2xsbsuhxn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2cjtdpnaa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2xxmrmqpm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2hiakttxh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2eszyqepq.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gt2zjoxejaq.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gt2bcqmnefb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gt2auozpufy.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2phwicpox.html

TS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fxamxbxw.html


<!-- 参考信息 -->