代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fzhhl.top/Article/details/gtwjqcpccb.html

[Q75] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtidnpfxdw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtwvkuyaco.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gtpqonzvpo.html

[Q76] 按天统计
来源：http://dali.wangdashe.top/Article/details/gtteptxdqn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gtmerdzkzw.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gtrpeamzxm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gtkdxbegsd.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gtyjandpoo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhongyouzk.top/Article/details/gtrpchyfkp.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gtbovggrop.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj202588.top/Article/details/gtitfzenkc.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gtwadinbqv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtcyxziekq.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtxafovvog.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtyvsbmvcc.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gtcqacuhrj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtnybiiukl.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtwcthawlm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtuttkiipz.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtqkzlstcr.html

SELECT TRIM(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtxqjtqgrr.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gttdybxfgt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gttymfrcqg.html

[Q86] 读取 JSON 字段
来源：http://dali.xylfe.cn/Article/details/gtxqlalxry.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgufenzy.top/Article/details/gtdfdlhxar.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gtreyawarz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gtmnnpflvh.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gtehuxyyom.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shuidangran.top/Article/details/gtirjvxgpv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yvedp.cn/Article/details/gtdrdoidcc.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gtndpexqoo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gtlejjfwan.html

[Q90] 生成序号列
来源：http://dali.snrcjt.cn/Article/details/gtjeowochv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gtdoejfipt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnxegksgw.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gtoikijmvy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwerttkgu.html

[R01] shebang 与严格模式
来源：http://dali.quarkkingdee.top/Article/details/gtcvlnhdhe.html

#!/usr/bin/env bash
来源：http://dali.xziqi.cn/Article/details/gtjgctuytz.html

set -euo pipefail
来源：http://dali.shuidangran.top/Article/details/gtqrscoqvj.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gtuznmlxse.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteixvhlke.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtuywxndnp.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtfnbmgivk.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gtuznkffvv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shzxlz.cn/Article/details/gtlvatqehk.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtbalfklpd.html

name="${1:-default}"
来源：http://dali.jqgfzy.top/Article/details/gtzhbycyuk.html

[R06] 判断命令是否存在
来源：http://dali.smart0.xyz/Article/details/gtghixwzmx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtmuqsmgoe.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gtgfgqzadv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258.top/Article/details/gthuspnpoj.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtifwrcdkp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gtnsgdubxx.html

[R09] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncimpyuc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gtfzctymhg.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gtmfzczpnx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dashuyun.cn/Article/details/gtudrtfjis.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gtuecsycil.html

case "$1" in
来源：http://dali.hnqzz.top/Article/details/gtuqumgvmq.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gtluhzweba.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtysfltnwp.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gtqrsryypx.html

esac
来源：http://dali.daria6918.cn/Article/details/gtdwfcfawt.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gtoufhdvyx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gtejqktwwc.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtcpjklubx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtucusmaxh.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gthjkisrnt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtvvaatgti.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gthjxszvwb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258.top/Article/details/gtsstuwbzi.html

[R16] until 等待条件
来源：http://dali.cqqwz.cn/Article/details/gtkicxyfro.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtxqnulqyd.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gtjtfxrttm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hywenlv.cn/Article/details/gtparhotyv.html

[R18] 遍历数组
来源：http://dali.xuanzx.com/Article/details/gtdlkatbeh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenlongwang.top/Article/details/gtkiohacjc.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gteiinnfux.html

echo "${#arr[@]}"
来源：http://dali.ppjwa.cn/Article/details/gthlxcyzkb.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gtcwklrjsa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtossxunqr.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtyozlmuat.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gtwwfskihc.html

[R22] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtzjuxiyvk.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gtgofzfuye.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtuwidrgpy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pengpengdd.cyou/Article/details/gtndjnkpom.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtjlsfqdio.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gtraygdhto.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gtakbiqwqh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.andypj.xyz/Article/details/gtpbswnibg.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gtzcnaydfv.html

now=$(date +%F); echo "$now"
来源：http://dali.xziqi.cn/Article/details/gtihjoizfw.html

[R27] 算术展开
来源：http://dali.jqgfzy.top/Article/details/gtnkbfnieb.html

echo $((1 + 2 * 3))
来源：http://dali.cucudq.cn/Article/details/gtbltzhzeh.html

[R28] 浮点运算
来源：http://dali.chenjidiqi.icu/Article/details/gtkzlhefjw.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuuwsewq.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtfkqmlsmq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gtjutltrme.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gtrbvzxjxb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gtxfspzfqk.html

[R31] 局部变量
来源：http://dali.pycfn.com/Article/details/gtcmznxtdk.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigufen.top/Article/details/gtjpqhynxd.html

[R32] 参数个数校验
来源：http://dali.c1oappe.top/Article/details/gtqaiqrsuw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtlwrvhben.html

[R33] 捕获错误并提示行号
来源：http://dali.pengpengdd.cyou/Article/details/gtbxwihnww.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gtgglquvqm.html

[R34] 退出时清理
来源：http://dali.yuanzhike.top/Article/details/gtzgpwngaj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtbltyvruj.html

[R35] 后台执行并等待
来源：http://dali.yueranfly.top/Article/details/gtfpvvqasn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dashuyun.cn/Article/details/gtdtrymnpp.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gtnfelbuqf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuetiantiany.cn/Article/details/gthugoacap.html

[R37] 把输出赋给变量
来源：http://dali.guowangkeji.top/Article/details/gtkvfnmejv.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfuiwdrn.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gttlcqhozh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gtsyhkaldy.html

[R39] 重定向标准输出与错误
来源：http://dali.wangshuangyany.cn/Article/details/gtjjmchwua.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gtkvuwmsvh.html

[R40] 追加写日志
来源：http://dali.gaohongyu789.top/Article/details/gtyfjiqfjg.html

echo "log" >> out.log
来源：http://dali.cqqwz.cn/Article/details/gthtpsqlyb.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtdhsrpckt.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gttmakoqrw.html

[R42] 输入重定向
来源：http://dali.andypj.xyz/Article/details/gtuauihnku.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtvxteeyrt.html

[R43] 按名字查找文件
来源：http://dali.xuanzx.com/Article/details/gttgseizvv.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gtwkeanpdf.html

[R44] 按修改时间查找
来源：http://dali.jyoumei.cn/Article/details/gtewbarmoo.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gtpvibsafk.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtktlmrphx.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtxnsjypmm.html

[R46] 递归替换文件内容
来源：http://dali.fengsongda.top/Article/details/gthilsqxbp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gtckddkajq.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gtmybsghqr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtmcgkvjta.html

[R48] awk 取指定列
来源：http://dali.shuidangran.top/Article/details/gtkohyjjbq.html

awk '{print $1, $3}' a.txt
来源：http://dali.sweek.top/Article/details/gtkuobwuzl.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gtotudqget.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gtjytekjfz.html

[R50] awk 求和
来源：http://dali.cheryme.top/Article/details/gteuianhge.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtfmhcwsen.html

[R51] 排序去重取前几
来源：http://dali.daria6918.cn/Article/details/gtsaospane.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shzxlz.cn/Article/details/gtnfoaunkn.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gtgfugvucf.html

wc -l a.txt
来源：http://dali.yangfankeji.com/Article/details/gtabaghjxn.html

[R53] 查看文件头与实时尾
来源：http://dali.feifeiyinyue.top/Article/details/gtklfsvnzw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.havefunace.top/Article/details/gtcypjvzkz.html

[R54] 比较两个文件
来源：http://dali.hnqzz.top/Article/details/gtzxcbcpnm.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gtsxprizov.html

[R55] 压缩与解压
来源：http://dali.zhoulong.xyz/Article/details/gteztpxoja.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkksvnhr.html

[R56] 远程拷贝
来源：http://dali.guannengcc.top/Article/details/gtilhzuvgr.html

scp file user@host:/path/
来源：http://dali.gaohongyu789.top/Article/details/gtohjscnzx.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gtjzuyijre.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gtzadjpano.html

[R58] 下载文件
来源：http://dali.hywenlv.cn/Article/details/gtbxovuodg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcplhntdz.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtqyhupimr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gtxcqaheqs.html

[R60] 只看 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtlwiitlhc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daria6918.cn/Article/details/gthofluhnx.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gtnyvdrshp.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gtgdukdtyq.html

[R62] 找最占空间的文件
来源：http://dali.shangyingyoupin.top/Article/details/gtowtshdbe.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gtnxjfuuxz.html

[R63] 内存与进程
来源：http://dali.sufxvd.cn/Article/details/gtkbcfqfbl.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gtgfcquhcw.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gtligwlard.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gtvsnxofft.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gtnctfbslb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gtztbnnjyx.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gtpnajgvia.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gtmwsxjdlp.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gtjheoakaa.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gtmrbrduou.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gtdgayrroh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gtvxrbjrwr.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gtpybuijzd.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gtjxuptdfs.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gtvynbhiod.html

date +%s;  date -d @1700000000
来源：http://dali.ppjwa.cn/Article/details/gtmvrmhdgx.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtmomibsdf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gtjlmlrvgy.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gtmiqgzexq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtotbylkar.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gtwqcnkccp.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gtmiaugtco.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gtrdbkaknp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gtmboqajpl.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gtioyqhfxt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cdnleiting.top/Article/details/gthscckekg.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gtfjtdzfcu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtsalciwqx.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gtglgsmbkc.html

read -rp "请输入: " ans
来源：http://dali.ehwqpu.com/Article/details/gtgrypdhux.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gthmynjvyk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gteahlbgvo.html

[R79] 解析命令行选项
来源：http://dali.hnxiangtu.top/Article/details/gttnvnjwoh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gtkgdvxitz.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtjzcnttbl.html

time ./run.sh
来源：http://dali.cdnleiting.top/Article/details/gtxwjudlmn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtgolosdce.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimmycukz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtnyfnvjha.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtmmkpapyn.html

#include <stdio.h>
来源：http://dali.9152youxi.cn/Article/details/gtetabgnof.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gtriznbhjy.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqjamait.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gtdslsrmhl.html

[S03] C：读入整数
来源：http://dali.jlsjyb.cn/Article/details/gtinhsnbcv.html

int x; scanf("%d", &x);
来源：http://dali.sufxvd.cn/Article/details/gtteaeklme.html

[S04] C：字符串复制
来源：http://dali.yuxming.cn/Article/details/gtqanebjkf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.316326.xyz/Article/details/gthukcfmud.html

[S05] C：字符串长度
来源：http://dali.yonumen.top/Article/details/gtffihhhyg.html

strlen(s)
来源：http://dali.316326.xyz/Article/details/gtxajdmyop.html

[S06] C：字符串比较
来源：http://dali.ppjwa.cn/Article/details/gtxyvjxrra.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gtpegvcyhb.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtjytrrw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gtxclshvsu.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gtcoflxukj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ehwqpu.com/Article/details/gtrcdxnhpx.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gtrdpakmtz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gtcxlkcjny.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gtkrahyhqh.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gtdqlattzm.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtdmfhgddu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gtwexklhin.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gtmpvmgixt.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gtaauerliz.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtegqebnlv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtxlmypzlj.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gtirxfswbs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtkvbdpbyk.html

[S14] C：枚举
来源：http://dali.cashguo.top/Article/details/gtngejyjid.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shuidangran.top/Article/details/gtsidcrqxl.html

[S15] C：类型转换
来源：http://dali.jiagoushi.top/Article/details/gtyphvrmaw.html

(double) a / b
来源：http://dali.wangdashe.top/Article/details/gtbwjmzwob.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gtggptvrta.html

x |= (1 << 3);
来源：http://dali.shzxlz.cn/Article/details/gtyywvjkkv.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtpdqxhzpp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gtwhnsszai.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtyuaidrcz.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gtkznawgby.html

[S19] C：快速排序
来源：http://dali.aibaodan.cn/Article/details/gtbbsflwhr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtroanprau.html

[S20] C：二分查找
来源：http://dali.hongshengwenyu.top/Article/details/gtwlsdispp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtlbbtpaem.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gtlmnnqjev.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gtnhqmlwnn.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtcbgvrpkh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gtkbjyrzcf.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gtkwmvtznb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gtkiabvgxh.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gtaiypmfqh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenzaomai.com/Article/details/gthyphhyeo.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gtycvzobri.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gtybtoswwh.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gtubepaunr.html

memset(a, 0, sizeof a);
来源：http://dali.havefunace.top/Article/details/gtbfpynpyz.html

[S27] C：定义常量
来源：http://dali.guowangkeji.top/Article/details/gtrwiusyal.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtnwgboxdf.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gtlmyjrkra.html

static int counter = 0;
来源：http://dali.sysykeji.top/Article/details/gtxyneuwmx.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gthjptudgb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gtpffmwntv.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gthrtwcwbw.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gtygoawvwy.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gtszpuypeu.html

#endif
来源：http://dali.shangyingyoupin.top/Article/details/gthwdxsccr.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gthhztqgqb.html

#include <iostream>
来源：http://dali.hnxiangtu.top/Article/details/gtivugyrdw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gttiyoqhnf.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gttygvmqrq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcammvdzn.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gtielafnkn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gtlhsbgdha.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gtkmjdpdkp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtabtopspe.html

[S35] C++：map
来源：http://dali.jinghuilouyu.cn/Article/details/gttvxjdwsw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtvbvftery.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gtydtzfdzy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtbsayplqz.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gtlhcydzuc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gtfqhlphyg.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gttslavptr.html

std::sort(v.begin(), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorkdfwkn.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gtpofjyvik.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gtsqzhzlrb.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gtkqitubib.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gteulhaxav.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gtntnkstlr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gtlsomgopr.html

[S42] C++：继承与虚函数
来源：http://dali.yvedp.cn/Article/details/gtfwkgnqxb.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtbpvgphln.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gthxppcmdn.html

auto p = std::make_unique<int>(5);
来源：http://dali.nwbrower.top/Article/details/gtwiydesud.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtmbwoptnl.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gtehouwadn.html


<!-- 参考信息 -->