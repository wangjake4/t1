代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gtpztxhwmz.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtbicbylzv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtcdurjbjf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gtsqhvufwl.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gtjeryrjav.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aibaodan.cn/Article/details/gtmmmegbpr.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gtsexkrufl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cdnleiting.top/Article/details/gtzlqrrlrk.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gtxitrgevc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.quarkkingdee.top/Article/details/gtaseuzxkw.html

[Q79] 字符串拼接
来源：http://dali.yj202588.top/Article/details/gtdrnvokkw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gtpyjjykwz.html

[Q80] 字符串截取
来源：http://dali.shuidangran.top/Article/details/gtqldlpcii.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gthchdrslg.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinmgphkx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gtlvmnvels.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gtjrwerbwo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtjjmrozdz.html

[Q83] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtpmnfinbw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gthonortgm.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gtoperdayh.html

SELECT TRIM(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjusieclf.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gtatuevyeo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gtnypmvlrs.html

[Q86] 读取 JSON 字段
来源：http://dali.wangshuangyany.cn/Article/details/gtewcwfekf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xylfe.cn/Article/details/gtouufexmz.html

[Q87] JSON 字段做条件
来源：http://dali.ivvv.top/Article/details/gtnjrkmyxw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jlsjyb.cn/Article/details/gtskihkkcq.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gtbkezhynx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gtgdhkxygr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gticcfmlrt.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtfmvhswyg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.vqdsnc.cn/Article/details/gtxaxltxvs.html

[Q90] 生成序号列
来源：http://dali.ivvv.top/Article/details/gtlejbgvvz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cqqwz.cn/Article/details/gthcpcwxfe.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgndpcevs.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtieucvoho.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtzwhnblrj.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gtjqnjsyqn.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gtioobrtfn.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gtgxxrxeyr.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gtzsvjoyrx.html

name="Tom"; echo "$name"
来源：http://dali.vqdsnc.cn/Article/details/gtpojlutje.html

[R03] 只读变量
来源：http://dali.ehwqpu.com/Article/details/gtsomtvjzk.html

readonly PI=3.14
来源：http://dali.shzxlz.cn/Article/details/gtbvvlxjsi.html

[R04] 位置参数
来源：http://dali.svipenyu.cn/Article/details/gtanfyqsay.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gtqzcizmxt.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gtyepjnndp.html

name="${1:-default}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtisocuybk.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gthaerzbbr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtjmlsgunr.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gtnedokurn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuanzhike.top/Article/details/gtqpuvrqlj.html

[R08] 数值比较
来源：http://dali.fzhhl.top/Article/details/gtmidvrrtb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiecisrvz.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtagueqhtp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gtyfeanzru.html

[R10] 正则匹配
来源：http://dali.zhoulong.xyz/Article/details/gtyaygtszz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shuidangran.top/Article/details/gtkmelvhvv.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gthwcgcksd.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gtsjteqcco.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkjctaov.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gtltxxwctg.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtoohnrsla.html

esac
来源：http://dali.jqgufenzy.top/Article/details/gtrukjuyhu.html

[R12] for 遍历文件
来源：http://dali.316326.xyz/Article/details/gtalzfmxns.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtyruauiqr.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gtfbtebviy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtncmcjhjo.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gtsfmpcolq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtragrfujh.html

[R15] while 逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtxphcikvl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gttardxjfi.html

[R16] until 等待条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsvgrecn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gthvgvbuwv.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gtwwaxnniw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.vqdsnc.cn/Article/details/gttmrspedf.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtzolpmfvj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.c1oappe.top/Article/details/gthrqvjuwr.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtjoplxejd.html

echo "${#arr[@]}"
来源：http://dali.zhixingplan.top/Article/details/gtqzhfkfwa.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gtozsqcexz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gtwuvsjkdt.html

[R21] 字符串长度
来源：http://dali.smart0.xyz/Article/details/gtxnwyyqmn.html

echo "${#s}"
来源：http://dali.cqqwz.cn/Article/details/gtxisnwsit.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtmgrudxiv.html

echo "${s:0:5}"
来源：http://dali.aizwys.cn/Article/details/gtctfhmklb.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtnhpefhbe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aibaodan.cn/Article/details/gtqvgquull.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtuiwzknij.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gtagonfyde.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gtfbhamzxa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gtmtmtgrzg.html

[R26] 命令替换
来源：http://dali.gzhubu.top/Article/details/gtnojzrnms.html

now=$(date +%F); echo "$now"
来源：http://dali.haohaochexian.top/Article/details/gtfkqqowrb.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gtvdfyybqt.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gtuwuhimyw.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gtnrjtcnxc.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gtadezavaz.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtunjkepyr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigufen.top/Article/details/gtqtgfamcg.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvotuzil.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gtvzoxbink.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gtgsmpiptb.html

f() { local x=1; echo "$x"; }
来源：http://dali.yanxiufei.cn/Article/details/gtdcoabpkl.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gtpzgavlnm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gtgpszrvpm.html

[R33] 捕获错误并提示行号
来源：http://dali.mhx1999.top/Article/details/gtugamzlvk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gtvoyjnhdp.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gtxlwgwnsu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtqkodqmkj.html

[R35] 后台执行并等待
来源：http://dali.yanxiufei.cn/Article/details/gtyktcrrhe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.c1oappe.top/Article/details/gtdovmkoki.html

[R36] 并发执行多个任务
来源：http://dali.sweek.top/Article/details/gtvimchocm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gtzovnzkim.html

[R37] 把输出赋给变量
来源：http://dali.hfpthk.cn/Article/details/gtjwbbduic.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtxmxxwbws.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtoecbzvbv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuanzx.com/Article/details/gtxtsgyewa.html

[R39] 重定向标准输出与错误
来源：http://dali.hnqzz.top/Article/details/gtnxbtfcoh.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtkiqficrs.html

[R40] 追加写日志
来源：http://dali.cucudq.cn/Article/details/gtmfvosvsk.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gtjggfakdy.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gttbwdzpdp.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtpbgzzbgq.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gtmgzxighx.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtmqgqonsy.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gtsjxjsvdy.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gtaoulbdnl.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gtijlxychx.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gtkgcsluxe.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyvawoyu.html

find . -name "*.tmp" -delete
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtywfcvr.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gtkmauhlkb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gtgbwjepos.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gtdsrbotas.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtffspqsym.html

[R48] awk 取指定列
来源：http://dali.gogol.net.cn/Article/details/gteawtvcba.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtazizgzit.html

[R49] awk 带条件
来源：http://dali.cheryme.top/Article/details/gtyoufhrtq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gtqffxzroe.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gtdhmbqslj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gthlgfowko.html

[R51] 排序去重取前几
来源：http://dali.yvedp.cn/Article/details/gtbcuedbmt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yangfankeji.com/Article/details/gthlweurcy.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gtgzkfrgma.html

wc -l a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtavunzmlk.html

[R53] 查看文件头与实时尾
来源：http://dali.guannengcc.top/Article/details/gtfbrkhirm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gtvfrmchla.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gtjlrfwxjy.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gteivjghhm.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweqghztv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ybcxt.top/Article/details/gtmwqxnvde.html

[R56] 远程拷贝
来源：http://dali.gotoacloud.top/Article/details/gtypjaocwf.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbelmfjr.html

[R57] 远程执行命令
来源：http://dali.yanxiufei.cn/Article/details/gtlvobfyem.html

ssh user@host 'uptime'
来源：http://dali.yueranfly.top/Article/details/gtnglkfaaz.html

[R58] 下载文件
来源：http://dali.bjfxy.top/Article/details/gtjulxqhnf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gtgogrbkwn.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtsekmtvsz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gtvbvtvkrn.html

[R60] 只看 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtmxysxdpk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtpgrxzrwm.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gtwycehzql.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gtcattntog.html

[R62] 找最占空间的文件
来源：http://dali.xziqi.cn/Article/details/gtstlysssx.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gtjvykaoey.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gttiqlxmvk.html

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gthmeoyesa.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gtcwpixwpr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gtgtwlriiu.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuiloldhr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gtjkumvlvg.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gtfjhukgjd.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gtnecfbbaj.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqazkyxq.html

openssl rand -hex 16
来源：http://dali.yanxiufei.cn/Article/details/gtylucyimc.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gttagswbnt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuanzhike.top/Article/details/gtpagwqswb.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gtjabvksir.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtrkdsjbfu.html

[R70] 时间戳与互转
来源：http://dali.hywenlv.cn/Article/details/gtabjtabrq.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gtahlfisgc.html

[R71] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtbhryhviv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gtcfokzjrk.html

[R72] 等待端口就绪
来源：http://dali.jinqigufen.top/Article/details/gtdysghedo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtksxodzwq.html

[R73] 分割大日志
来源：http://dali.tianlin.xyz/Article/details/gtcqmyturu.html

split -l 1000 big.log part_
来源：http://dali.zhiwuduotai.top/Article/details/gtebruwfvp.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gtuacryrjb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gthmjooztm.html

[R75] 导出环境变量
来源：http://dali.meibo888.top/Article/details/gtlnrdyxgk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gtckkvyulw.html

[R76] 使用临时文件
来源：http://dali.nanxuanxn.top/Article/details/gtxhjeydiy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtmeebrzdp.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtvvedlthl.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gtpjttcxrl.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gtfplkguiw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gtrnemcewc.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gteenbbcsf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gtbvpzkxqv.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gtgiadiaun.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gtmsqlipnx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtigbxlmyd.html

S. C / C++ 专题
来源：http://dali.hfpthk.cn/Article/details/gtyhvmxori.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdbdrufuz.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtpqspqnpi.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gtgtitiaym.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gtpfvbehbr.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtfcmoztyz.html

int a = 10; printf("%d\n", a);
来源：http://dali.dashuyun.cn/Article/details/gtiqvimkst.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gtrooozvlh.html

int x; scanf("%d", &x);
来源：http://dali.guannengcc.top/Article/details/gtzwvjaifd.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gtamvvyocp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtxknjostp.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtgjskuutz.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gtywebylno.html

[S06] C：字符串比较
来源：http://dali.jyoumei.cn/Article/details/gtmhapxcta.html

strcmp(a, b) == 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgneuzstu.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gtjilkrjqb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gttayarjyi.html

[S08] C：动态内存分配与释放
来源：http://dali.zycfv.cn/Article/details/gtvfledhgh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gtflbylcvh.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gtvdzitloj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gtxartoazx.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gttvjiasld.html

int *p = &a;  *p = 5;
来源：http://dali.jyoumei.cn/Article/details/gtrvnumxsx.html

[S11] C：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtvlwerytm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gtxqljwoza.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gtihqgyuiv.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtaamwmqeq.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtvcshxpdq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gttryqkaim.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gttpdmhqja.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gtmggrhsve.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gtitgmmabg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gtysfnqbby.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gtcthxsxqg.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gtpxxkjqha.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gtqajheuok.html

x |= (1 << 3);
来源：http://dali.jqgfzy.top/Article/details/gtchjpxxgq.html

[S17] C：安全拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtyxylvlay.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guannengcc.top/Article/details/gtlisjmtpf.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtmgccrdee.html

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gtfzhuxbyt.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gtofuwxrfc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtraxvdcya.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gtraaameub.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtgshcmvqs.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gtoiniqxae.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gtspqmmcmh.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gthgtrkprm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gtjocqefqk.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtctalkgwt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gthzhcaqgi.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gtmhxxsvav.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuxming.cn/Article/details/gtgotlnwzr.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gtpympkyqt.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gtaemnatvi.html

[S26] C：内存清零
来源：http://dali.yj20258.top/Article/details/gtjqizlley.html

memset(a, 0, sizeof a);
来源：http://dali.havefunace.top/Article/details/gttqsushfz.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gtjxaaglmg.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtqpdougxo.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gtdoglkjro.html

static int counter = 0;
来源：http://dali.shuidangran.top/Article/details/gtktixjahh.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gtmmpuvbdq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gtvqzjnxzw.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gtgwgtupzt.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gtranygmlm.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gtmiapqtke.html

#endif
来源：http://dali.redwolf501.top/Article/details/gtlssbscnr.html

[S31] C++：Hello World
来源：http://dali.smart0.xyz/Article/details/gtsmxdptgz.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gtyfwjbpin.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtcpeypnoi.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gtznehpjgt.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gtslrodthh.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gtmuegibrp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gtzsqwkrdu.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gtvmknrtce.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gtkezqkjrx.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gtbeicjztw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtsfdbxgcl.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gtraamkuzr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtrnekmwfb.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gtwvtxykxj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gtltypgror.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gtkthskowz.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtionwsobz.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gtkgjhskjr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gtbetyzjwm.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gtedrzzwrk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gtgqqlnblr.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gtpsiruosu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gtylgviwzy.html

[S42] C++：继承与虚函数
来源：http://dali.havefunace.top/Article/details/gtzsyfykdf.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigfzy.top/Article/details/gtwojurbzi.html

[S43] C++：智能指针
来源：http://dali.zycfv.cn/Article/details/gtefywwowr.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gtzvbuoxaq.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gtdhzrwcwf.html

void inc(int &x) { ++x; }
来源：http://dali.yuxming.cn/Article/details/gtojtjmwtn.html


<!-- 参考信息 -->