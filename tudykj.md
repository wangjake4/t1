代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtvdbgac.html

[Q73] 查看表状态
来源：http://dali.aibaodan.cn/Article/details/gttrfzxhyh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jianghu66.top/Article/details/gtmkudqtwy.html

[Q74] 强制使用索引
来源：http://dali.hnxiangtu.top/Article/details/gtaxifhaga.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yanxiufei.cn/Article/details/gtphhqecos.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtopnmuopj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtnelpqhtw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gtmvozqrpv.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gtnfojwlyn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gtsckapmuc.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gtiufucjhy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.9152youxi.cn/Article/details/gtnuxmqbyl.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblgwlbla.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cashguo.top/Article/details/gtsmzbwrmi.html

[Q79] 字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpmqkvzf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guannengcc.top/Article/details/gtohtbiccc.html

[Q80] 字符串截取
来源：http://dali.sysykeji.top/Article/details/gtwuetojer.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gttobwezez.html

[Q81] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gthkmsmvsy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtehfjszde.html

[Q82] 字符长度与字节长度
来源：http://dali.zhixingplan.top/Article/details/gtluzytxpt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtvulabfnd.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtoafhycim.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtqhlsgdbr.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gtyzkdxiit.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzviojjwg.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gtgrogluvc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gttaahfqie.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gtjjrwpjhs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gtnaxzydoz.html

[Q87] JSON 字段做条件
来源：http://dali.chenzaomai.com/Article/details/gtunmhwymi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gtwkhkvgit.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gtlntmrepl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gtjvpwiluf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgdwwowl.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gtotxbijth.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258888.top/Article/details/gtloqjfbor.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtzuceapmv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gtujjbprum.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtsubjqcce.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtcyqbfsfc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgclsnicu.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gtjhyiqmxp.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gtbcrpmbut.html

set -euo pipefail
来源：http://dali.meibo888.top/Article/details/gtdqgsieze.html

[R02] 变量赋值与使用
来源：http://dali.aizwys.cn/Article/details/gtkionoxhg.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gtndopzlgs.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gtyimwgedj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gteolvsdqi.html

[R04] 位置参数
来源：http://dali.daxiang520.top/Article/details/gtyxngjinj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gtszzvcknj.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gtuddcyquf.html

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gtnypcnhke.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gtimpohbfn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtawyswhce.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gtogwmhdpq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdtcoxua.html

[R08] 数值比较
来源：http://dali.shzxlz.cn/Article/details/gtlpdlsoii.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gthptgsheg.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtrllqazue.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gtmwaqjnsl.html

[R10] 正则匹配
来源：http://dali.yvedp.cn/Article/details/gtbsnuwayt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtnbxwzgrn.html

[R11] case 多分支
来源：http://dali.ybcxt.top/Article/details/gtpzzfnxht.html

case "$1" in
来源：http://dali.gaohongyu789.top/Article/details/gtlfmxterp.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gttrsuoaoq.html

stop)  echo "停止" ;;
来源：http://dali.shuidangran.top/Article/details/gtuaqgordf.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtitwwnmhg.html

esac
来源：http://dali.dashuyun.cn/Article/details/gtzezllley.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcxjprma.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xziqi.cn/Article/details/gtwgdvjxos.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gtqrttvony.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gtngklbtkb.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gtgorhypbz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtxbqdhogr.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gttownljwm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gtdxilqvtn.html

[R16] until 等待条件
来源：http://dali.jqgufenzy.top/Article/details/gtdvydlltf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtspelkxet.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtvazntata.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbgbzzmn.html

[R18] 遍历数组
来源：http://dali.haohaochexian.top/Article/details/gtoppjxvci.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gtxzagijai.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gtrpnuleuz.html

echo "${#arr[@]}"
来源：http://dali.yj20258888.top/Article/details/gtwuisrstz.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gtgeypitnx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangdashe.top/Article/details/gtcaatnkfs.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gtphkdrqwh.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gtvlnfkpdz.html

[R22] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxobeehi.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gtzsrjrcoj.html

[R23] 字符串替换
来源：http://dali.cashguo.top/Article/details/gtxqbhqvss.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gtdametsnq.html

[R24] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gtdtmiuzhp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.birdmap.top/Article/details/gtbtaylggf.html

[R25] 去后缀 / 去前缀
来源：http://dali.bjfxy.top/Article/details/gtyjcefhss.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuanzhike.top/Article/details/gtiorwgqtr.html

[R26] 命令替换
来源：http://dali.zhoulong.xyz/Article/details/gtgjtxlnbe.html

now=$(date +%F); echo "$now"
来源：http://dali.cdnleiting.top/Article/details/gtinihwstz.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gtuwwixeur.html

echo $((1 + 2 * 3))
来源：http://dali.fengsongda.top/Article/details/gttgoxxycu.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gtlthfjivk.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gtdjzqsdgr.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gttwmxfhxn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gtmbbnclnb.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gtfcfoqqdp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxuanxn.top/Article/details/gttnbhisxj.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gtsdnipzhp.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttxkhkaky.html

[R32] 参数个数校验
来源：http://dali.jyoumei.cn/Article/details/gtijustckn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtcxyavdfn.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gtplznznew.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gtuebnypyy.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtcebltptl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtxnawwnxq.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gtriwcsxjk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258.top/Article/details/gtzqkeghyc.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gttndlzrsw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258.top/Article/details/gtsehrkidl.html

[R37] 把输出赋给变量
来源：http://dali.dashuyun.cn/Article/details/gtkwfzwoky.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtsouhinxj.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gtfivxrnrd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqnhknxt.html

[R39] 重定向标准输出与错误
来源：http://dali.chenzaomai.com/Article/details/gthnvlqidl.html

cmd > out.log 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtfgiuqgef.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gtabuigqrg.html

echo "log" >> out.log
来源：http://dali.vqdsnc.cn/Article/details/gtuvtfffcn.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gteocovbrl.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnfdrtmo.html

[R42] 输入重定向
来源：http://dali.feifeiyinyue.top/Article/details/gtonorqobw.html

wc -l < a.txt
来源：http://dali.haohaochexian.top/Article/details/gtedpziufx.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gtcoovgwpu.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gtmaepknmj.html

[R44] 按修改时间查找
来源：http://dali.jyoumei.cn/Article/details/gtkymmasfb.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gtnwkzhlxg.html

[R45] 批量删除
来源：http://dali.hnxiangtu.top/Article/details/gtsbrchgqe.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gtvkegjrxj.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gtyqdhplcr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gtwqtaofto.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gtucdcfbcc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqgydqjq.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtkgavytwg.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtfwzaaivb.html

[R49] awk 带条件
来源：http://dali.zhoulong.xyz/Article/details/gttjuweytj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtlvqlsscs.html

[R50] awk 求和
来源：http://dali.jlsjyb.cn/Article/details/gtjawsnswf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtgamziqdy.html

[R51] 排序去重取前几
来源：http://dali.aibaodan.cn/Article/details/gteydokhra.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gtimiqzuxo.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gtejskenfc.html

wc -l a.txt
来源：http://dali.daria6918.cn/Article/details/gtvjxhcnjo.html

[R53] 查看文件头与实时尾
来源：http://dali.yuxming.cn/Article/details/gtogohrihv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258888.top/Article/details/gtagoubbvc.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gtbhrdujzv.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gtltesbkmj.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gthleozzgb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtdspyfyiz.html

[R56] 远程拷贝
来源：http://dali.cqqwz.cn/Article/details/gtdowfxvzk.html

scp file user@host:/path/
来源：http://dali.birdmap.top/Article/details/gtrunllbyz.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gtoweyngvj.html

ssh user@host 'uptime'
来源：http://dali.zhoulong.xyz/Article/details/gthrrudltw.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gtonrxryjf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gtwibmmaey.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtbffjnylr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gteeaswlbx.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtiudlarel.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gtwghwaahq.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gtyeciaggk.html

df -h;  du -sh *
来源：http://dali.ppjwa.cn/Article/details/gtkcqvambt.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gtmhxysqhu.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gtfrfkimwt.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtdqxfvwme.html

free -h;  ps aux | grep nginx
来源：http://dali.chenlongwang.top/Article/details/gtvnkpckiv.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gttbqplabz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gtwogwyfou.html

[R65] 查看端口占用
来源：http://dali.zdqjudy.top/Article/details/gteofzbvgs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtkjnmqxvr.html

[R66] 定时任务
来源：http://dali.pycfn.com/Article/details/gtshqfrund.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gtgbqynzri.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gtacurzuwd.html

openssl rand -hex 16
来源：http://dali.wangdashe.top/Article/details/gtqxsrgtnd.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gtebqatkog.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtiivrgfel.html

[R69] 生成随机密码
来源：http://dali.c1oappe.top/Article/details/gtukbobwfl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gtvzokough.html

[R70] 时间戳与互转
来源：http://dali.cdnleiting.top/Article/details/gtcqjcxydc.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhoowmff.html

[R71] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtdhvmmaio.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gtqqnwmqba.html

[R72] 等待端口就绪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomnjzuny.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gteddysnfa.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gtvhvgbxsp.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gtsplkmdut.html

[R74] 批量重命名
来源：http://dali.xziqi.cn/Article/details/gtxrogjqze.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenzaomai.com/Article/details/gtcewduhvq.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtivojlata.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifnjqfvp.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtjhndtpdt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gthyqjdryi.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gtjwdbmkja.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gtbiinilpk.html

[R78] 交互式菜单
来源：http://dali.jlsjyb.cn/Article/details/gtmexxcths.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gtnjjnigxk.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gtsaepztxk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtalctmwpd.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqrgzuzd.html

time ./run.sh
来源：http://dali.ydzc1.top/Article/details/gtpawmqtmy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxnfbafwb.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbziplij.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtqcdszxoi.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtvdnvmtyq.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gtvbbjqnai.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gtldxkivyq.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtjwfpijsu.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gtlydmjalz.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gtghaeqdtg.html

int x; scanf("%d", &x);
来源：http://dali.zhiwuduotai.top/Article/details/gtcmglxqdh.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gtdufiieao.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtnqdthfbz.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtsnzzhfvf.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gthdockecg.html

[S06] C：字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtjqegqxll.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gtkciduqmh.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gtiamtwsxy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gttelxljwy.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gtqvsqqezg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbcewgep.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtxczeapax.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gttrtxkyvj.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gtrehbgpjg.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gtoqkzurqn.html

[S11] C：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrbstusq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gtpvmprrdg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.9152youxi.cn/Article/details/gtlfdnpabh.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtcoczwsam.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gtzersjlrr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtdyxcanlj.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gtdztrduzw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gtesialgqg.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtoeqqzfqr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gtcvbnbuir.html

[S15] C：类型转换
来源：http://dali.nanxuanxn.top/Article/details/gtrjqqsith.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgwpkrxi.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gtrbdxtdbi.html

x |= (1 << 3);
来源：http://dali.xuanzx.com/Article/details/gtuahfurcx.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtevxutkkv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuanzx.com/Article/details/gtkzvmjule.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybpohgvq.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtcbfmzkip.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gtnibhista.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtudcfwuvi.html

[S20] C：二分查找
来源：http://dali.hnxiangtu.top/Article/details/gtdupkkxjc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtpndkbjxq.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkyalmba.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yangfankeji.com/Article/details/gtrjqjfqpu.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtbrhsxaby.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gtcsqgkjyn.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtmjtwbaci.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gtfondzsuj.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gtnokmejkz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gtrrqodghg.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtthpqfews.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gtmutmxckt.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtpttpgxfr.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gthqcoxogb.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gtrbympsut.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtowkjsejn.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtnuaqvwsv.html

static int counter = 0;
来源：http://dali.sysykeji.top/Article/details/gtmvnopyea.html

[S29] C：变参函数
来源：http://dali.yonumen.top/Article/details/gtdftqhcsx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gtcrivllti.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gtngbalyqm.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfrvsrkk.html

#define X_H
来源：http://dali.tianlin.xyz/Article/details/gtgspzfwek.html

#endif
来源：http://dali.cheryme.top/Article/details/gtknvrzqce.html

[S31] C++：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtozjlccel.html

#include <iostream>
来源：http://dali.jlsjyb.cn/Article/details/gtjnagectl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gtglrsfmfh.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtwkgihgeu.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonxsbpop.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gtcwwxasvy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtujxlxgvf.html

[S34] C++：遍历 vector
来源：http://dali.redwolf501.top/Article/details/gttlhrplun.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzchzgqai.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gtaahsewmw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtlslcqtov.html

[S36] C++：unordered_map
来源：http://dali.zhongyouzk.top/Article/details/gtiqogdsec.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtafvcyhfr.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gtwlcclezx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gtfgxspuow.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gtqekuobmx.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtaxjjcfqi.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gtfjgqizdk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtjutgkooo.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gtkgiusazs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gtlzdyadpc.html

[S41] C++：类与构造函数
来源：http://dali.hnxiangtu.top/Article/details/gttefczmei.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtkvqwukkv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gtcnqlvizh.html

class B : public Base { public: void f() override {} };
来源：http://dali.c1oappe.top/Article/details/gtuiztvder.html


<!-- 参考信息 -->