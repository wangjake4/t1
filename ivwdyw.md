代发 wailian999

[Q76] 按天统计
来源：http://dali.andypj.xyz/Article/details/gtckrdqbuo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aibaodan.cn/Article/details/gtvnibdzax.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gtbjzqknxn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gtvpyhuawx.html

[Q78] 当前时间
来源：http://dali.daxiang520.top/Article/details/gtovzqaltd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gtpejiryga.html

[Q79] 字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gtqgvgubfx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gteuacxrvy.html

[Q80] 字符串截取
来源：http://dali.chenzaomai.com/Article/details/gtbdshkedp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtwtehclan.html

[Q81] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtnlrwudsv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtooykdimn.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gtlmnlzjfa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtyowitrmo.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gtttufntds.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtnjzbehwg.html

[Q84] 去除首尾空格
来源：http://dali.tianlin.xyz/Article/details/gtpbxjtzbh.html

SELECT TRIM(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtudxgzclf.html

[Q85] 数值取整
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrbncuku.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gtfftkptai.html

[Q86] 读取 JSON 字段
来源：http://dali.hywenlv.cn/Article/details/gtrojgkcju.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gtmjwzwnnc.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtchlckgen.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgrqlfhy.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gtufzcydtt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gtyxnynxak.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtpcllluqz.html

[Q89] 判断表是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibjhrkxo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtlgdtoazr.html

[Q90] 生成序号列
来源：http://dali.zhixingplan.top/Article/details/gtmyoqlsab.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xziqi.cn/Article/details/gtxgqnrdyr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtyrgoxjsd.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtsmpyoybr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpefwvsqr.html

[R01] shebang 与严格模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowkocujb.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gttdeyztyg.html

set -euo pipefail
来源：http://dali.cucudq.cn/Article/details/gtqpscyylr.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gtxofypsso.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gtjubzcahz.html

[R03] 只读变量
来源：http://dali.hywenlv.cn/Article/details/gtukqkdfpc.html

readonly PI=3.14
来源：http://dali.pengpengdd.cyou/Article/details/gtdfpgmohp.html

[R04] 位置参数
来源：http://dali.sweek.top/Article/details/gticomuidn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gtnrdunwfo.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gtgkhosark.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gtyesmrkhd.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gtshzasmrb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtbatfteni.html

[R07] if 判断文件
来源：http://dali.jqgufenzy.top/Article/details/gtdtxjtwwu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xinyue.icu/Article/details/gtujdvctwh.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gtbiparwll.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gtewsnudza.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlcatznh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbahushmn.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtiijxpmeq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.smart0.xyz/Article/details/gtlznensde.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gtpvfmrdgp.html

case "$1" in
来源：http://dali.nwbrower.top/Article/details/gtjvqmygff.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtkhefjttq.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gttkbkwkdm.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtbdfmgmkh.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gtresphyyo.html

[R12] for 遍历文件
来源：http://dali.pycfn.com/Article/details/gtzjgeurmv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenzaomai.com/Article/details/gtykwlkkdp.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gtznsxjolg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtsvpfizqp.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gtyktmteoo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtbqnveywr.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtjcmypmij.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gtpypoibbi.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gtufplwkee.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtbpxhlpsi.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gtbscbjurv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aibaodan.cn/Article/details/gtghbeebjr.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gtursaeylz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.havefunace.top/Article/details/gtgowjmnsv.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtoayttlxn.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gtwnwxjoyj.html

[R20] 关联数组（字典）
来源：http://dali.chenjidiqi.icu/Article/details/gtlpfcaxis.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtscdrphmp.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gtjvuyrkuk.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gtepmeusyv.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtvljgshke.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gthgldqdku.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtozjkouvo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenlongwang.top/Article/details/gtscfutkhr.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtazopafdw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gtbgqqtsac.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gtpilzkash.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gtxtkrgxso.html

[R26] 命令替换
来源：http://dali.cqqwz.cn/Article/details/gtakcftpwk.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gtehheylno.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gtitvdogam.html

echo $((1 + 2 * 3))
来源：http://dali.nwbrower.top/Article/details/gtemelulnv.html

[R28] 浮点运算
来源：http://dali.jinqigfzy.top/Article/details/gtwxstmnet.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gtplupfcxu.html

[R29] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtcxukefrl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxuanxn.top/Article/details/gtgonacufi.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gtfezuvvor.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gtnbwfpqsf.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gtjthrhsik.html

f() { local x=1; echo "$x"; }
来源：http://dali.daxiang520.top/Article/details/gtopfioayf.html

[R32] 参数个数校验
来源：http://dali.hysaishi.cn/Article/details/gtqggzlawk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtwpopvelg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhongyouzk.top/Article/details/gtrdzlbgre.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gtprtaqmsr.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gtepmmjpkh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtuamyojps.html

[R35] 后台执行并等待
来源：http://dali.cqqwz.cn/Article/details/gtjzbzdnen.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gthzeggqcf.html

[R36] 并发执行多个任务
来源：http://dali.zhiwuduotai.top/Article/details/gtivxcegxs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gtkkvkjzkk.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtzwutaiyg.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gtfqcskojt.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbsxzang.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdycdzzwh.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuhzhytc.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtpxchsgmm.html

[R40] 追加写日志
来源：http://dali.jlsjyb.cn/Article/details/gtmfzxvhgh.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gtzlsjyatf.html

[R41] 丢弃输出
来源：http://dali.nanxinkj.top/Article/details/gtdaeeaxkb.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gtdwvlijnv.html

[R42] 输入重定向
来源：http://dali.tianlin.xyz/Article/details/gtikzdupzt.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtjbxetufc.html

[R43] 按名字查找文件
来源：http://dali.zhongyouzk.top/Article/details/gtzgueiesx.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gtfllfrpdw.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gtfuljzwye.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gttdyftwrm.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gtjksfboob.html

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gtaabyufsh.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gttsneoaai.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gtmuubqqar.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtcfnybhja.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gtsqruzxej.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuqfxvoa.html

awk '{print $1, $3}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtfrqultww.html

[R49] awk 带条件
来源：http://dali.yonumen.top/Article/details/gthmtrjypm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gtyppdlbsp.html

[R50] awk 求和
来源：http://dali.zhengqikj.top/Article/details/gtagsxryvz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvfxmafw.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gtklxrvria.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gtcmjwvrlv.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gtjxjuhfur.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtaaqyefal.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gttxzwiane.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfuvbbyk.html

[R54] 比较两个文件
来源：http://dali.chenzaomai.com/Article/details/gtsurazvjy.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gtxoqfaarf.html

[R55] 压缩与解压
来源：http://dali.wangshuangyany.cn/Article/details/gthnvvslcg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sxryk.cn/Article/details/gtijwouqqk.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gtfalmchek.html

scp file user@host:/path/
来源：http://dali.zycfv.cn/Article/details/gtckmonypz.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimyllxma.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtkvsqgdcr.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtndywyxuv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenzaomai.com/Article/details/gtwnulvwgz.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtwjxgedsf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gtlrnivqba.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtekldfejz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigufen.top/Article/details/gtvrpcgols.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gtaydpjswc.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gttpfxuhfd.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gtdtgyxjkr.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gtiackooli.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gtmrxtmkxr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhengqikj.top/Article/details/gtawfadivm.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gtzfycyklt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gtvwxrlizl.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gttllbqabd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gtjigmcfmt.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gtezqdhwri.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gtutrlodtf.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gtppagaiop.html

openssl rand -hex 16
来源：http://dali.hysaishi.cn/Article/details/gtqqxmgbis.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gtgqunoeyh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gtpxiuqrta.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gtwxjekewk.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gtjumhoych.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdxpegty.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gtszdunxau.html

[R71] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gthgjrkedj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gtrtpkplho.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gtrxbfpvwg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtlzhmnndl.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gtrobtvxzf.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gtsknxmqwl.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gtxtxdthts.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtasrblpqz.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtipmajyzs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhengqikj.top/Article/details/gtfeecajdb.html

[R76] 使用临时文件
来源：http://dali.0kj1m.cn/Article/details/gtdtlrbjut.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gttwmjcjpe.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gtvaddchhg.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gtrdgexkps.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gtysdtyaik.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gtvurjkscl.html

[R79] 解析命令行选项
来源：http://dali.hfpthk.cn/Article/details/gtldvnhdbh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gtsgdqalam.html

[R80] 查看脚本执行耗时
来源：http://dali.daxiang520.top/Article/details/gtlxmvrsyd.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gtvthwhtwq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdobeuvpq.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gtrakffrtr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfucddefr.html

[S01] C：Hello World
来源：http://dali.cheryme.top/Article/details/gtthaikgpj.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gttvecjfgr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigufen.top/Article/details/gtinfgciiy.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtztqsazqh.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gtadndbyxa.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gtavnhqhyi.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gttipolmsd.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtlrjawabw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtudoxrjpq.html

[S05] C：字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtemrubnfb.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gtrvyhptsc.html

[S06] C：字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtkovsutle.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gtsbghlzth.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gtlxavbajk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gtdebmimnz.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gtgamendbc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tian-w.cn/Article/details/gttqgceqsp.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gttsjqcukx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtwaxbebia.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gtygoxxlhb.html

int *p = &a;  *p = 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtesblqtsh.html

[S11] C：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtbsolguch.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gtsliszzvl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gtpwdnfrxn.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtdwnmvgdi.html

[S12] C：写文件
来源：http://dali.yonumen.top/Article/details/gtzwwrsdzo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cashguo.top/Article/details/gtuwzrppqp.html

[S13] C：宏定义
来源：http://dali.yuanzhike.top/Article/details/gtgmdoiswt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gtqwvdkehb.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtvoewezpj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gtogdyokyz.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gtedzrlvfs.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gtzukhmizv.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gtwkjcnhdd.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gtstqzgsiz.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtmfrcaywy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gtnlgoicyi.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gttxcaabxm.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtdarybgho.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtsfgbiyir.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtktvueaod.html

[S20] C：二分查找
来源：http://dali.daxiang520.top/Article/details/gtcsshvfrf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtfsjrralh.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gtztmxjsjf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gtpiisuvti.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gttrabbmbr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xylfe.cn/Article/details/gtraoozjds.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gtbypydllj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gtkqteyxde.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gtacjqtvnb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gtesudmhdp.html

[S25] C：内存拷贝
来源：http://dali.tian-w.cn/Article/details/gtrapzmoab.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gtysqfaacp.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gtkfbzefam.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gtoaoqmrbm.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gttkcupdzf.html

const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtwbondkyb.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gtwcsacdto.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtgkgizfzw.html

[S29] C：变参函数
来源：http://dali.guannengcc.top/Article/details/gtppkmsquu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gtlbdxugys.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gteyrhcjix.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gtcjdiptgk.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gtsvjstnvx.html

#endif
来源：http://dali.0kj1m.cn/Article/details/gtyshtpyso.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gthdxdqgvz.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gtddyjumpc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gtmpjbbbki.html

[S32] C++：字符串
来源：http://dali.yangfankeji.com/Article/details/gtadganhfz.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gtnxwrnrau.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gtyidofxxp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gtsufvynqj.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gtegdeodst.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gtupxxekme.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gtvvgjdcxh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gttrrvgbvm.html

[S36] C++：unordered_map
来源：http://dali.yj20258888.top/Article/details/gtombkrlaa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtmivmhcbs.html

[S37] C++：set
来源：http://dali.cheryme.top/Article/details/gtueqyajot.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.smart0.xyz/Article/details/gtmihlnfsk.html

[S38] C++：排序
来源：http://dali.c1oappe.top/Article/details/gtbgimcqvr.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtzghgvfkf.html

[S39] C++：自定义比较器排序
来源：http://dali.iojbl.cn/Article/details/gtuzmngush.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gtryvuwatj.html

[S40] C++：查找元素
来源：http://dali.sweek.top/Article/details/gtlbyidxxv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gtmmaqrjnq.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtztvwapzy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gogol.net.cn/Article/details/gtufscpulk.html

[S42] C++：继承与虚函数
来源：http://dali.andypj.xyz/Article/details/gtmchoqkcp.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gtsdxqijxd.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gtlfemyqrg.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gtetkgvxdc.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gttqzpwxhv.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkjrafke.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gtxwrhmyqv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hongshengwenyu.top/Article/details/gtfjlqvoxh.html

[S46] C++：函数模板
来源：http://dali.dashuyun.cn/Article/details/gthaaivzfn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gtueyjxwmi.html


<!-- 参考信息 -->