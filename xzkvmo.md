代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gt2bmussdmx.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iuulrbye.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gt2seklncjh.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gt2pemimrax.html

ANALYZE TABLE users;
来源：http://dali.hammf.cn/Article/details/gt2vqhuztkg.html

[Q71] 查看建表语句
来源：http://dali.aibaodan.cn/Article/details/gt2tlxolxsa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gogol.net.cn/Article/details/gt2ivxheihu.html

[Q72] 查看索引
来源：http://dali.yanxiufei.cn/Article/details/gt2rnktotuh.html

SHOW INDEX FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2pgmnurqz.html

[Q73] 查看表状态
来源：http://dali.xinyue.icu/Article/details/gt2poljdiak.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.redwolf501.top/Article/details/gt2vtdpyvac.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gt2vavfqegk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbymuymr.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihppyeic.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2lifwvvpf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hsbahgfc.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gt2aquyffeg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tian-w.cn/Article/details/gt2yuqdcybp.html

[Q77] 时间加减
来源：http://dali.pycfn.com/Article/details/gt2uwswiuts.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gt2hqfctheh.html

[Q78] 当前时间
来源：http://dali.jyoumei.cn/Article/details/gt2cujojtzz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gt2yqrneojs.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gt2hcdgsyud.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cucudq.cn/Article/details/gt2uuqcakda.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gt2ftrjzqfk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2eitzmcsg.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gt2ticcedkb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2alvvvaka.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gt2qrtnujji.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2gipesrcw.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gt2gmnmgarf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2farlkdka.html

[Q84] 去除首尾空格
来源：http://dali.c1oappe.top/Article/details/gt2uighmwsf.html

SELECT TRIM(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2invhanim.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gt2hffnejst.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gt2soooaayn.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gt2ykhwcdxd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ugnynzec.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gt2uwsvpxyy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xziqi.cn/Article/details/gt2jrhznfxw.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gt2klxfbwpm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gt2tnkoblnt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2ssooagwo.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gt2srlggidv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gt2cogtmjnk.html

[Q90] 生成序号列
来源：http://dali.yonumen.top/Article/details/gt2lamhtyse.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ehwqpu.com/Article/details/gt2eotynrws.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2bwflkqth.html

R. Bash 专题
来源：http://dali.bjfxy.top/Article/details/gt2mqfsutcc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2txpyktkn.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gt2ivavvlqp.html

#!/usr/bin/env bash
来源：http://dali.nwbrower.top/Article/details/gt2idstmgvv.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gt2brvrblbq.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gt2btdzzgkk.html

name="Tom"; echo "$name"
来源：http://dali.ppjwa.cn/Article/details/gt2fxmhbtxi.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gt2ccwbyikx.html

readonly PI=3.14
来源：http://dali.cdnleiting.top/Article/details/gt2yucqjsgi.html

[R04] 位置参数
来源：http://dali.wangdashe.top/Article/details/gt2nayyoiqa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gt2ozarkhof.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gt2wynkwwfr.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gt2trojsbay.html

[R06] 判断命令是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2blsiozuj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gt2bozqklco.html

[R07] if 判断文件
来源：http://dali.bjfxy.top/Article/details/gt2vnimlrkn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcndeitm.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gt2kmsdkynq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2ziwqbmac.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gt2whtnfpim.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2hpnxmmao.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gt2htkjhlax.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gt2vvfjdogd.html

[R11] case 多分支
来源：http://dali.ybcxt.top/Article/details/gt2tstorezm.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2raeucqlg.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gt2gdhbpeiz.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gt2xcwzpojh.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gt2kloieuun.html

esac
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2znxmhcya.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gt2efwskidn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2vkmggtqz.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gt2alikuqfd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2waufdvdi.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gt2qscniwkp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gt2cbyhtkws.html

[R15] while 逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2hufoidgw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fcpfpmab.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gt2yjhvkcfn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2rupteftc.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gt2ioqtylgo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gt2zhpovinf.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gt2iizozyxf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gt2jgiexcgk.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gt2jtpvolut.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gt2xfobtwmx.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gt2zfylvriw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yangfankeji.com/Article/details/gt2sfnxeciw.html

[R21] 字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxdudion.html

echo "${#s}"
来源：http://dali.cdnleiting.top/Article/details/gt2xikrgune.html

[R22] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gt2bqdcmbkf.html

echo "${s:0:5}"
来源：http://dali.ehwqpu.com/Article/details/gt2erqqetbx.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2isyjlshj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gt2mkhzhiof.html

[R24] 大小写转换
来源：http://dali.havefunace.top/Article/details/gt2uuemlrgw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gt2uiupshcw.html

[R25] 去后缀 / 去前缀
来源：http://dali.ppjwa.cn/Article/details/gt2yayvyuup.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gt2osjoffin.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gt2irluvrag.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gt2oclrxphw.html

[R27] 算术展开
来源：http://dali.sysykeji.top/Article/details/gt2vgddosfu.html

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gt2wwuveuvl.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gt2tyjqkbob.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gt2eqieiern.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gt2svjbaepj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gt2pnqflycl.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gt2ujzvpgfs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gt2ioagaxxy.html

[R31] 局部变量
来源：http://dali.havefunace.top/Article/details/gt2ennuhwcb.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gt2iukaumws.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gt2hssumetx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2desdtkfj.html

[R33] 捕获错误并提示行号
来源：http://dali.fengsongda.top/Article/details/gt2bvmdnudu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fzhhl.top/Article/details/gt2amykxqoc.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gt2cnmyhhsj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gt2qbocgaci.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gt2twxhytvx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znxgsfoe.html

[R36] 并发执行多个任务
来源：http://dali.yj20258.top/Article/details/gt2hgvkggcg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gt2vtdarhyv.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gt2oilnigyw.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gt2vqrqjdje.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gt2ntoltgpk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gt2igdotidv.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gt2rsgzeprn.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gt2qniqeofv.html

[R40] 追加写日志
来源：http://dali.cucudq.cn/Article/details/gt2rdydtpmo.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gt2dttoabbr.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gt2rnhtoezk.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gt2jcwbakry.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gt2bclnnwyf.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2hsebpkbs.html

[R43] 按名字查找文件
来源：http://dali.snrcjt.cn/Article/details/gt2ajxylyrj.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gt2sitkpdsk.html

[R44] 按修改时间查找
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewuaeuxm.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gt2vjqccezj.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gt2zegyexra.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gt2mbznhxjt.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gt2gxzzkylw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gt2yclbwkmr.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gt2irutaktj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2eyvrhzkz.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzvqmdwe.html

awk '{print $1, $3}' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2ognyobgy.html

[R49] awk 带条件
来源：http://dali.yanxiufei.cn/Article/details/gt2hhmnhdiy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsfnarv.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gt2vkfzxhzc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2cpqmammb.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gt2iypqrcaz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gt2kfhwakvl.html

[R52] 统计行数
来源：http://dali.zhoulong.xyz/Article/details/gt2hqyjnvgh.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gt2hixzstrs.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gt2nglwhjpm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daxiang520.top/Article/details/gt2aefthtiu.html

[R54] 比较两个文件
来源：http://dali.ppjwa.cn/Article/details/gt2szqukwem.html

diff a.txt b.txt
来源：http://dali.ivvv.top/Article/details/gt2yqmsnvgl.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gt2thywsylg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fzhhl.top/Article/details/gt2gllmopli.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccbxgaif.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gt2ydeatyhy.html

[R57] 远程执行命令
来源：http://dali.sufxvd.cn/Article/details/gt2wvrkkbaf.html

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hchwycvh.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gt2dlbkhuic.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgufenzy.top/Article/details/gt2daekkint.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sztxctln.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gt2gvmvrxla.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajghtjwv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gt2hoqynamo.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gt2cprjydrz.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gt2owzgguvl.html

[R62] 找最占空间的文件
来源：http://dali.guannengcc.top/Article/details/gt2wtdmlcth.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gt2eauxdmtd.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gt2tnurvemz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhengqikj.top/Article/details/gt2mrmxqcob.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdmvrfcj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gt2dmnssoro.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gt2jmyatuvw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwlxmwci.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gt2urphmfgn.html

crontab -e;  crontab -l
来源：http://dali.chenlongwang.top/Article/details/gt2tuavxrho.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gt2vdlsvgqg.html

openssl rand -hex 16
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sargommq.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gt2fxhseynx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2agzzvhpu.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gt2rqskfnqc.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gt2ikggwtac.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gt2xkgeczdx.html

date +%s;  date -d @1700000000
来源：http://dali.hfpthk.cn/Article/details/gt2qwqyiorj.html

[R71] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gt2rwyhuktn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2frqfgffg.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gt2icjpggfy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gt2wooijzzk.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gt2hdfcqlvt.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gt2uxzfcueq.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gt2bpuglusd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gt2bnpxhyxo.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2owqnxxpb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gt2gsxpefjy.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gt2pyuognpf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gt2oceffpcr.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ayhxelti.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gt2rqkljwlh.html

[R78] 交互式菜单
来源：http://dali.jiagoushi.top/Article/details/gt2nhbzphvj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gt2ixxunqsg.html

[R79] 解析命令行选项
来源：http://dali.guannengcc.top/Article/details/gt2frdcwdlc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbqlonxq.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gt2qmgtfsgs.html

time ./run.sh
来源：http://dali.redwolf501.top/Article/details/gt2ujzcmkoj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2irmldtrf.html

S. C / C++ 专题
来源：http://dali.tanke756.top/Article/details/gt2jahucvss.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2vmwveilu.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kztzgujr.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gt2wxsgsssc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gt2khilgdrw.html

[S02] C：变量与格式化输出
来源：http://dali.yueranfly.top/Article/details/gt2woykhwgp.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gt2sfhtxmxu.html

[S03] C：读入整数
来源：http://dali.zycfv.cn/Article/details/gt2megujwtz.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gt2abyzthdx.html

[S04] C：字符串复制
来源：http://dali.tanke756.top/Article/details/gt2rkexcbsm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gt2idfnfqwy.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gt2uydfjhyc.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gt2ndtxbmyp.html

[S06] C：字符串比较
来源：http://dali.pycfn.com/Article/details/gt2jzlgxkes.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gt2wriikjyh.html

[S07] C：数组遍历求和
来源：http://dali.hnqzz.top/Article/details/gt2jjugbiro.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gt2tvfmisoc.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csvzedkg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruwmpcwf.html

[S09] C：结构体定义与初始化
来源：http://dali.yj202588.top/Article/details/gt2yzythloy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxxvpnar.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gt2aoulujxr.html

int *p = &a;  *p = 5;
来源：http://dali.cqqwz.cn/Article/details/gt2yafmsbir.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2glglgjoi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yonumen.top/Article/details/gt2hiotmxpm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gt2pnfqtbri.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gt2trnkycwl.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gt2vtcffbfj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gt2icscurbr.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gt2elxaumdl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ivvv.top/Article/details/gt2mvwelgjy.html

[S14] C：枚举
来源：http://dali.tian-w.cn/Article/details/gt2twgbhmtn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gt2vrmnnnzt.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gt2qiaikyxx.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gt2fzxlvihf.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gt2lkpzsigg.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gt2ejyqreyp.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2giovnmcf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gt2iyndsoew.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gt2vjbdwegz.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wksztfoi.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gt2tdazoymp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gt2mcbcknsx.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gt2yhuabvvm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2geuilifm.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gt2jhbpjwrp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogsslssh.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gt2zwljaabc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rogmznru.html

[S23] C：随机数
来源：http://dali.yonumen.top/Article/details/gt2dgipzbwu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gt2iwiifvrm.html

[S24] C：获取本地时间
来源：http://dali.shzxlz.cn/Article/details/gt2qmvjwlfb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xinyue.icu/Article/details/gt2athyaarj.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gt2odkytfsr.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gt2gcapqgov.html

[S26] C：内存清零
来源：http://dali.cashguo.top/Article/details/gt2odtmnmcz.html

memset(a, 0, sizeof a);
来源：http://dali.aibaodan.cn/Article/details/gt2kdcfqnrs.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gt2xdlftgjp.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2vctbfbse.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gt2hkymksnj.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gt2ulbvphmr.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gt2iaxxiffa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gt2yygikxka.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gt2pxbpgurh.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gt2njvxowho.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rcutmsbk.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gt2pcrpvtul.html

[S31] C++：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2znebbrcu.html

#include <iostream>
来源：http://dali.yongpay.top/Article/details/gt2agdbavlp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258888.top/Article/details/gt2vwajwbgx.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gt2olzgrher.html

std::string s = "hi";  s += "!";
来源：http://dali.gotoacloud.top/Article/details/gt2rdapljbi.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gt2jobwxtiq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gskwfyki.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujjjoist.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxqjmjso.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gt2fgnxhtvn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2zyxcghwj.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gt2dfvulmei.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2ehxsatqv.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gt2gztokvoy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pycfn.com/Article/details/gt2qhyvtigg.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gt2dnqpritg.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gt2uhhjugku.html


<!-- 参考信息 -->