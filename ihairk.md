代发 wailian999

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtkpfsgubo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.mhx1999.top/Article/details/gtatmjtude.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gtjbfwcacm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gtrtndgkla.html

[Q78] 当前时间
来源：http://dali.guowangkeji.top/Article/details/gtbwallqih.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cucudq.cn/Article/details/gtlrqrxhxv.html

[Q79] 字符串拼接
来源：http://dali.yongpay.top/Article/details/gtmudxdwwi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gtwoquzhhw.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangtech.top/Article/details/gtkelowjvh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtfjjiscbj.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gterlxtahm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtvnaqgzjn.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gtkfytsywp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtptrszsip.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtubeionkv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtvkxiqtfv.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gtpakymitu.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtvyhkmxmp.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gtnhmyklzy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gtmduxxmai.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gtuuxvlhcv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sysykeji.top/Article/details/gtjloluolm.html

[Q87] JSON 字段做条件
来源：http://dali.cqqwz.cn/Article/details/gtugogyopv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gtgngfdvya.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gtxiokwkuz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gtukwdwvqx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gtirwjdxhu.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gtaisfiiuy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xziqi.cn/Article/details/gtvkowuwpw.html

[Q90] 生成序号列
来源：http://dali.daria6918.cn/Article/details/gtkejmemby.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtheqvcwis.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtyvrnxdeb.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gtfipaezyv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtckhwegco.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gtbkjhfzae.html

#!/usr/bin/env bash
来源：http://dali.jiagoushi.top/Article/details/gtwheceajn.html

set -euo pipefail
来源：http://dali.chenjidiqi.icu/Article/details/gtjaepokci.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gteublxaqk.html

name="Tom"; echo "$name"
来源：http://dali.cdnleiting.top/Article/details/gtfcoksoor.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gtltgyttab.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gtjvfsmlrj.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gtdgaqjvmb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shuidangran.top/Article/details/gtgwuzroki.html

[R05] 参数默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgjhlqow.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtlhoiitxk.html

[R06] 判断命令是否存在
来源：http://dali.sufxvd.cn/Article/details/gtsbhmgkqm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gtyreiwyzj.html

[R07] if 判断文件
来源：http://dali.snrcjt.cn/Article/details/gtmejkzrqb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gtfluailxz.html

[R08] 数值比较
来源：http://dali.jqgufenzy.top/Article/details/gtorseugtq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.andypj.xyz/Article/details/gtftlsccrs.html

[R09] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtkpqtakuq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gtvcbwekbk.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtjhypbjqs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gtwaaawwen.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gtstnxbuae.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gtbhtspido.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtfespukxw.html

stop)  echo "停止" ;;
来源：http://dali.gzhubu.top/Article/details/gtcwsgnmex.html

*)     echo "未知命令" ;;
来源：http://dali.xinyue.icu/Article/details/gtdsguzlsl.html

esac
来源：http://dali.chenzaomai.com/Article/details/gthugrrksj.html

[R12] for 遍历文件
来源：http://dali.tianlin.xyz/Article/details/gtjdupxbpd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gtioktvucq.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtclxiqilo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtflkimlms.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcessopaj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gtpxtiewpv.html

[R15] while 逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtkbsaybfr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtqiuspbij.html

[R16] until 等待条件
来源：http://dali.yangfankeji.com/Article/details/gtcbvcgboo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtnmsijkff.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gtpxcxyjbu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sxryk.cn/Article/details/gtoqczyxuq.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gtjxtkcxbj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtnjixxnfc.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtclklguki.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gtlaumwrof.html

[R20] 关联数组（字典）
来源：http://dali.guannengcc.top/Article/details/gtnktzkynn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.c1oappe.top/Article/details/gtjvskhgob.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gtjxhthcxp.html

echo "${#s}"
来源：http://dali.shuidangran.top/Article/details/gtqfkdlkzc.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtviksmjcf.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gtmlplfhxl.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtsjyzxail.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gtsbwoxrkp.html

[R24] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gthaleskyp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gtiggqjyvi.html

[R25] 去后缀 / 去前缀
来源：http://dali.sxryk.cn/Article/details/gtwmtcwnao.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fzhhl.top/Article/details/gtdtdyoqai.html

[R26] 命令替换
来源：http://dali.snrcjt.cn/Article/details/gtshxteqbr.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gtiswciyfp.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gteqqdtoaj.html

echo $((1 + 2 * 3))
来源：http://dali.dianchejie.cn/Article/details/gtzfggjxfc.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gtgkoxjujs.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gtyribcicc.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtqtnpvveu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhengqikj.top/Article/details/gtzsxiqlyf.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gtpezlpgdu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gtaildljaj.html

[R31] 局部变量
来源：http://dali.gzhubu.top/Article/details/gtcsgxcrac.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gtkldttxyt.html

[R32] 参数个数校验
来源：http://dali.yanxiufei.cn/Article/details/gtndsjyahs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtqduzsdhn.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gtvgcyenbc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gtomqbpran.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gtxnzagnrc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtnlbdsngh.html

[R35] 后台执行并等待
来源：http://dali.chenlongwang.top/Article/details/gtuvnknjxm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gtwrjdwleq.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gtmtnxedrb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gtpdhylgyu.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gthpepkljb.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gtjhqalzdj.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gtobhlrbvs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangshuangyany.cn/Article/details/gtthkoeliq.html

[R39] 重定向标准输出与错误
来源：http://dali.zdqjudy.top/Article/details/gtjexlzkof.html

cmd > out.log 2>&1
来源：http://dali.meibo888.top/Article/details/gthrcqcsgi.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gtubgofscs.html

echo "log" >> out.log
来源：http://dali.cucudq.cn/Article/details/gtxpwskyyi.html

[R41] 丢弃输出
来源：http://dali.nwbrower.top/Article/details/gtuakdgcsm.html

cmd >/dev/null 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhjbzirz.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gtirevizjy.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtpzumrees.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gtbtemptrv.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gtnjylknqp.html

[R44] 按修改时间查找
来源：http://dali.tanke756.top/Article/details/gtjezclpvt.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuikzzii.html

[R45] 批量删除
来源：http://dali.shzxlz.cn/Article/details/gtowxblkfb.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gtpplidtkk.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gtqejyaswl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gtduywzrlr.html

[R47] sed 单行替换
来源：http://dali.gaohongyu789.top/Article/details/gtjvsefsgv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtimpnjwex.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtrflhjtkg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtxetitifw.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gtowperylz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hysaishi.cn/Article/details/gtbalszfrv.html

[R50] awk 求和
来源：http://dali.zycfv.cn/Article/details/gtaedctxtc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtnuursnif.html

[R51] 排序去重取前几
来源：http://dali.jinqigfzy.top/Article/details/gtuqoxzqaj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tianlin.xyz/Article/details/gtysljfjyz.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gtaufwrpoy.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gtcmbylqgm.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gttdutztwl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gtslrasmiy.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gtbzcsqqfa.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtwhibnfri.html

[R55] 压缩与解压
来源：http://dali.daria6918.cn/Article/details/gtiryklulo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.svipenyu.cn/Article/details/gtzyqjrllk.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gtvdxoeayl.html

scp file user@host:/path/
来源：http://dali.sufxvd.cn/Article/details/gtpzjkmnsw.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gtlcqmmopc.html

ssh user@host 'uptime'
来源：http://dali.ivvv.top/Article/details/gtmpyntbxq.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gtfdnkaukk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gtklsdfbjt.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtndjhhubl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gtcurjfifl.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtolmwjevv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gtsmzpzhvf.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gtpetlcsym.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gttsnyueis.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gtiygcysji.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gthadkesdm.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gtolcddxew.html

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gtcnwybyev.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaiupxrqq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gteasnwwkt.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gtztfscpju.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daxiang520.top/Article/details/gtmufxbcsj.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gtujhitiss.html

crontab -e;  crontab -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfqkqbky.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gtnzxfqons.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gtdjkipiju.html

[R68] 计算文件校验值
来源：http://dali.bjfxy.top/Article/details/gtkoilolsn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gtrfdlislu.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gtrywdkkix.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gtpmlcygmz.html

[R70] 时间戳与互转
来源：http://dali.wangshuangyany.cn/Article/details/gthwbtjiab.html

date +%s;  date -d @1700000000
来源：http://dali.tanke756.top/Article/details/gttqgfgzsp.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtbwoipfxu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtryjvypqa.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gtnumvamlc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtgmicpkfq.html

[R73] 分割大日志
来源：http://dali.yj20258888.top/Article/details/gtusihasuz.html

split -l 1000 big.log part_
来源：http://dali.dashuyun.cn/Article/details/gteahjjjwz.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gtfwljqaus.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhnkaiqc.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtmpvulysh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.0kj1m.cn/Article/details/gtoacclojf.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gtftafkppv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtacyxbpfy.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gtdlxfqvto.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtjihryrjr.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gtvpooloqd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gtbxfghwkl.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gtwbsvakcc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gthnbahrje.html

[R80] 查看脚本执行耗时
来源：http://dali.vqdsnc.cn/Article/details/gtoemicbrg.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gtmaezwifj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtaosgoouu.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gtbjtccbhj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwycmatrz.html

[S01] C：Hello World
来源：http://dali.fzhhl.top/Article/details/gtkjnfvwaq.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gtmbmgocxz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.snrcjt.cn/Article/details/gtjehjoywl.html

[S02] C：变量与格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtibbdwfqg.html

int a = 10; printf("%d\n", a);
来源：http://dali.aizwys.cn/Article/details/gthyvqdwpk.html

[S03] C：读入整数
来源：http://dali.ehwqpu.com/Article/details/gtzuklrwpp.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gtmoogdypc.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gtbkzxkffz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gogol.net.cn/Article/details/gtyosljkkt.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtylrsprhb.html

strlen(s)
来源：http://dali.snrcjt.cn/Article/details/gtsskigckf.html

[S06] C：字符串比较
来源：http://dali.pycfn.com/Article/details/gtpwqsvnut.html

strcmp(a, b) == 0
来源：http://dali.zycfv.cn/Article/details/gtawdnbvuc.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gtogchnvgu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gtxggbrpuk.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gtmtflgaoa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcnewqbs.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gtyfbwlvde.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gtusrzgngw.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gtkrgbfnwh.html

int *p = &a;  *p = 5;
来源：http://dali.dianchejie.cn/Article/details/gtqcofxghv.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtwwxmkfgj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jlsjyb.cn/Article/details/gtqaiejrew.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sufxvd.cn/Article/details/gtclxklymi.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gtjvpnxxxd.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtnzxilnts.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtsypcigyh.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gtnhekqbot.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtqyqcfrzu.html

[S14] C：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhyjexvl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangshuangyany.cn/Article/details/gtlnduswiz.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gtrjcppyti.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gtuanjeiev.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gtwoetlech.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gtiwsjhmks.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtziotrind.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gtjxtazvlk.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddubqznh.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gthxixhflf.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gtdwiuwtuo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtddhygbei.html

[S20] C：二分查找
来源：http://dali.tian-w.cn/Article/details/gthimsczio.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtxtmodnmo.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtdjobadsn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtpounwxea.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtgelhoqlk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyphfgxfr.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gtnpytibkm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtigzzszsl.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gtacoxnjgx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gtrtermvxw.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gtsctkbqeu.html

memcpy(dst, src, n);
来源：http://dali.vqdsnc.cn/Article/details/gtajcpyjhr.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gtilbdcnep.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gtjslsrtpv.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gtiaejcnoq.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gttbdghulm.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtllwiicbx.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtwbvlxhah.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gtwrksotfr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dashuyun.cn/Article/details/gtlbjujhmb.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gtwbnawopk.html

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gtoteagiir.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gtpxlwywba.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtyscheqdv.html

[S31] C++：Hello World
来源：http://dali.birdmap.top/Article/details/gtcyliumua.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gtcwejpycf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gttunjndtr.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gtomyirhsp.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gtjfalnvwo.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gtjdfpyzwk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtwzzbeuoi.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gtjscjsswy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gttrvouduj.html

[S35] C++：map
来源：http://dali.jianghu66.top/Article/details/gtnrccklyb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtehzkbgmw.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gtqpdusqng.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtbjtvuttp.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gtinsezzcf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtioxbatrq.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtfwfdollh.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtbzfjrdht.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gthznlbwts.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gtmlbeygrm.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gtppgbkyov.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gtsdrnxhtc.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gtrsnttkop.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gtymxodsla.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gtsromeezg.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gtgfktuocw.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtwtsiokxr.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gtblnnitxe.html

[S44] C++：引用传参
来源：http://dali.guowangkeji.top/Article/details/gtigrgoaey.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamgsgvod.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gtbeuzoicr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtdawiacyj.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtvaifmqxg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gtxsntathx.html


<!-- 参考信息 -->