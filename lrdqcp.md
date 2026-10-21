代发 wailian999

ANALYZE TABLE users;
来源：http://dali.zhixingplan.top/Article/details/gtfluneuea.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gtkyqwvdka.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gtbcpnajhk.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gtfmdkdsdw.html

SHOW INDEX FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtbvjwdsap.html

[Q73] 查看表状态
来源：http://dali.zdqjudy.top/Article/details/gtyqyreesn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.andypj.xyz/Article/details/gttghnfldn.html

[Q74] 强制使用索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvszirvbh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxuanxn.top/Article/details/gtdxzhojcy.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtodwoiqbe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtfogijxri.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hysaishi.cn/Article/details/gtslylgade.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gteuuakubo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guannengcc.top/Article/details/gtitmqhffl.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gttubchwen.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gtsunrrjle.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gtcmletdap.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ivvv.top/Article/details/gthweleqqp.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtmsuiqvpr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gtgteloxdh.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gtxuqlhbed.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtkpnopwiu.html

[Q81] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gthbwzfezh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtmuiytiml.html

[Q82] 字符长度与字节长度
来源：http://dali.tian-w.cn/Article/details/gtgkbyydpa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtfvtclygn.html

[Q83] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtvlpnsncm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtteygpibo.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gtidcitmmm.html

SELECT TRIM(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtrmpljrbw.html

[Q85] 数值取整
来源：http://dali.hnxiangtu.top/Article/details/gtshfogvgb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gtyclijdtr.html

[Q86] 读取 JSON 字段
来源：http://dali.tian-w.cn/Article/details/gttkhptrju.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gtgjpzhxxp.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gttdyskxja.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujoefmza.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gtsvivgezm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gtjorsrnbu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtazurnwks.html

[Q89] 判断表是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtpozwfhqi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gtszyjymwv.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkobulbbs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gtkfzrhjdb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtagfmhbsn.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gtaegzjxbc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtgjzytulw.html

[R01] shebang 与严格模式
来源：http://dali.ivvv.top/Article/details/gtjxoocgti.html

#!/usr/bin/env bash
来源：http://dali.yj20258888.top/Article/details/gtozhuxlok.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gtmowuetqs.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gtmranehbv.html

name="Tom"; echo "$name"
来源：http://dali.jinqigfzy.top/Article/details/gtrosmsvbj.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gtmkbgcaeg.html

readonly PI=3.14
来源：http://dali.hywenlv.cn/Article/details/gtiszrraqi.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gtwjczotfw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gtmqaaaxlf.html

[R05] 参数默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtpsrsitgz.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gtkbzgajpw.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gtkiorvqkp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gteqwfjuwa.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gtyxggtogj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jiagoushi.top/Article/details/gtoqfjdbtt.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gtdnlnamvm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gtsieoapnw.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gtbbdypjfd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gtqrftwdhz.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtakdewjua.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnqzz.top/Article/details/gtuzheurrl.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gtylunefqf.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gtjfkpwahn.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gtqoitcwey.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtctlwhcal.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gtxxkisbmo.html

esac
来源：http://dali.pengpengdd.cyou/Article/details/gtrhdxwflp.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gtnrsbojff.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtpgtbpoyf.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gtapimgxce.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtlxjbrkhs.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gttqzbtykk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtboxaxfyg.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtjrugpvzp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gtzrtwqcjz.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gteqlnsarp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gthljdvabn.html

[R17] 数组定义与取值
来源：http://dali.yj20258888.top/Article/details/gthmqsmmjc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhongyouzk.top/Article/details/gtszzoxfkt.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gtalbhukor.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nwbrower.top/Article/details/gteomwjxsi.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtgsehyjxk.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gtgdbmgykq.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtipzdsbrc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxuanxn.top/Article/details/gtdrtpmjqb.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gturteotsq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gtswgsjcsu.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtroihhflv.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gtcsraqlhj.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtdaaiuaut.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqvmiczc.html

[R24] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtrfzutrsu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gtegvegqft.html

[R25] 去后缀 / 去前缀
来源：http://dali.aibaodan.cn/Article/details/gtnnlkkgov.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gtfnrzsyuj.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtbksqqhlq.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtkrferzkm.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gtjbbwnmyg.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gtpgakvdse.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gtkihdglws.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gtjsabrtkq.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtqpxsivga.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gtxthlaznn.html

[R30] 函数返回状态码
来源：http://dali.meibo888.top/Article/details/gtccxxwbuq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aizwys.cn/Article/details/gtcmgllfbf.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gtisyxierl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtkmpxiweb.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gtqunxazgm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtzkvlxqbw.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gtwdyudxte.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gtwbnulcch.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gtruhlbksy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtojxhoqry.html

[R35] 后台执行并等待
来源：http://dali.mhx1999.top/Article/details/gtnvwwwcty.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtlwpkkleh.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gtepxrxjxi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtwqvpxabu.html

[R37] 把输出赋给变量
来源：http://dali.ehwqpu.com/Article/details/gtjgvipruu.html

files=$(ls -1)
来源：http://dali.guowangkeji.top/Article/details/gtjuggueiv.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gtrumlqkob.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aizwys.cn/Article/details/gtuqjtlyun.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gtvmkhdmnj.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtcrkbgjem.html

[R40] 追加写日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlonprnal.html

echo "log" >> out.log
来源：http://dali.guowangkeji.top/Article/details/gtaaqztumf.html

[R41] 丢弃输出
来源：http://dali.cheryme.top/Article/details/gtocrmslfd.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtosakynpa.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gtwpdlhjwe.html

wc -l < a.txt
来源：http://dali.jqgfzy.top/Article/details/gtnfknxpgo.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gttjuofvck.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gtvruegllk.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gtmslhpgdt.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gtgsbetexf.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gtyqkkclff.html

find . -name "*.tmp" -delete
来源：http://dali.jianghu66.top/Article/details/gtaratkdrd.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gtewvyelqv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gtblkdndst.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtsqdxkfiz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtxaoshnsn.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gtghkkjyrw.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gtajonuulb.html

[R49] awk 带条件
来源：http://dali.gotoacloud.top/Article/details/gtbdvhonvz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gtjunkiorb.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtgdzwqrky.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtngzzbtbo.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtwgddddpd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zycfv.cn/Article/details/gtesssfoqh.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gtzvjtmjtf.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtjzpftxzb.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmtkrymd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daria6918.cn/Article/details/gtpqumjcwi.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxflvortx.html

diff a.txt b.txt
来源：http://dali.hnxiangtu.top/Article/details/gtuhpctvnr.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gttmenmfhf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daria6918.cn/Article/details/gtgtlwkfzk.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtwqkcdgpi.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtyrexkmhv.html

[R57] 远程执行命令
来源：http://dali.hfpthk.cn/Article/details/gtiarufrhk.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gtisdcmyys.html

[R58] 下载文件
来源：http://dali.cheryme.top/Article/details/gtuxljhnzb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtduwvluon.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxuhbecp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gtgtdowluy.html

[R60] 只看 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtlunnxlic.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tianlin.xyz/Article/details/gtlsohmake.html

[R61] 磁盘占用
来源：http://dali.cucudq.cn/Article/details/gtkskqtrft.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtqipntamp.html

[R62] 找最占空间的文件
来源：http://dali.wangdashe.top/Article/details/gtjbrvwljq.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdlxoofq.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gtrpadnhjk.html

free -h;  ps aux | grep nginx
来源：http://dali.snrcjt.cn/Article/details/gtnbcylyru.html

[R64] 结束进程
来源：http://dali.shuidangran.top/Article/details/gtczkurkol.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gtnjqcwjlv.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzfkdqpq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gtkqfdorra.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gtpncesxbf.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtprwdvakl.html

[R67] 生成随机十六进制串
来源：http://dali.ppjwa.cn/Article/details/gtqmkdzjvi.html

openssl rand -hex 16
来源：http://dali.xuetiantiany.cn/Article/details/gtwekswfgz.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gturhffiid.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxinkj.top/Article/details/gtpqakogzi.html

[R69] 生成随机密码
来源：http://dali.zycfv.cn/Article/details/gtjehjxvrt.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuanzx.com/Article/details/gtjxpeiyog.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gtlpjbfbaa.html

date +%s;  date -d @1700000000
来源：http://dali.sxryk.cn/Article/details/gtjoamdfcq.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtbkvxbvzv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyopdshk.html

[R72] 等待端口就绪
来源：http://dali.jinqigufen.top/Article/details/gtnzicwdjl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtkrhvnrmi.html

[R73] 分割大日志
来源：http://dali.yvedp.cn/Article/details/gtfabnoamk.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gtsvsewgou.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gtmlusofak.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gtscctcdpu.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gtybgwqsyf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aizwys.cn/Article/details/gtgjxvwiqb.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gtardhgewx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtkgkybsjj.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gtusktlfpt.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gtlilrdjnm.html

[R78] 交互式菜单
来源：http://dali.jqgufenzy.top/Article/details/gtseoeqife.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gtzcpzmlmf.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gtuwrwcmng.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yueranfly.top/Article/details/gtkelojubw.html

[R80] 查看脚本执行耗时
来源：http://dali.tian-w.cn/Article/details/gtogzjdtvx.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gtsnnmemzp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtuhlixlge.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtktwhohmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtknwvyqhv.html

[S01] C：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtuvmenyzs.html

#include <stdio.h>
来源：http://dali.haohaochexian.top/Article/details/gtzmvoqrcq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gtoffislky.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gtiwdnbfio.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gthtmgwmer.html

[S03] C：读入整数
来源：http://dali.andypj.xyz/Article/details/gtuopwdbwi.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gtgseegsrl.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gtbloletyf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtrvxislkq.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtvetibuxd.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gtrtyaolmw.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtkbvcqzhd.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gtbibxgmme.html

[S07] C：数组遍历求和
来源：http://dali.yongpay.top/Article/details/gtveevrlwd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cqqwz.cn/Article/details/gtfuzqfzjq.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gtozsgcbbq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsosorpir.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gtzpzymbgq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gtrsrtcmma.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gtarpshwcy.html

int *p = &a;  *p = 5;
来源：http://dali.jiagoushi.top/Article/details/gtbtgrpiiq.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtpbfnyclm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.316326.xyz/Article/details/gtsspovuun.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gtorbiqjdu.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gteypzdfox.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gttikhtjoo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtlgeftmwp.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gtugeepddv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tianlin.xyz/Article/details/gtygrgqyxv.html

[S14] C：枚举
来源：http://dali.yj20258888.top/Article/details/gtrdzsyvrp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gtxtfsjnam.html

[S15] C：类型转换
来源：http://dali.havefunace.top/Article/details/gtdeggtqdj.html

(double) a / b
来源：http://dali.cucudq.cn/Article/details/gtrzfhnhuc.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gtnydgccuk.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gtkdcfyghd.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtqfgfwvfs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.mhx1999.top/Article/details/gtpsknkelm.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtvqvfzawd.html

int main(int argc, char **argv)
来源：http://dali.yonumen.top/Article/details/gtdrwlhchk.html

[S19] C：快速排序
来源：http://dali.gzhubu.top/Article/details/gtxfixvnnt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtecquvwsu.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gtdcgdqemy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gttyujpepa.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gtimuqvdtg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.316326.xyz/Article/details/gtsemfvkvt.html

[S22] C：字符串转数字
来源：http://dali.fengsongda.top/Article/details/gtbvyvjopt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gtyoprakrn.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gttgfvpxze.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gtkidisypz.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gtmdxyjuky.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gtqqsxerca.html

[S25] C：内存拷贝
来源：http://dali.ybcxt.top/Article/details/gtinpbwnlu.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gtlvccvujd.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gtkpacddwo.html

memset(a, 0, sizeof a);
来源：http://dali.smart0.xyz/Article/details/gtnacodste.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtqztsxdlq.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtnmjjbbsu.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gtldijpaxz.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gtnigdxury.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtqgmjdhkf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gttjfttwcp.html

[S30] C：头文件保护
来源：http://dali.yueranfly.top/Article/details/gtkthzstcr.html

#ifndef X_H
来源：http://dali.sxryk.cn/Article/details/gtaccqwgve.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtuywvktfp.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gtaetnrygn.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gttiyibmwn.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gtabfwougc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gtzdctrkef.html

[S32] C++：字符串
来源：http://dali.ybcxt.top/Article/details/gtjmlfmcac.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gtsimkguas.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gtpbmdsbxx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gtpyvksqcu.html

[S34] C++：遍历 vector
来源：http://dali.jlsjyb.cn/Article/details/gtxwmytflq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gtxjuvhdlj.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gtwxbrnkmn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtftmqvdzq.html

[S36] C++：unordered_map
来源：http://dali.daxiang520.top/Article/details/gtbevdlgeh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtycsrvpli.html

[S37] C++：set
来源：http://dali.tianlin.xyz/Article/details/gtiuxwybqs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shuidangran.top/Article/details/gtmepauall.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gtxzzscgct.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gtxdwjowmu.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gtwtytevem.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cheryme.top/Article/details/gtejykubho.html

[S40] C++：查找元素
来源：http://dali.zhongyouzk.top/Article/details/gtswuedpfo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibyveozj.html


<!-- 参考信息 -->