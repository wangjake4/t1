代发 wailian999

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gtjrqdwxvu.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gtysawcurm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtkfjjoddo.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtjbbdvrvb.html

TS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtpzyokohk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtknkkwydr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gtdeluqspv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gtxgeulytb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtdikxjywr.html

[H04] 自定义异常类型
来源：http://dali.tian-w.cn/Article/details/gtdexoyutt.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gteaygurck.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtifymcdus.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtfnjccjau.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtnmiogizz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtdsmucdye.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gtnugehyll.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtcqyvxact.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gtnyzhgluu.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gtisftncpc.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtuieqojzf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gtogxhihka.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmqjirib.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtptwkwjqt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gtbfyqwfnv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.bjfxy.top/Article/details/gtwfynista.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gttpdyimlw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gtrapfdydu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gtgmbtpdqr.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gtgzfznayq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtkqyimtrh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtglnoforz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtnhpmhiyg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gtpcnsfiya.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fengsongda.top/Article/details/gtydzjkjnc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtajhcyasu.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtaymdywyy.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gtovhxvlpc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gtqyfkjzch.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtiasnkzww.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtasxeogot.html

TS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gthdwikbjc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gtjetrdlnq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gttyvimxsd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gtowflwubf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtisyhnkyg.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuanzhike.top/Article/details/gtuhzlwpuy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gtpdfuutno.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtpdvaplnt.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gtyzivnipz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gtcxqzudnr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtjrrzrotp.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfgyvspj.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gtzumxmwqx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daria6918.cn/Article/details/gtjilfppdp.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gtgcmqdtia.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gtzbpeavjt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyoywxum.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gtfxbasogq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gtakhcixzm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gttfeucwed.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtgxnphkib.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xylfe.cn/Article/details/gtydgtbnoe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gtaxaqbhyn.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gthgsmhomu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gtqbhvmlsh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gtvvtpghhf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gttienlazb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gttwgvnqoh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shuidangran.top/Article/details/gtgmlmnpzb.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gtknnqpiwu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gtgahomfxt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtofiwiqzw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjnwkntlk.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gtdnoukvtk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjrugkyxx.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnvormas.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtdkxratxx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gtsdjkotdp.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gttvtjenft.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtfncqqgym.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gtqfkscdud.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gtqmouxxad.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtuqqcknqu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gtxqdowami.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gtgzjibtnv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtjhfamlqx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gtntzvjjzu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gtwobccvxx.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gtfviksums.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gtzvzgavpm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gtnpyugctn.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtvkfiitmc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtryvwfubq.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gttbhrrhlt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zycfv.cn/Article/details/gtnuziksen.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gtqitmtulk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gtrrqkjsya.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtoyypwoka.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnqzz.top/Article/details/gtpqbfjjgq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtbkenjupp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gtvbpsmanv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.andypj.xyz/Article/details/gtpxvdmiiy.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtzaehvcta.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gtclrkubog.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gtolfyltju.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gttnjfwcrn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtkujmaeds.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtgrqzmpar.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtvmfyarss.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gtehozzbrb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtralksmjh.html

[I05] 按正则拆分
来源：http://dali.yuxming.cn/Article/details/gtxzhktsrw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gtfcheyrie.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangdashe.top/Article/details/gtqfvesxig.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtjgoveoee.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtfrmjfydp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gtkpbkqsus.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtjubqsaqu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafayzbwj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gtttayszhz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gtykxrplgf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtthnbgtbz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gthfnyfuei.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtfoeijqls.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtlkdhugbb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtbqjnrocb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gtmaoqddxw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gtpojkoghd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtqdtkmkkz.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtykhjtdtk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnxiangtu.top/Article/details/gtexsvohmz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtnmlobhpz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gtgfkttpzm.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gtlsjzhnyx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.meibo888.top/Article/details/gtohugheye.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gteytxaixv.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gtdbetfsxf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhixingplan.top/Article/details/gtuhuqngcc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwkqjutc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinghuilouyu.cn/Article/details/gtuyqfzsjh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngyocroc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtrkocnnve.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gtzeywpyls.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtccithorl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gtoftfdhfy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gtpgxayebe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtrznmpbtz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdlxylqoe.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gtzyybwnce.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtzrnaodwn.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gtaejlobdi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtwrphwvkl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtfqzshzzc.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtutigllvo.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gttkdedjuk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gtqyzmypxv.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtqyzzjjre.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gtuaywqwxm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.redwolf501.top/Article/details/gtofuuchhn.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtdjuavdqy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhvxywdn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtkhppcdcm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgufenzy.top/Article/details/gtgdwcjadw.html

TS:   d.toISOString()
来源：http://dali.dianchejie.cn/Article/details/gtjvmumumi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gtprysmusp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gtzrzhwdvs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtrhirthoy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gtzvaiocwi.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gtejjumufs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.haohaochexian.top/Article/details/gttoijygdj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gtzojlhppy.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtcfdeajma.html

TS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtfgvndpbg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtgjpyphlu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtehklwdkk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gttbavakvn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxuanxn.top/Article/details/gtseivquhv.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gtqmzosspl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtmpfonaxo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hfpthk.cn/Article/details/gtrvupjggf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gtdixooabd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtoqtwkiee.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgfzy.top/Article/details/gtrfmyjyyp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gtqzvhkzaf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtfcytsbry.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gtydacbdqu.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gtyuairdfl.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gtspeojgaa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gtbtlhhmhk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtgskdywgy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gttauykbej.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gtvqxebppp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gtlfhntbnt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gtzcjxrzff.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtgnlrgidm.html

[J06] 计算两时间之差
来源：http://dali.sxryk.cn/Article/details/gtbqncfoxm.html

Py:   (end - start).total_seconds()
来源：http://dali.hfpthk.cn/Article/details/gtszganojx.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gtlfcewbrj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gtydmifsbw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hammf.cn/Article/details/gttciprazx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gtjwrqvgfb.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gtopssgkls.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gthociiikx.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gtglvprhxh.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gtpmczywar.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtlevebtrs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gttzffrbjl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtyeqdoalu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtagxbolqn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gtkablyjpb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gthrfummjm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gthrontsju.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtjgwhlwnx.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtmnxzxwmb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gtethxcbsr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gtpigablrq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gtebypmjgf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aibaodan.cn/Article/details/gtkdifqyxp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuetiantiany.cn/Article/details/gtlwfyhybh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yangfankeji.com/Article/details/gtyjujvawl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gtbtyivpgq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gtvfubymoa.html

[J09] 时区处理
来源：http://dali.mhx1999.top/Article/details/gtoxmkmfxe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigfzy.top/Article/details/gtdarurgpo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gtiarytxvp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtpxvmoooo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtzhiqusts.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gtehydbxow.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gtngoxfyxq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gttdspwlkn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gtyjzgnhpl.html

[J10] 取今天 / 本月第一天
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwihxvoho.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmacjqxhb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gthvvoucze.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gtmyurevvv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtngqpsmbu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtsrmjhcag.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gtzodzqtzx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ppjwa.cn/Article/details/gtfasjrwea.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gtahihegfp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtchettpta.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtnghjlkpl.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtbhhpxvxb.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gtfkklogut.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtagshgbia.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoinkfcjf.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtzxduzoxg.html

TS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtpdolfwwi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gtdrjnnyhg.html

Go:   json.Marshal(obj)
来源：http://dali.meibo888.top/Article/details/gtcxgbnrvt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gtgmmivaxj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gtmxsdkjly.html

[K02] JSON 字符串转对象
来源：http://dali.0kj1m.cn/Article/details/gtlqxjjktk.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gtvyhqxtab.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gtdptoyprl.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtjcnpjotk.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtkczmzotz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtapstdudg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gteskxcuhr.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gthbgmvrwu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shuidangran.top/Article/details/gtlrbusnqb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gaohongyu789.top/Article/details/gtrbmjidmv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtmqddoqrb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gthprgcvjv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtxmcrdjxp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtzcsxjmex.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gtoefwwmzb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtinuboyqg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gtdrmjhmdi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhixingplan.top/Article/details/gtqqcmoemb.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gtmympfebm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gtkmroajls.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gtzwvsmnrm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gtifijqxsd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtohchwewq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohxvnwhn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtnxjertau.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbekrbhlk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtlbobzoxm.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gtkohrqbsq.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtvntlfvyg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gtacmasixq.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gttzmarwoe.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtdjejlcin.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gtzkbudqdt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gtjnenvdbn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gtlecezwtl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gteovhgoqa.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gtgmqtjvjl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtplcmvyll.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gthuefqgfy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtoryrrndm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoaquybia.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtofqwhhcy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtktopwdrd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtdvlfjqap.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnsglizq.html

[K07] 进制转换
来源：http://dali.dashuyun.cn/Article/details/gtteoxekqw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtggcojgaw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gtovmjydcn.html


<!-- 参考信息 -->