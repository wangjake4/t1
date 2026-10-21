代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gtauooqhjo.html

[Q73] 查看表状态
来源：http://dali.xylfe.cn/Article/details/gtrtqijnxc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gtyxcpeiyw.html

[Q74] 强制使用索引
来源：http://dali.yj20258888.top/Article/details/gtjeeghduh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gtfybwrmkw.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtdcgzghmj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtkupkgyqr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gtkdyxephk.html

[Q76] 按天统计
来源：http://dali.chenjidiqi.icu/Article/details/gtsyweahlz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gtubdoorww.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gtzhvocxxp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangshuangyany.cn/Article/details/gtxtzcyafj.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqrtlbtu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gtfzfxsiac.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gtzwtnpoby.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gtsczzzqfq.html

[Q80] 字符串截取
来源：http://dali.hfpthk.cn/Article/details/gtohlvrdcq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtlpqevqqh.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gttbbdoysl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtcxcfxjdk.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwihsjswa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtcfrlxapb.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtgramzixd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsbqpisz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gtfmqucrak.html

SELECT TRIM(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtlonqglce.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gtkaeimgvh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gtuyuilnvy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhengqikj.top/Article/details/gtkclniodw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gtllclntki.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gtkmsbeoko.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jiagoushi.top/Article/details/gtmmndbyry.html

[Q88] 行转列（条件聚合）
来源：http://dali.havefunace.top/Article/details/gtsfnpjhwo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gaohongyu789.top/Article/details/gtfmvqeyhw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gtgoiuybeo.html

[Q89] 判断表是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtroorsxyy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gtqvhfssvl.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gtalzcfimg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shuidangran.top/Article/details/gtoiesdmbw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtzpqmuxph.html

R. Bash 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtityfvauh.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvjgtldgs.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gtuyysjbyk.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gtswknhebn.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gtwhvtfpgy.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gtdbsgcuyu.html

name="Tom"; echo "$name"
来源：http://dali.jinqigfzy.top/Article/details/gtlnvwzwfb.html

[R03] 只读变量
来源：http://dali.xuanzx.com/Article/details/gtppwuqufx.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gtwxpssokl.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gtvjuxtdnx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gtwzraevms.html

[R05] 参数默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtjlqpaktz.html

name="${1:-default}"
来源：http://dali.bjfxy.top/Article/details/gtkrfcsamb.html

[R06] 判断命令是否存在
来源：http://dali.mhx1999.top/Article/details/gtxzzeegui.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtrutfnhpk.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gtpgwszlsl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gtyyfskust.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtpouisokr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gtvazgcsag.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gtyyjjldsb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.0kj1m.cn/Article/details/gtlhfrkmci.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gtumelzahy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gtqydcoawp.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gtyhgsiftd.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gtirzqdwym.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gtvbjvrfku.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gtyuqfjnrd.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtqdwmkktr.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gtxrkmjaxl.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gtifdjvisb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gtpuxotngx.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtxoxiesmw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtnrtkdpob.html

[R14] C 风格 for
来源：http://dali.chenjidiqi.icu/Article/details/gtputiaxew.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtnyqvhwbi.html

[R15] while 逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtswdggreo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guannengcc.top/Article/details/gtkmjrdoti.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gtgrrrirdk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtuizggahc.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gtyhnyjbbg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gtkyoppxvi.html

[R18] 遍历数组
来源：http://dali.cdnleiting.top/Article/details/gtxeazyqod.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zycfv.cn/Article/details/gtcshseltk.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtsebbgqbq.html

echo "${#arr[@]}"
来源：http://dali.vqdsnc.cn/Article/details/gtjzpthpfx.html

[R20] 关联数组（字典）
来源：http://dali.hnqzz.top/Article/details/gtrizzlefj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gtsasljcya.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtxzcfaulf.html

echo "${#s}"
来源：http://dali.haohaochexian.top/Article/details/gtggkimhqb.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gtxkventhr.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gtdqcfvzmb.html

[R23] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gthwwjfhdx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gtstheizxh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtzcrhzgyd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtehltdsru.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gtlahybonx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.bjfxy.top/Article/details/gtlpywpqkb.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gtupxjmttk.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgorngexc.html

[R27] 算术展开
来源：http://dali.jqgufenzy.top/Article/details/gtzcdljtbo.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gtnvumrbjw.html

[R28] 浮点运算
来源：http://dali.xuanzx.com/Article/details/gttueabrub.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtpjzxepfe.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtoofprpqo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkioswix.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyajgzjj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxuanxn.top/Article/details/gtxerlzpxu.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gttpngkpuw.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gtfodexfac.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gtzfebmizv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtiwnzubpv.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gtejgsmlld.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ivvv.top/Article/details/gtyrbciuuy.html

[R34] 退出时清理
来源：http://dali.0kj1m.cn/Article/details/gtodedxopl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtdpnwcjeq.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtdvpfzssn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.kuanghao11.cn/Article/details/gtnhjpisbe.html

[R36] 并发执行多个任务
来源：http://dali.yangfankeji.com/Article/details/gtqsktuyke.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnsfhiqn.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gtmblxyvjx.html

files=$(ls -1)
来源：http://dali.haohaochexian.top/Article/details/gtwisqmuum.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gttecxxmnh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gtkqmoqraa.html

[R39] 重定向标准输出与错误
来源：http://dali.jlsjyb.cn/Article/details/gtmopqagvp.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtmofehbaq.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtqqcxwrrw.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gthfghqres.html

[R41] 丢弃输出
来源：http://dali.bjfxy.top/Article/details/gtxawjetcg.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtqbddibxc.html

[R42] 输入重定向
来源：http://dali.cucudq.cn/Article/details/gteonplijy.html

wc -l < a.txt
来源：http://dali.yj202588.top/Article/details/gtxuxaqyug.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gtqwsnwgov.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gtcnqypjxj.html

[R44] 按修改时间查找
来源：http://dali.tianlin.xyz/Article/details/gtvgdhusmy.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gtqcgrnixv.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gtwurnecqh.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gtonjkkbjc.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gtqzavtmbf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuanzhike.top/Article/details/gtwwqjmwjg.html

[R47] sed 单行替换
来源：http://dali.daria6918.cn/Article/details/gtexlmqssz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gtlkjzxjbd.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gtfskcxkpv.html

awk '{print $1, $3}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtesscuove.html

[R49] awk 带条件
来源：http://dali.bjfxy.top/Article/details/gtzczgkxsj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuetiantiany.cn/Article/details/gtjcrhuvto.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gtmvlymgkg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gteabmvjlt.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtjcgkhqbs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gteecteckw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gtlijpklva.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gttrxddabb.html

[R53] 查看文件头与实时尾
来源：http://dali.shangyingyoupin.top/Article/details/gtkvkavsax.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenjidiqi.icu/Article/details/gtaqmaazrp.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gtlzghwvxj.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gtchvqcyxd.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gthynagkcu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtwnhkfpze.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtovazchcz.html

scp file user@host:/path/
来源：http://dali.mhx1999.top/Article/details/gtmkasylvz.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gtpcqakyoe.html

ssh user@host 'uptime'
来源：http://dali.yongpay.top/Article/details/gthqlyqwid.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtrvebdtyq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gtocihgvkv.html

[R59] 发 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gtshetycci.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cqqwz.cn/Article/details/gtwkipqjsu.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtlxoqddky.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cqqwz.cn/Article/details/gtzazwfwfu.html

[R61] 磁盘占用
来源：http://dali.yanxiufei.cn/Article/details/gtlnsnymsy.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gtvoddfsva.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gtbqgfawfg.html

du -ah . | sort -rh | head -10
来源：http://dali.havefunace.top/Article/details/gtjoxhacaf.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gtpxrxscan.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gtlxograkk.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gtjleahiwm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtphhuwyna.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gtnrmzoono.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtmwpqvgai.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gtsqbgywwl.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gtqfzegdqq.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gtnsherpku.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gtmcvfjelk.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gttbixreuf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtkocrveew.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gtgblxzhls.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtilauijho.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gtcoarjovr.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gtnnqgxfsp.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gttgwmjdwf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gtuklkntap.html

[R72] 等待端口就绪
来源：http://dali.gzhubu.top/Article/details/gtiobducow.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqtxpppk.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gtmwxblnkz.html

split -l 1000 big.log part_
来源：http://dali.nanxuanxn.top/Article/details/gtotleydos.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtqqamzfbv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gtdgnyeysk.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gtvnryklls.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gtahjlfznp.html

[R76] 使用临时文件
来源：http://dali.pycfn.com/Article/details/gtwbwbcoib.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtkkvtjgzo.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gtpyniwkeq.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtmdbmupzm.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gtlpmtjlto.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gtjtnttlqj.html

[R79] 解析命令行选项
来源：http://dali.jinqigufen.top/Article/details/gtrstyljxi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gtptjfltku.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gtjczfpupc.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gthymnsrar.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtkvlqmnxd.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtcktvawyh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtogxgkpay.html

[S01] C：Hello World
来源：http://dali.sxryk.cn/Article/details/gtgwvtttpb.html

#include <stdio.h>
来源：http://dali.zhoulong.xyz/Article/details/gtrtqtyxdk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhengqikj.top/Article/details/gtpyvlzxdr.html

[S02] C：变量与格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtzvoyxxsx.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gteytpaysk.html

[S03] C：读入整数
来源：http://dali.birdmap.top/Article/details/gtqrovhvuv.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gtoajltwvy.html

[S04] C：字符串复制
来源：http://dali.dashuyun.cn/Article/details/gtcchichku.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jiagoushi.top/Article/details/gtjoymqjxe.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtsqiyhgyy.html

strlen(s)
来源：http://dali.316326.xyz/Article/details/gtbpcapdtf.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtvawqxpso.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gtgrqcsqmp.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtozmskgfh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yvedp.cn/Article/details/gtinircbxz.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gtvvtjlroy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gtxgegwrjb.html

[S09] C：结构体定义与初始化
来源：http://dali.birdmap.top/Article/details/gtnceegdln.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tanke756.top/Article/details/gtaiyhmkeh.html

[S10] C：指针与解引用
来源：http://dali.dianchejie.cn/Article/details/gtnxskeuxv.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gtjxvavlsy.html

[S11] C：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtyckvcvig.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gtrpqcheor.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daria6918.cn/Article/details/gthxkhyayz.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gttiwhedjy.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtvcflimxn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtkualzqsc.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gtnmtanefp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gtmmwvamft.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gtnogpfyix.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gtxqqwtgdb.html

[S15] C：类型转换
来源：http://dali.gzhubu.top/Article/details/gthppjpyri.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzbcnjgb.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gtvrrxgatc.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gtkwqivwbu.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gthkgzkfwd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtpcvetotb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gthuklggah.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gttglnpibd.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gtsiekfris.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtgzetdkfx.html

[S20] C：二分查找
来源：http://dali.ydzc1.top/Article/details/gtulfglstt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtzxwcrxva.html

[S21] C：字符类别判断
来源：http://dali.jlsjyb.cn/Article/details/gtlltbhkxk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gtyeraufwd.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gtxibpcubr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gtjxzrxndc.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gttdaapqcq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gtureokkvh.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gtnioocvwf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yvedp.cn/Article/details/gtbcniclgk.html

[S25] C：内存拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtnvebieru.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gtgfqswwed.html

[S26] C：内存清零
来源：http://dali.hnxiangtu.top/Article/details/gtgyimoefv.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gthsagnbxf.html

[S27] C：定义常量
来源：http://dali.gotoacloud.top/Article/details/gtxjzyjicn.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtdhplstyi.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gtfulpcsrp.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gtorxijyez.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gtridousio.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gttrrfwxep.html

[S30] C：头文件保护
来源：http://dali.zhengqikj.top/Article/details/gtdbbxjfby.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gttkbuzogs.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gtmsiagmxw.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gttsbtvvyf.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gtfjrjljgv.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtwngsxncv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.meibo888.top/Article/details/gtiautnppx.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gtiagrhssg.html

std::string s = "hi";  s += "!";
来源：http://dali.ybcxt.top/Article/details/gtzsrpwiji.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gtovwmiwau.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gtxsnvzwnw.html

[S34] C++：遍历 vector
来源：http://dali.jiagoushi.top/Article/details/gtgkwapaag.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gtamiuotoo.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gtcjiaviwy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtedteubvy.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gtefknqrsd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtrhsnajcx.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gtcihzxjpc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gtzngbdqmd.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gtsruoueff.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gtgqwsxhsx.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprhkaiym.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shangyingyoupin.top/Article/details/gtiazrwxwb.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gtiabzmgbm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fengsongda.top/Article/details/gtcfciamar.html

[S41] C++：类与构造函数
来源：http://dali.cheryme.top/Article/details/gtyexftnbe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.c1oappe.top/Article/details/gtqwcxsnnq.html

[S42] C++：继承与虚函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsocrtpbx.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gtpebpueoq.html


<!-- 参考信息 -->