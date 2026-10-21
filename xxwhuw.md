代发 wailian999

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gtpseaiuef.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xylfe.cn/Article/details/gtfttfgrqk.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtjmlzfcaa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gtyxuitkeu.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gtcpnzcwhy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtvhnkoefa.html

[Q81] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtmznurzeq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gtzhymbifa.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gtaqikrori.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtnimzvfvf.html

[Q83] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtvojuzvjs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcuviyhc.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gtgpzibjjp.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtwccgwvnv.html

[Q85] 数值取整
来源：http://dali.hnqzz.top/Article/details/gtyxkzuevn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gtaunamncl.html

[Q86] 读取 JSON 字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugmxuder.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zycfv.cn/Article/details/gtmutgucxq.html

[Q87] JSON 字段做条件
来源：http://dali.gotoacloud.top/Article/details/gtzwdbxpqi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yueranfly.top/Article/details/gtrqykmhbp.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gtnzsobjpd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gtblxzexgx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtospnmxpw.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gtrgrhskly.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gtvetpgjsy.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gtpvuxtgpr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuanzhike.top/Article/details/gtcngxvxdi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttpcvdofl.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtoxxeumhf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtcnngxlcs.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gtdcykitnn.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gtrodfsaot.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gtlwfmasno.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gtaxlaozic.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gtvqpkqdxl.html

[R03] 只读变量
来源：http://dali.dianchejie.cn/Article/details/gtognttjkm.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gtqazbqjxz.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gtjujzxbro.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gthktesiap.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gtvdwijliq.html

name="${1:-default}"
来源：http://dali.gotoacloud.top/Article/details/gtludgzfxj.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtayuqygsf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtzqcwngxp.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gtacyspfoh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gtjisfumjc.html

[R08] 数值比较
来源：http://dali.nanxinkj.top/Article/details/gtfescjdpr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtfrxfvpot.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtdgaomama.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gtsngajiff.html

[R10] 正则匹配
来源：http://dali.yongpay.top/Article/details/gtqargufhw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtajpaoxus.html

[R11] case 多分支
来源：http://dali.zdqjudy.top/Article/details/gtupapayrm.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gtjwzglwrq.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfizsvgr.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtwoyvvvyj.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gttjmtiavr.html

esac
来源：http://dali.sufxvd.cn/Article/details/gtugqplmxv.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gtrdoamjii.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gtnhdygroe.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtjoqlmccm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gtjfuosnze.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqvkzgkm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtsyfuwbnv.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtehmddsdc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhongyouzk.top/Article/details/gtsdviugzo.html

[R16] until 等待条件
来源：http://dali.dianchejie.cn/Article/details/gttqzvrwyp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtwbfcnqhx.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gtuxdkwdxo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtsezadbwe.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdoacftq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gtrtvtvwdi.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gteroxqozv.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gtwmpdeipw.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gtsobjmstz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gtoyqtrmxu.html

[R21] 字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfqghvhn.html

echo "${#s}"
来源：http://dali.hfpthk.cn/Article/details/gtnltnhkqq.html

[R22] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtcjlxmodm.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gtzdouxrsv.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtdqlcbzcc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gtpicspngi.html

[R24] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtfqnkfdgj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gtmfmunehs.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gturnfuiha.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gtiyztihpo.html

[R26] 命令替换
来源：http://dali.ehwqpu.com/Article/details/gtshblrcxu.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gtixnwdohm.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtopalzlkh.html

echo $((1 + 2 * 3))
来源：http://dali.nwbrower.top/Article/details/gtrkjsklno.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gtvahcidhr.html

echo "scale=2; 10/3" | bc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltmolfsh.html

[R29] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gthvhxtetk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258888.top/Article/details/gthqaxbyht.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodcjrsch.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daria6918.cn/Article/details/gtwonhkqiy.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjthqhixi.html

f() { local x=1; echo "$x"; }
来源：http://dali.daxiang520.top/Article/details/gtybxzjxuv.html

[R32] 参数个数校验
来源：http://dali.jinqigufen.top/Article/details/gtvubjexbw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtmaeupapm.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gthunuagnl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gtzhpctieu.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtgbavnhuc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtvgtbtubi.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gtkaoftkyu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gtnmapiqwx.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gtjzoluktz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gtcucwwfxu.html

[R37] 把输出赋给变量
来源：http://dali.tanke756.top/Article/details/gtstiwfdic.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gtjejltnrk.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gtladhltsd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gthxtvzdrv.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gtnecrrysg.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtnpyjgjux.html

[R40] 追加写日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapecexqo.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gtkrkyxmxn.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtufqiodyn.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gttwfnzdzg.html

[R42] 输入重定向
来源：http://dali.zhoulong.xyz/Article/details/gttzafazjv.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gttenrehol.html

[R43] 按名字查找文件
来源：http://dali.fengsongda.top/Article/details/gtovtxobkw.html

find . -name "*.log" -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnslnhxfh.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gtazwbvkjk.html

find . -mtime -7 -type f
来源：http://dali.shuidangran.top/Article/details/gtqmksritn.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gtmabcrwnh.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhukbcqp.html

[R46] 递归替换文件内容
来源：http://dali.daria6918.cn/Article/details/gtdsfdgzxe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gtkqlqewia.html

[R47] sed 单行替换
来源：http://dali.aibaodan.cn/Article/details/gtmlyifhzw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gtbkzamsjv.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gtufpicnpd.html

awk '{print $1, $3}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gterbyoecs.html

[R49] awk 带条件
来源：http://dali.yangfankeji.com/Article/details/gtclmxfmrg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zdqjudy.top/Article/details/gtdtqljhan.html

[R50] awk 求和
来源：http://dali.yongpay.top/Article/details/gtwjddvkcj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtcxjzqmyq.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gtxwzjbgbx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtegyyaqlb.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gtzresgqtv.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtcstefczv.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gttqsrcmnk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dashuyun.cn/Article/details/gtgkxcbsit.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gtbfyelenf.html

diff a.txt b.txt
来源：http://dali.pycfn.com/Article/details/gthscyctkb.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gtiwwgwxss.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvruzogt.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gtrbtfcwzj.html

scp file user@host:/path/
来源：http://dali.pycfn.com/Article/details/gtxnocczgq.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gtqmjtmjks.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gteawkbzrq.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gttczwbhig.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.iojbl.cn/Article/details/gtkxazbbbc.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gtcnybcqxe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.kuanghao11.cn/Article/details/gtnlukgbca.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtfkgjqzyw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gtzlgmfmew.html

[R61] 磁盘占用
来源：http://dali.hnxiangtu.top/Article/details/gtosziviwy.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gtqlttmwrj.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gtbbvetqso.html

du -ah . | sort -rh | head -10
来源：http://dali.shangyingyoupin.top/Article/details/gtlcsceyfy.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtguwqmfci.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gtnyvqrbtx.html

[R64] 结束进程
来源：http://dali.andypj.xyz/Article/details/gtjysvgibw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gtvxcbtfow.html

[R65] 查看端口占用
来源：http://dali.zdqjudy.top/Article/details/gttiznygto.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtfcjjgbcd.html

[R66] 定时任务
来源：http://dali.c1oappe.top/Article/details/gttqshbtyw.html

crontab -e;  crontab -l
来源：http://dali.snrcjt.cn/Article/details/gtciyyvckf.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixzabgdn.html

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gttyhfgybz.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gtcxweirnq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gtzghcmjwl.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gtokxaeith.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gtycjphfnb.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gtgbmbikyt.html

date +%s;  date -d @1700000000
来源：http://dali.aizwys.cn/Article/details/gtlcisyfuo.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtyjlkydkc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gtaqzjshdv.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gtyyzllbmr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmdkpzru.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gtztsyeskq.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtmwyfexnh.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gthwdudfir.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gtwtkzijqo.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gtnaoasxxe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gtalxgxbmq.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gthiarfmax.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtaxjzgtny.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gtowskaavi.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gtujptoenp.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gtaxzfamfe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuetiantiany.cn/Article/details/gtgnlrdqsd.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gthsqekvnx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gtfukovvjb.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggwgktln.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gthihkyvxo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvnfmiygy.html

S. C / C++ 专题
来源：http://dali.9152youxi.cn/Article/details/gtddmwtioc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssxzjlki.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gtmeeyjyvo.html

#include <stdio.h>
来源：http://dali.aizwys.cn/Article/details/gtcrxferwa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gtynrvdote.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gtoupoouzy.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gtehsrqlfc.html

[S03] C：读入整数
来源：http://dali.fzhhl.top/Article/details/gtyyehbqvr.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gtpgbjkwxf.html

[S04] C：字符串复制
来源：http://dali.0kj1m.cn/Article/details/gtmgxypfku.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gtnxxkmyvl.html

[S05] C：字符串长度
来源：http://dali.cucudq.cn/Article/details/gtsgnlobfr.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtzgfksjlj.html

[S06] C：字符串比较
来源：http://dali.yj20258888.top/Article/details/gtubfzhdqu.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gtebyipohl.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gtdylixmzv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gtgxfauojp.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtfysvwplh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttogarrlm.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gtszmhgfqf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigufen.top/Article/details/gttsyoukzg.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtmwprpyyr.html

int *p = &a;  *p = 5;
来源：http://dali.dianchejie.cn/Article/details/gtnoqmzqnu.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtzisllchf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtnifxgprt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gtiqwmsaws.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gtnommdrxi.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gtkofaknnu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtxidoidnw.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gttleieedv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gtftcuunux.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gtflwoywqh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmouysxjf.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gtlljaozie.html

(double) a / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtocquqlmw.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gtesdazqxm.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gtfogsicmb.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtazslktvd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhongyouzk.top/Article/details/gtdchmnoas.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gthyyclxcv.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gtkkdoccsh.html

[S19] C：快速排序
来源：http://dali.ehwqpu.com/Article/details/gtnjsvfuqv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtjwsecmtz.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gtvmgqoxls.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtwnctrwqc.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gtlpamvofz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ivvv.top/Article/details/gtkqnqudye.html

[S22] C：字符串转数字
来源：http://dali.fengsongda.top/Article/details/gtnelnftdc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gtgjylyhft.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gtpcpbnfhc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gtghnntgxp.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpttmeayg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gtefpfnwfm.html

[S25] C：内存拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhslixhe.html

memcpy(dst, src, n);
来源：http://dali.feifeiyinyue.top/Article/details/gtfogbufhu.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gtwqtiehxc.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gtxwermnof.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gtialtmcpi.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtgpwmxwas.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudaoqxwy.html

static int counter = 0;
来源：http://dali.quarkkingdee.top/Article/details/gtwiraykct.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gtsspmqdlb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ydzc1.top/Article/details/gtmjquundn.html

[S30] C：头文件保护
来源：http://dali.nwbrower.top/Article/details/gtjehsdjfj.html

#ifndef X_H
来源：http://dali.hysaishi.cn/Article/details/gteocglmsp.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gtajdubgxh.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gtiqtonker.html

[S31] C++：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtrvaidmvg.html

#include <iostream>
来源：http://dali.zycfv.cn/Article/details/gtilbhogqr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttywldfxw.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gtggzhvced.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtelhrlzcu.html

[S33] C++：vector 增删
来源：http://dali.tian-w.cn/Article/details/gtyiqmufqr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gtnejcthou.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gtdjsorjlw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzyzatjrt.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gtdaovlteq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpsezvme.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gtzbozouso.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtoewilhgc.html

[S37] C++：set
来源：http://dali.ehwqpu.com/Article/details/gtfcputdja.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtynylwnjc.html

[S38] C++：排序
来源：http://dali.zhiwuduotai.top/Article/details/gtgqamvwdt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtgockjafv.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gtcmydcudb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gtzcegrvat.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gthjvizsia.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gthjeafmxh.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtiyjurzjm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shuidangran.top/Article/details/gtalxlnxee.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gttlaqlvrz.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gtjbzjromc.html

[S43] C++：智能指针
来源：http://dali.jianghu66.top/Article/details/gtmlilbhln.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gtansidnqh.html

[S44] C++：引用传参
来源：http://dali.hfpthk.cn/Article/details/gtakoqetdx.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gtgbpsmcbf.html

[S45] C++：lambda
来源：http://dali.andypj.xyz/Article/details/gtcjucvzvh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gtlirksxcd.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gtiuwuxoyi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gtgzifekej.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtpecrjryy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gtrupogodu.html

[S48] C++：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtbfbbgokj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gtmhtkqlce.html


<!-- 参考信息 -->