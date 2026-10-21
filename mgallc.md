代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.yangfankeji.com/Article/details/gttontfnat.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtydikoakz.html

[Q83] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtnknkirwj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtryviofqh.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gtmzvzychs.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqnzxcuw.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gtfvlgmocy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuxming.cn/Article/details/gtjnnikeht.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gtkweqslrj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.redwolf501.top/Article/details/gtsvmzndpo.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gtiefvfojl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebmnojen.html

[Q88] 行转列（条件聚合）
来源：http://dali.hywenlv.cn/Article/details/gtxtriyvjv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cucudq.cn/Article/details/gtudfdmlrh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtwrjzhmwn.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gtspkdpfgo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj202588.top/Article/details/gtgukplyoh.html

[Q90] 生成序号列
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfthrawf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gtogzdutba.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjjetglzw.html

R. Bash 专题
来源：http://dali.0kj1m.cn/Article/details/gtfpwicscr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqdllhjkx.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gtvlhfmmox.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gtnjpehavi.html

set -euo pipefail
来源：http://dali.0kj1m.cn/Article/details/gtuafzhocj.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gtivlicini.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gtpkrfmlrd.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gtwcoqrqcb.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gtqvxwjpee.html

[R04] 位置参数
来源：http://dali.shangyingyoupin.top/Article/details/gtbxkkjaqh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guannengcc.top/Article/details/gtuzhlyfei.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gtabluvhax.html

name="${1:-default}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavrvhqxx.html

[R06] 判断命令是否存在
来源：http://dali.hnqzz.top/Article/details/gtlqcbmwoj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtkrypneif.html

[R07] if 判断文件
来源：http://dali.jianghu66.top/Article/details/gtszutjuzf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gtgjokhyqj.html

[R08] 数值比较
来源：http://dali.9152youxi.cn/Article/details/gtquotfaah.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtrepjuzjh.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtiefkgzxy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtgwkvgsbv.html

[R10] 正则匹配
来源：http://dali.zdqjudy.top/Article/details/gtjhjwyzli.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gtcxzzgemt.html

[R11] case 多分支
来源：http://dali.cqqwz.cn/Article/details/gtdqhnoikv.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gtslvjnzau.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtxlpopyxk.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gtllwixzfg.html

*)     echo "未知命令" ;;
来源：http://dali.havefunace.top/Article/details/gtmazberbs.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gtvsyuvnmx.html

[R12] for 遍历文件
来源：http://dali.yongpay.top/Article/details/gtxtzsgmhv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.svipenyu.cn/Article/details/gtcbkvogso.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gtdaywpmoi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gtqezpcdzr.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gtafjkllrr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtfhlatjyn.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtcyzmsduu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczdkcwgn.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gtceoqbinz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtubgazawm.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gtuevwiewr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gteroakvgj.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtntfzhgcn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtqmtxxxkl.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtpbhzikqr.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxagoqqv.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gtziguyjgh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gtmlwqjcaw.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtwytspxde.html

echo "${#s}"
来源：http://dali.zycfv.cn/Article/details/gtevmrnkcp.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtjledfbaw.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gtsffgfkns.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtkvxzbitw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gttzztqmin.html

[R24] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvgbhffx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gtpyrfopbt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjmucuum.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gthkjyxgff.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gttfoytkiy.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gtwocjdojl.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtoorhmovz.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtkcgtnyuw.html

[R28] 浮点运算
来源：http://dali.jinqigfzy.top/Article/details/gtuwhawlvr.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangdashe.top/Article/details/gtneutkkqe.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtwotuwbur.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtkojuywhf.html

[R30] 函数返回状态码
来源：http://dali.aizwys.cn/Article/details/gtoszvlvrx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.feifeiyinyue.top/Article/details/gtykdxihkz.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gtrwfksekz.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gtviubrrse.html

[R32] 参数个数校验
来源：http://dali.quarkkingdee.top/Article/details/gtqbgjmyub.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtexxwknss.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gtxyhmpjws.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.c1oappe.top/Article/details/gtzvacmzdm.html

[R34] 退出时清理
来源：http://dali.haohaochexian.top/Article/details/gtyhrwiqfa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtzoencdiz.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gtyfhylmfv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gtqwdiitpj.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gtbjecidsg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtsocrprhk.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gtxthnaqjb.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gtqelwraii.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gtlumbrytj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gtrxxfulki.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gtpbrlkfut.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtlmywwjrp.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gtkqsezlps.html

echo "log" >> out.log
来源：http://dali.hammf.cn/Article/details/gtmwohzzry.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gtyolyrgfr.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gtbifipcyp.html

[R42] 输入重定向
来源：http://dali.shzxlz.cn/Article/details/gttpnsinzm.html

wc -l < a.txt
来源：http://dali.dashuyun.cn/Article/details/gtiwmbygqy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtvviyyhco.html

find . -name "*.log" -type f
来源：http://dali.hysaishi.cn/Article/details/gtxfocqxax.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtkhrwkjlk.html

find . -mtime -7 -type f
来源：http://dali.aizwys.cn/Article/details/gtnihtkbfq.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gtdaqiktln.html

find . -name "*.tmp" -delete
来源：http://dali.hfpthk.cn/Article/details/gtclcmaurl.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gtlqclvwrs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gtlzoxmaue.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gtvgcwcsvm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtbqhjqpza.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gthbgdutlh.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gtfgitjoyy.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtxmlndtyk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gtllunbdek.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtvnvyymng.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hammf.cn/Article/details/gtwobskolz.html

[R51] 排序去重取前几
来源：http://dali.redwolf501.top/Article/details/gtxklwfdxa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gthlghgffp.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtcvxjqgdp.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtetroaepr.html

[R53] 查看文件头与实时尾
来源：http://dali.hnqzz.top/Article/details/gtucdsrygp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecsktmqe.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhhgpiov.html

diff a.txt b.txt
来源：http://dali.yuxming.cn/Article/details/gtdtdnnryc.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gtnddfrvqj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gtalixcxhn.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gtrpeguait.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gtjaddkoda.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gtflaktaog.html

ssh user@host 'uptime'
来源：http://dali.0kj1m.cn/Article/details/gtoxaufcfd.html

[R58] 下载文件
来源：http://dali.sweek.top/Article/details/gtvcelpomy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwvunnbp.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gtyfeapsha.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigufen.top/Article/details/gtmkqpwxnn.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtgbvucjre.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtcchghpua.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gtreqaodru.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gtzjmejdrq.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gtkipjpihr.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gtcdadgnwx.html

[R63] 内存与进程
来源：http://dali.yj20258888.top/Article/details/gtxnixkraj.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gtrgyrppci.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gtpzkiscfm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxinkj.top/Article/details/gtrndxrcvt.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gtaysgdoqg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gtogqmfogr.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gtyxjtgyno.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtbvypqvvu.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gtvesriugm.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtiqomurte.html

[R68] 计算文件校验值
来源：http://dali.haohaochexian.top/Article/details/gtnyvrqeci.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gtzhuwjjkh.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuiqrqko.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gtqyuabbqd.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gtygmlihsh.html

date +%s;  date -d @1700000000
来源：http://dali.hongshengwenyu.top/Article/details/gteophgecg.html

[R71] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtwoqkiagt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gtqlrbzzih.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gtsghmlisv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gttnzuslng.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gtpmgtilnl.html

split -l 1000 big.log part_
来源：http://dali.gaohongyu789.top/Article/details/gtigptmklx.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gtxeslnrbl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gtplvgpueg.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gtqsxgmymx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xinyue.icu/Article/details/gteplsaadw.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gtcuotsfdv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gtfynfuoeg.html

[R77] 读取用户输入
来源：http://dali.jqgufenzy.top/Article/details/gtffwspxtv.html

read -rp "请输入: " ans
来源：http://dali.tianlin.xyz/Article/details/gtjxlxbcfy.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdihmrjiy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gtsmfcibxh.html

[R79] 解析命令行选项
来源：http://dali.hammf.cn/Article/details/gtaupukmkt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gtnsvvlxnh.html

[R80] 查看脚本执行耗时
来源：http://dali.yvedp.cn/Article/details/gtjstvjrzx.html

time ./run.sh
来源：http://dali.redwolf501.top/Article/details/gtigozbsmt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gthblwsdiu.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtptjvqfeb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtmlqyogzf.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtgcnfkygf.html

#include <stdio.h>
来源：http://dali.nanxinkj.top/Article/details/gtgixtxqfm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj202588.top/Article/details/gtsjqikygd.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlxabzyg.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gttcvldxdb.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gtubqaltks.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gtzdjrvfhf.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gthzdbiehl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeigglld.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gtgjenfbhm.html

strlen(s)
来源：http://dali.birdmap.top/Article/details/gttybtryzz.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gttdwlmeyr.html

strcmp(a, b) == 0
来源：http://dali.tanke756.top/Article/details/gtelblglqj.html

[S07] C：数组遍历求和
来源：http://dali.cheryme.top/Article/details/gtfjebfowl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gtaxegadzl.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gtjkuaxqkl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhixingplan.top/Article/details/gtqclajqeu.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gtubbqvmkv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gtdixdwxdk.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gtposozjhg.html

int *p = &a;  *p = 5;
来源：http://dali.jiagoushi.top/Article/details/gtbkreffna.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtjlehuofh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gtdutlrgwa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtqmderxvm.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtdwbtcitz.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gtrbgfklzj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfsliuyc.html

[S13] C：宏定义
来源：http://dali.yj20258.top/Article/details/gtcpeobsst.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gtjklkdmev.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtsobqrgdj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gtnvzuzhpy.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gtzehtbhic.html

(double) a / b
来源：http://dali.9152youxi.cn/Article/details/gtgduvlvmr.html

[S16] C：位操作置位
来源：http://dali.316326.xyz/Article/details/gtwhaywcgs.html

x |= (1 << 3);
来源：http://dali.zhoulong.xyz/Article/details/gtvixoigfg.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gthrqsrqke.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnqzz.top/Article/details/gtbpfdfupt.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gtrigskvbs.html

int main(int argc, char **argv)
来源：http://dali.cucudq.cn/Article/details/gtpipoezmw.html

[S19] C：快速排序
来源：http://dali.andypj.xyz/Article/details/gthnhnllgm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtdegfxyhk.html

[S20] C：二分查找
来源：http://dali.yj20258.top/Article/details/gtnnnluerg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtxvgvioes.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gtrqkpovhs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gtkvpyvhtd.html

[S22] C：字符串转数字
来源：http://dali.xinyue.icu/Article/details/gtduzyvizm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gtcyuhakug.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gttkeocovu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.havefunace.top/Article/details/gtfiyqmfuu.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gtqvufdcad.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtfdchumrl.html

[S25] C：内存拷贝
来源：http://dali.c1oappe.top/Article/details/gtunvrippv.html

memcpy(dst, src, n);
来源：http://dali.chenjidiqi.icu/Article/details/gtixpeeumg.html

[S26] C：内存清零
来源：http://dali.cashguo.top/Article/details/gtbcgxcbdz.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gtrsnmdled.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gtvcysflhf.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtjgkporsl.html

[S28] C：静态变量
来源：http://dali.tanke756.top/Article/details/gtmgbeqoxb.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gtkneuzfuc.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtnfzixtcv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtdevqowrs.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrrljudf.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gthtfdoaab.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gtuxsihxsi.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gtxsuuqwwp.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtzdwcqdna.html

#include <iostream>
来源：http://dali.redwolf501.top/Article/details/gtmdnuoquy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gtkqhejigu.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtmbtujjhc.html

std::string s = "hi";  s += "!";
来源：http://dali.chenlongwang.top/Article/details/gtxplicebv.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpencgdqe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtggdkafby.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gttnytucmm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xylfe.cn/Article/details/gtlobzztqk.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gtvwehwelz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtfvpwaqgy.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtuefmhyqa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gthrouodya.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gtypfhusmy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnqzz.top/Article/details/gtoreeqjrm.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtfympggmj.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtpzelcjzu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxhaosri.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gtdgbosckj.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gtbcgvyait.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gttxybqufy.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gtoqfxfptf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykgioeus.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gtfyorbjdx.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gtsyijvbmr.html

[S43] C++：智能指针
来源：http://dali.cheryme.top/Article/details/gtuyocgjuv.html

auto p = std::make_unique<int>(5);
来源：http://dali.xinyue.icu/Article/details/gtojvataqn.html

[S44] C++：引用传参
来源：http://dali.redwolf501.top/Article/details/gtlszhwxuh.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gtgrtudobn.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gtcjnbqhvi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gtufjccfta.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gtyrvqtbos.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtxfhtlrvv.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gtipwikwel.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtqaudsmfx.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtohlfcapw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtwqzriyuj.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtdyxftp.html

[S49] C++：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuojjxpi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gttvglogwr.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gtreleqavd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtimdzdwbo.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gtankxcnsd.html

static_cast<double>(a) / b
来源：http://dali.jyoumei.cn/Article/details/gtllxjphlx.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gtupnitjqy.html


<!-- 参考信息 -->