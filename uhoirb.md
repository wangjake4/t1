代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gtrkpdgozz.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gthkzgtgdr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gtevinfros.html

[Q70] 更新统计信息
来源：http://dali.hnqzz.top/Article/details/gtctbnttzb.html

ANALYZE TABLE users;
来源：http://dali.chenlongwang.top/Article/details/gtocxjmfys.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gtanjplxvs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hfpthk.cn/Article/details/gtvzwllvfa.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gtoidwhsry.html

SHOW INDEX FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtwgskvsiu.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gteyutshnp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gtfxsxnyei.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtqblobmyz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gteahizoba.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtbmjidrlw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtwyprwgvs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sysykeji.top/Article/details/gtxkwxtgqw.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gtzbvncogr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.quarkkingdee.top/Article/details/gtymgekvxq.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gthyyhlddl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gaohongyu789.top/Article/details/gtzogfkwzb.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gtukrgznhc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gtxsgehlgv.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtngpjqylh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gthtcnhxdd.html

[Q80] 字符串截取
来源：http://dali.ppjwa.cn/Article/details/gtqskbeamd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtnmaiwnlk.html

[Q81] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtrameokzj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtdvulpjjs.html

[Q82] 字符长度与字节长度
来源：http://dali.aizwys.cn/Article/details/gttnvdnupa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtmzpqjsxh.html

[Q83] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtnrdzvagq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gthebksrod.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gtsabajolq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtzxqeffgw.html

[Q85] 数值取整
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzwfjyui.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gtudhdgoqr.html

[Q86] 读取 JSON 字段
来源：http://dali.shangyingyoupin.top/Article/details/gtmzzvblol.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gtvcvgqsub.html

[Q87] JSON 字段做条件
来源：http://dali.guowangkeji.top/Article/details/gtcccecfyt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sysykeji.top/Article/details/gtzgtyqlhx.html

[Q88] 行转列（条件聚合）
来源：http://dali.hywenlv.cn/Article/details/gtgccgpare.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zdqjudy.top/Article/details/gtejylqgmh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fzhhl.top/Article/details/gtncdgmhag.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gtnuxdesmz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtjubngalw.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gtszcghben.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtanyksqvt.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtomjveozg.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gttlqoujzm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtkvnilfvg.html

[R01] shebang 与严格模式
来源：http://dali.feifeiyinyue.top/Article/details/gtmdgixisw.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gtjbjovoik.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gturykqqry.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gtgexaaast.html

name="Tom"; echo "$name"
来源：http://dali.aizwys.cn/Article/details/gtvrlczxpc.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gtdgqetbgg.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gtsntfdowe.html

[R04] 位置参数
来源：http://dali.xuanzx.com/Article/details/gtxrwzmdig.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.svipenyu.cn/Article/details/gtgsdfrzqs.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gtmvokgqrd.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gttbbxsjyd.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gtsyzzemox.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtonrmodso.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gtxmwnqral.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gtmizzwlmb.html

[R08] 数值比较
来源：http://dali.yueranfly.top/Article/details/gtkwzwcxyz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangdashe.top/Article/details/gtipqyprex.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtdlapwkij.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtcwmlyjxp.html

[R10] 正则匹配
来源：http://dali.nanxuanxn.top/Article/details/gtxlrwqcbm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sxryk.cn/Article/details/gtzalolcvf.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gtkdttywgr.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gtnattafua.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gtsurgnijq.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtptlwxsha.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gtcvytnklc.html

esac
来源：http://dali.aibaodan.cn/Article/details/gtlmrcwolk.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gtjmdixmmo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yvedp.cn/Article/details/gtshpwevba.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtzlwqjmez.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtjdcribgl.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gtvlfkfmfu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtntsrhmed.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtsqefctwq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangdashe.top/Article/details/gtuijistbb.html

[R16] until 等待条件
来源：http://dali.dashuyun.cn/Article/details/gtoxskiauh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtrbanpjgn.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gtoicrelme.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jlsjyb.cn/Article/details/gtdqshwvbp.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gtftuuyzgh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yongpay.top/Article/details/gtfiauqavs.html

[R19] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtygpxnrqo.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gtctpjcykg.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gtavyalrgn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gtrwqopbkz.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gtlvdpucay.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gtgsdwwvlx.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtvyrpnthp.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gtdhdrtgbv.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtcdarwqaj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnxiangtu.top/Article/details/gtmotyzkqp.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gteukpvxmy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yongpay.top/Article/details/gtcmwnofte.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gtigqcrqki.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gtupbfnroh.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gtqelvdkrn.html

now=$(date +%F); echo "$now"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxxudeqq.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gtijxdqmql.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtodjxyqji.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gtgcglhgcz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmieroafb.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtmtugtjvr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gtbcporfvq.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtelsfcelm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jyoumei.cn/Article/details/gthtjlwbjw.html

[R31] 局部变量
来源：http://dali.dianchejie.cn/Article/details/gtstudusij.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gtrzpmsoem.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gtdvpxqqcm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtajrulrle.html

[R33] 捕获错误并提示行号
来源：http://dali.sysykeji.top/Article/details/gtuppttxqg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jianghu66.top/Article/details/gtqdvboubr.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gtgrpvenvi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gthwxvfcll.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gtfuiwwrjl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cdnleiting.top/Article/details/gtidxcysum.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gtxhuvmccx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gtmozndfdo.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtnxinfmqe.html

files=$(ls -1)
来源：http://dali.chenzaomai.com/Article/details/gtebyunlgd.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gtekraxcow.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gthoijihml.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrexwziox.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtmauszglo.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gtvtmnmepn.html

echo "log" >> out.log
来源：http://dali.sysykeji.top/Article/details/gtfqxxaenx.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gtrgsgyvqi.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gtcogaxffs.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gtzrygqkda.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gtchdkzlix.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gtuhrtmyan.html

find . -name "*.log" -type f
来源：http://dali.yuxming.cn/Article/details/gtmldqngrj.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gtkkvcyvnn.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gtjcjctkwc.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gtjloqeyaz.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gtkcxtvhda.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gtmpyjybyt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cheryme.top/Article/details/gtlutjblcf.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gtonouzrpp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gtpkfdslzt.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gtyakbzuyg.html

awk '{print $1, $3}' a.txt
来源：http://dali.316326.xyz/Article/details/gtemcftxow.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gtoawkmmie.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gtrrkxyput.html

[R50] awk 求和
来源：http://dali.sxryk.cn/Article/details/gtirwneiet.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj202588.top/Article/details/gtjjwtqbxi.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gttllqinah.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gtkwtrsafh.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtutoubxza.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gtecsrjlno.html

[R53] 查看文件头与实时尾
来源：http://dali.quarkkingdee.top/Article/details/gtfobncjpx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gtqmckiflr.html

[R54] 比较两个文件
来源：http://dali.smart0.xyz/Article/details/gtgrlgzphs.html

diff a.txt b.txt
来源：http://dali.chenlongwang.top/Article/details/gtebrdtyvj.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtkdpendgx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258.top/Article/details/gtrqbaqlyt.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gtwbdsucui.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gtuncvlzoh.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gtzkbkkcrf.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gtignojesh.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gtvyrladmh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pengpengdd.cyou/Article/details/gtsmhmogyi.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtbqcohbwh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtxyvtdcal.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtqfljtxib.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gtkafcvznk.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gtcofizgcl.html

df -h;  du -sh *
来源：http://dali.sysykeji.top/Article/details/gtjpkvjxzb.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gtsvdrbkpo.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gtklffymcs.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtqsdubixj.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtrjjnkloz.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtnftthrvi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gthstaodab.html

[R65] 查看端口占用
来源：http://dali.cdnleiting.top/Article/details/gtgfhknwyb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.redwolf501.top/Article/details/gtwxtzuflp.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gtmywzzltb.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gtiyudljdq.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtukcbsbng.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtggzeldlj.html

[R68] 计算文件校验值
来源：http://dali.cdnleiting.top/Article/details/gtzvjqjzyb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhengqikj.top/Article/details/gtvyhjsgfn.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gtslnyscqk.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gtidfwccfh.html

[R70] 时间戳与互转
来源：http://dali.nwbrower.top/Article/details/gtlvoazelt.html

date +%s;  date -d @1700000000
来源：http://dali.ybcxt.top/Article/details/gtzdbntngf.html

[R71] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gthhwowasc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfarvsvyl.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gtznndotze.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtkbvwowqh.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gtvhlwkkhj.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gtkpuwqsyu.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gtpjspfsus.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtsoddxbbg.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gtxboqaxjx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gtvtpadiwt.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtpdcjpsax.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtvsofnqto.html

[R77] 读取用户输入
来源：http://dali.hysaishi.cn/Article/details/gtvmkawgtq.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gttiniyrrw.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gtmugmkrso.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gtemetijti.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gthkncpzhy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtorylytag.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gthtlxvryv.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gtcmxalizg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtirzaenpd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gtsklffgur.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gthlxdsmty.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gtjlbqqliu.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtxkabmpga.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gtasyksonq.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtsfyilmhc.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gtamjwrexc.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gtnlhdhemh.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gtdinuaiwd.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gtzbwrdrkx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cucudq.cn/Article/details/gtjsmyrmtp.html

[S05] C：字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtqdbefuhy.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gtmjpwsyej.html

[S06] C：字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtivvbxlmi.html

strcmp(a, b) == 0
来源：http://dali.quarkkingdee.top/Article/details/gtglmuvyew.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gtziasnecb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gttbnhbuwa.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gtecgpeccr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gtidmzhkeo.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gtuwcuampb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmxfewgf.html

[S10] C：指针与解引用
来源：http://dali.ivvv.top/Article/details/gtgmfowajs.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gttzaezncq.html

[S11] C：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtiirbavqf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gtgoovbrrn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gtkljzfotk.html

fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtdjcakvwz.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gtfbaupbtx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtittdrifq.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gtaxuomsjy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gtolvpubxp.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbtsohdf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gtzjmouvgr.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gttwphxhqq.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gtuppasmef.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gtuugnbwlj.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gtaylrzzbi.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtvxvxwuqa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtzyuwukiy.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gtmjwpxxsq.html

int main(int argc, char **argv)
来源：http://dali.jqgufenzy.top/Article/details/gtqrjgzivq.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtjoxuusak.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtulpqkkif.html

[S20] C：二分查找
来源：http://dali.ivvv.top/Article/details/gthtsqthjc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gthajjmweh.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gtotexsnaf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gtfdxtelhy.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtgowaglme.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pengpengdd.cyou/Article/details/gtzemlgkbw.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gtevewhlbk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gtnfdcsnfe.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gtvegmtosv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gtyyjesokd.html

[S25] C：内存拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebagmxse.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gthamnmlrb.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gtrzpldqke.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gtjxcvkewg.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gthrvnkkdj.html

const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtblmjwbry.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gtniwqdufb.html

static int counter = 0;
来源：http://dali.bjfxy.top/Article/details/gtnpjoezsn.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gtukcezwvb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gtwqeemiiq.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbdnirpq.html

#ifndef X_H
来源：http://dali.cashguo.top/Article/details/gtvnadteiq.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gtyjczlgxe.html

#endif
来源：http://dali.chenjidiqi.icu/Article/details/gtmxlelwbd.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtejttmypx.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gtubjvjeze.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gtwfkcxcwp.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gttmproeje.html

std::string s = "hi";  s += "!";
来源：http://dali.ppjwa.cn/Article/details/gtinejoebh.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gtuctliagy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtbprgdzmc.html

[S34] C++：遍历 vector
来源：http://dali.yj20258888.top/Article/details/gthuebkhxn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvnngnyrr.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gtsttbhlvw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtvbkynvzp.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqjafrjc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtemsqllqs.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gtbyhukcuz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gtxiiufrta.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gtdoboyomo.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtiwbcscxr.html


<!-- 参考信息 -->