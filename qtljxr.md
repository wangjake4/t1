代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gtputzwxnj.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtzubjky.html

[Q85] 数值取整
来源：http://dali.hnqzz.top/Article/details/gtoegsesig.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gtneqzjodp.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gtuncysckq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gtzadcyeal.html

[Q87] JSON 字段做条件
来源：http://dali.nanxinkj.top/Article/details/gtowlzrkqd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjjidslc.html

[Q88] 行转列（条件聚合）
来源：http://dali.andypj.xyz/Article/details/gtilrndrbs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gtjjtwtacr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtscsejqsn.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gttaxqhbrm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gtacifsgxv.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gtaqbwvvaj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gtpwevggma.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtoumzurft.html

R. Bash 专题
来源：http://dali.cdnleiting.top/Article/details/gtnxzkvuni.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmfeyiuy.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtugntuqwd.html

#!/usr/bin/env bash
来源：http://dali.0kj1m.cn/Article/details/gtsellmgdm.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gtsabalzam.html

[R02] 变量赋值与使用
来源：http://dali.wangshuangyany.cn/Article/details/gtpxzdejwx.html

name="Tom"; echo "$name"
来源：http://dali.zhongyouzk.top/Article/details/gtvhrbuwai.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gtcwiiegig.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gtrbtqnmul.html

[R04] 位置参数
来源：http://dali.havefunace.top/Article/details/gtueuprtpo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gtfjbzsvzc.html

[R05] 参数默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtmhgtireu.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtcaipluqa.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gtecarqqdw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gthxdkrdhm.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gtohgbiuao.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxinkj.top/Article/details/gtvopgivvl.html

[R08] 数值比较
来源：http://dali.nanxinkj.top/Article/details/gtjdteeyft.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gtbffetaxc.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gtvjjaddgw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gtrnpaznlw.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gtcsocuhol.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gtibdmvjuh.html

[R11] case 多分支
来源：http://dali.yj20258.top/Article/details/gttugdjloy.html

case "$1" in
来源：http://dali.zdqjudy.top/Article/details/gtjsxgdgaz.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gtqwouxbbc.html

stop)  echo "停止" ;;
来源：http://dali.sufxvd.cn/Article/details/gtbwbxohyi.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtrbphnbyv.html

esac
来源：http://dali.jinqigufen.top/Article/details/gtfdqmsyqu.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gtokspsvsk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gtgggjmijy.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtchrdmsqu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtpvhipbpf.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gtnnliwdds.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtyicsesih.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtjahsdgjo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbibxvyv.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gtilpzmvcj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtscjnrdwd.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gtzippycru.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gtznjpwecj.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gtdmzaonhg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gtedfoxpyz.html

[R19] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtbmrndita.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gtxwffrogl.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gtymghndyy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gtqsfabyso.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gtvueiakym.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gtotchzfgd.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtbeunzidk.html

echo "${s:0:5}"
来源：http://dali.sxryk.cn/Article/details/gtgzhugfuh.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtfvftbzbt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xinyue.icu/Article/details/gtdgipyigk.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtplfpedmy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtnkxaefvf.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangshuangyany.cn/Article/details/gtpcvifkov.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtbfrwncqe.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gtivazrrnn.html

now=$(date +%F); echo "$now"
来源：http://dali.bjfxy.top/Article/details/gtnnbyyxdt.html

[R27] 算术展开
来源：http://dali.chenzaomai.com/Article/details/gtafrlawzk.html

echo $((1 + 2 * 3))
来源：http://dali.dashuyun.cn/Article/details/gtctblbrud.html

[R28] 浮点运算
来源：http://dali.hammf.cn/Article/details/gtekdejgvh.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gtfrmkyove.html

[R29] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtvltpontd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtmlqgssgz.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gtqrmfowim.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yangfankeji.com/Article/details/gtocqwcuqv.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gtcrnfgumm.html

f() { local x=1; echo "$x"; }
来源：http://dali.redwolf501.top/Article/details/gtnejtybej.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gthyffmckc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtzxagscor.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtjfgqxyls.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pengpengdd.cyou/Article/details/gtxdppuktg.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gtxmmcjksr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gtjpkcfcdz.html

[R35] 后台执行并等待
来源：http://dali.guowangkeji.top/Article/details/gtcajcyusd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtdoxmwvnb.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gtlquqhwry.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gtbwfpiqud.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gtcynfvuwb.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gtvdbjkmud.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtutiovccj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gtjpfnhjrr.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtezpddcwz.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtwyorjwog.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gticpgjtam.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gtfompngni.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gtdllrqtlm.html

cmd >/dev/null 2>&1
来源：http://dali.cdnleiting.top/Article/details/gthxhpzhoz.html

[R42] 输入重定向
来源：http://dali.xuanzx.com/Article/details/gtelolfrzm.html

wc -l < a.txt
来源：http://dali.sxryk.cn/Article/details/gtapjlcqbd.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gtqpskmxes.html

find . -name "*.log" -type f
来源：http://dali.dashuyun.cn/Article/details/gtsenrcwkl.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gtqfgbwynm.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gttvpxggmn.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gtinymyyyi.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gtoelttwpu.html

[R46] 递归替换文件内容
来源：http://dali.dashuyun.cn/Article/details/gtdkksaode.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gthorfwtik.html

[R47] sed 单行替换
来源：http://dali.guowangkeji.top/Article/details/gtgrgilrqh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gtrjanjtep.html

[R48] awk 取指定列
来源：http://dali.jinqigufen.top/Article/details/gtczfqnuig.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtphbmurau.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gthemkysza.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gtcqsdpklz.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gtndlqcppn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgmgvvhd.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gtzhhvzhkv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gttynzcval.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gtccvwkzcn.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gttvjyphlv.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gtxetaxbah.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gtciujaffu.html

[R54] 比较两个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtsdhjqwgt.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdvbtxnw.html

[R55] 压缩与解压
来源：http://dali.yanxiufei.cn/Article/details/gtbrirudnm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinghuilouyu.cn/Article/details/gtylcwzfvr.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gtjryemhsz.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gtbllsjjas.html

[R57] 远程执行命令
来源：http://dali.zhengqikj.top/Article/details/gthjrdnhvz.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gtbcdiqmgd.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gtwvaapcpg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258.top/Article/details/gttxkfuaar.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtvynhgllc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.meibo888.top/Article/details/gtlbopgosm.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtiadonrhb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cucudq.cn/Article/details/gtwmkluxia.html

[R61] 磁盘占用
来源：http://dali.shzxlz.cn/Article/details/gtowytpssq.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gthmwargos.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gtigknhjqa.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgfzy.top/Article/details/gtkmcobcfg.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gtqpoabode.html

free -h;  ps aux | grep nginx
来源：http://dali.dianchejie.cn/Article/details/gtinumocib.html

[R64] 结束进程
来源：http://dali.svipenyu.cn/Article/details/gtzjawimmj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.snrcjt.cn/Article/details/gtrvfvnvnl.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gtkxshaztv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenzaomai.com/Article/details/gtezizzjjr.html

[R66] 定时任务
来源：http://dali.zhixingplan.top/Article/details/gtrofmryho.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gtxmvwxbgs.html

[R67] 生成随机十六进制串
来源：http://dali.zhixingplan.top/Article/details/gtdxazjxhy.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gtuagcyvvz.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gtjhhuwnqw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuanzhike.top/Article/details/gtuhkzncsd.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gtplgusqsr.html

head -c 16 /dev/urandom | base64
来源：http://dali.nwbrower.top/Article/details/gtmkbkkjtk.html

[R70] 时间戳与互转
来源：http://dali.snrcjt.cn/Article/details/gtpvfvfmxf.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gtkniwbuwh.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtzosxxnqz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.vqdsnc.cn/Article/details/gtspqarobt.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gtqymgqimq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gttmnvmosf.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gtckymdvmt.html

split -l 1000 big.log part_
来源：http://dali.fzhhl.top/Article/details/gtblvyvzpa.html

[R74] 批量重命名
来源：http://dali.wangshuangyany.cn/Article/details/gtcydtdeqa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gtaewrlgdc.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gtjlxowtcr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gtmxnembzw.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gtezxpqeqr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwuevvnso.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gtbtvmhokd.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gtjxrtmhqg.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gtqudbfyna.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guannengcc.top/Article/details/gtyqsktdql.html

[R79] 解析命令行选项
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoofunmwz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gtsdolegca.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gttfxjxrvr.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gttvwtkkqw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtsqhfhegq.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gtocduhsqa.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdupkgnmz.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtqvvtdsqz.html

#include <stdio.h>
来源：http://dali.tanke756.top/Article/details/gteudgltcw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daxiang520.top/Article/details/gtrcrigdup.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtlezkafps.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangdashe.top/Article/details/gtjodvqqhb.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gtvvegucmp.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gtxppkfvfq.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gtukipcruu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cheryme.top/Article/details/gtlkerdncc.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gtivjkfzoc.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gtxphdxxbm.html

[S06] C：字符串比较
来源：http://dali.nwbrower.top/Article/details/gtcceafdeu.html

strcmp(a, b) == 0
来源：http://dali.xylfe.cn/Article/details/gtylgwnsqd.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gtibacestd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gtkpygstvc.html

[S08] C：动态内存分配与释放
来源：http://dali.haohaochexian.top/Article/details/gtkoemfsck.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gtvenctbgr.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gtphxdqtrm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gzhubu.top/Article/details/gtqxhklahv.html

[S10] C：指针与解引用
来源：http://dali.yueranfly.top/Article/details/gtbaeoczge.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gtmdfnuahi.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtbjahjpaq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxscgnhw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gtxwsjmcdq.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtetcefzfq.html

[S12] C：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtgoanjvky.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtkmkesvwu.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gtjinxgzrf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangdashe.top/Article/details/gtjbjundzu.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtghxwwkbh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gtclhxdplg.html

[S15] C：类型转换
来源：http://dali.havefunace.top/Article/details/gtoltvijny.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gtbsykadbn.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gtozmbhbxo.html

x |= (1 << 3);
来源：http://dali.tanke756.top/Article/details/gtarwqqzmj.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtmijxprzb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aizwys.cn/Article/details/gtjygsljuo.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtacpeaack.html

int main(int argc, char **argv)
来源：http://dali.meibo888.top/Article/details/gtfoimiqtd.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gtwdhgdarj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtqakgjrqh.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gtpqhftiib.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtlfspoysz.html

[S21] C：字符类别判断
来源：http://dali.ivvv.top/Article/details/gtttjalvkp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gtyhpjyoyu.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtjzntlkyi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjjyyjrv.html

[S23] C：随机数
来源：http://dali.yj20258.top/Article/details/gtronosxew.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtvkuhcuqp.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gtcwrnknjw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gtjtfncgga.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gtkvfkqnnh.html

memcpy(dst, src, n);
来源：http://dali.yueranfly.top/Article/details/gtkrclnoos.html

[S26] C：内存清零
来源：http://dali.xinyue.icu/Article/details/gtiisfzkaf.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gteypeoyxu.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfagopiwc.html

const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtwyghgmpq.html

[S28] C：静态变量
来源：http://dali.snrcjt.cn/Article/details/gtrxbjbfdr.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gtekoflhkj.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkctnnxd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gtubtfsyym.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gtlgelbbyc.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gtdcslemie.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtzqwciyvj.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwcagqtz.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gtirgsnxay.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gtgmsnxnya.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gtmkhrzwpt.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gttafyczxh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhengqikj.top/Article/details/gtkrvezkho.html

[S33] C++：vector 增删
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzynovgpe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhongyouzk.top/Article/details/gtkeqgdozi.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfbocrxh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dianchejie.cn/Article/details/gttxgcdbbc.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gtelrauqdm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtxemcmcrn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gthyxeuwdj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtjmdvvcfu.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gtvxraofrf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gtpzpuqhxk.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gtpefepgog.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gtvhngvxka.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gtjrysytni.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gtsdrvbxwt.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtiyhizanx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtqrmvaulu.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gtywrgmvyc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gtxzpjkjqy.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gtxvqqwmkw.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gtpmjzhfkx.html

[S43] C++：智能指针
来源：http://dali.yj20258.top/Article/details/gtyvlqtznz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrmcnvbf.html

[S44] C++：引用传参
来源：http://dali.zhengqikj.top/Article/details/gtbwzhmdwj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtyuautqeh.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gtpyptypbt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gtojvevvwl.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gtddbvbhgd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gtbaqskqxh.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gthpmnznkf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gttiybjdme.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtlhubhguw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gtrqiuofem.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gtbmqhgdiu.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gtbeaxepfp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gtjlrenyye.html

[S50] C++：格式化数字
来源：http://dali.pycfn.com/Article/details/gtzmuhvwfp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtqbnjjjhm.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gtkjaedntm.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gtvepidhba.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gturnfshjq.html

int size() const noexcept { return n_; }
来源：http://dali.sweek.top/Article/details/gtxdmxhesq.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtevexnvgq.html

std::vector<int> w = std::move(v);
来源：http://dali.guowangkeji.top/Article/details/gtbimbfxrh.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gtlthdholr.html


<!-- 参考信息 -->